---
collection: data_sets
type: dataset
nav_order: 2
permalink: "/data_sets/party_statements"
title: 'South Korean Party Statements Corpus (2003-2022)'
---

The South Korean Party Statements Corpus is a collection of official statements from the two major parties in South Korea from 2003 to 2022. The dataset comprises a total of 35,115 entries from the Conservative Party and 48,086 entries from the Progressive Party (83,201 total, 9 variables). It is distributed through `krpoltext` v0.2.0, which supports managed CSV/Parquet artifacts, metadata and schema helpers, and a refreshed static JSON API.

> Lim, T.H. (2025). South Korean Election Campaign Booklet and Party Statements Corpora. *Scientific Data*, 12, 1030. [https://doi.org/10.1038/s41597-025-05220-4](https://doi.org/10.1038/s41597-025-05220-4)

### Access

| Resource | Link |
|----------|------|
| **R Package & Documentation** | [taehyun-lim.github.io/krpoltext](https://taehyun-lim.github.io/krpoltext/) |
| **AI agent (MCP)** | [kr-elections-mcp](https://github.com/taehyun-lim/kr-elections-mcp) &middot; ask in plain language |
| **Static Data API** | [index.json](https://taehyun-lim.github.io/krpoltext/data/index.json) &middot; [metadata.json](https://taehyun-lim.github.io/krpoltext/data/metadata.json) &middot; [schema](https://taehyun-lim.github.io/krpoltext/data/schema/party_statements.json) |
| **OSF Repository** | [doi.org/10.17605/OSF.IO/RCT9Y](https://doi.org/10.17605/OSF.IO/RCT9Y) |
| **GitHub** | [taehyun-lim/krpoltext](https://github.com/taehyun-lim/krpoltext) |
| **Release Notes** | [NEWS.md](https://github.com/taehyun-lim/krpoltext/blob/main/NEWS.md) |

### Quick Start (R)

```r
# install.packages("remotes")
remotes::install_github("taehyun-lim/krpoltext")

library(krpoltext)
ps <- load_party_statements()
metadata("party_statements")
```

### License

Data: [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) &middot; Code: [MIT](https://github.com/taehyun-lim/krpoltext/blob/main/LICENSE.md)
