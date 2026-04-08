---
collection: data_sets
permalink: "/data_sets/individual_manifesto"
title: 'South Korean Election Campaign Booklet Corpus (2000-2022)'
---

The South Korean Election Campaign Booklet Corpus is a collection of manifesto pamphlets of individual candidates who ran for offices in single-member or multi-member districts during six National Assembly elections, six local elections, and five Presidential elections in South Korea between 2000 and 2022. The dataset has 49,678 observations across 31 variables. It is distributed through `krpoltext` v0.2.0, which supports managed CSV/Parquet artifacts, metadata and schema helpers, and a refreshed static JSON API.

> Lim, T.H. (2025). South Korean Election Campaign Booklet and Party Statements Corpora. *Scientific Data*, 12, 1030. [https://doi.org/10.1038/s41597-025-05220-4](https://doi.org/10.1038/s41597-025-05220-4)

### Access

| Resource | Link |
|----------|------|
| **R Package & Documentation** | [taehyun-lim.github.io/krpoltext](https://taehyun-lim.github.io/krpoltext/) |
| **Static Data API** | [index.json](https://taehyun-lim.github.io/krpoltext/data/index.json) &middot; [metadata.json](https://taehyun-lim.github.io/krpoltext/data/metadata.json) &middot; [schema](https://taehyun-lim.github.io/krpoltext/data/schema/campaign_booklet.json) |
| **OSF Repository** | [doi.org/10.17605/OSF.IO/RCT9Y](https://doi.org/10.17605/OSF.IO/RCT9Y) |
| **GitHub** | [taehyun-lim/krpoltext](https://github.com/taehyun-lim/krpoltext) |
| **Release Notes** | [NEWS.md](https://github.com/taehyun-lim/krpoltext/blob/main/NEWS.md) |

### Quick Start (R)

```r
# install.packages("remotes")
remotes::install_github("taehyun-lim/krpoltext")

library(krpoltext)
cb <- load_campaign_booklet()
metadata("campaign_booklet")
```

### License

Data: [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) &middot; Code: [MIT](https://github.com/taehyun-lim/krpoltext/blob/main/LICENSE.md)
