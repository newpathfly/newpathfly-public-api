# Public API

This repository holds both [OpenAPI specification](/src/main/resources) of `newpathfly` public API.

> **Important:**
>
> The specification files should be copied and checked into [newpathfly/newpathfly.github.io](https://github.com/newpathfly/newpathfly.github.io) for public access after every release.

## Build

Run `mvn clean compile` to build.

> Interfaces and model classes will be automatically generated from the specification files using [openapi-generator-maven-plugin](https://github.com/OpenAPITools/openapi-generator/tree/master/modules/openapi-generator-maven-plugin).
