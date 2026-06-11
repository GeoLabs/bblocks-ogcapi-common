
# API Definition Path (Path)

`ogc.api.common.v1.paths.ApiDefinition` *v0.1*

This building block corresponds to the API definition path (/api) from OGC API - Common - Part 1: Core

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
get:
  summary: This document
  description: This document
  tags:
  - server
  parameters:
  - $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/parameters/f-openapi/schema.yaml
  responses:
    '200':
      $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/responses/ApiDefinition/schema.yaml
    '400':
      $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/responses/InvalidParameter/schema.yaml
    default:
      $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/responses/ServerError/schema.yaml

```

Links to the schema:

* YAML version: [schema.yaml](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/paths/ApiDefinition/schema.json)
* JSON version: [schema.json](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/paths/ApiDefinition/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)
* [OGC API - Common - Part 1: Core - OpenAPI 3.0 Requirements Class](https://docs.ogc.org/is/19-072/19-072.html#_ab6e3c2d-d2dc-4f01-a7d4-8b52133289a0)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/GeoLabs/bblocks-ogcapi-common](https://github.com/GeoLabs/bblocks-ogcapi-common)
* Path: `_sources/v1/paths/ApiDefinition`

