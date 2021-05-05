# Public API

This repository holds both [OpenAPI specification](/src/main/resources) of `newpathfly` public API, as well as the [generated documentations](/doc) in both HTML and Markdown formats.

## Documentations

- [Search API](/doc/markdown/search/README.md)

- Data API

- Order API

## Important

Generating HTML files and Markdown files under `/doc` folder will not remove any file generated previously.

> For example, if a schema `LegacyAirline` is removed from a OpenAPI yaml file, the corresponding `LegacyAirline.md` markdown file previously generated will never be removed.

Because files are only added, not removed, it is **important** to remove `/doc` folder and generate the documentation files from scratch before checking into the Git repo.
