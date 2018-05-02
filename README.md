# MiniProfiler.ElasticsearchCore
Put your [Elasticsearch.Net and NEST](https://github.com/elastic/elasticsearch-net) requests timings directly into [MiniProfiler](https://github.com/MiniProfiler/dotnet).

![profiler-popup](https://user-images.githubusercontent.com/3474842/30780873-de83efd8-a11d-11e7-8735-49dea4a1d4f1.png)
![profiler-queries](https://user-images.githubusercontent.com/3474842/30780952-edf8adea-a11e-11e7-8d64-c65331f389bf.png)

## Install
Run the following command in the Package Manager Console (NuGet).
```bash
PM> Install-Package MiniProfiler.ElasticsearchCore
```
## Versions compatibility
| MiniProfiler.Elasticsearch | NEST and Elasticsearch.Net | MiniProfiler | Build Status | NuGet Feed |
| -------------------------- | -------------------------- | ------------ | ------------ | ---------- |
| `6.x` | `6.x` | `4.x` | [![Build status](https://ci.appveyor.com/api/projects/status/qw3w0kb6wthln4hv?svg=true)](https://ci.appveyor.com/project/tunurgitr/miniprofiler-elasticsearchcore) | [![Nuget feed](https://img.shields.io/badge/nuget-v6.0.0-blue.svg)](https://www.nuget.org/packages/MiniProfiler.ElasticsearchCore)

## Usage
Update usages of ``ElasticClient`` or ``ElasticsearchClient`` with their respected profiled version ``ProfiledElasticClient`` or ``ProfiledElasticsearchClient``.
