
# Server Error Response (Response)

`ogc.api.common.v1.responses.ServerError` *v0.1*

This building block corresponds to the server error response (500) from OGC API - Common - Part 1: Core

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: A server error occurred.
content:
  application/json:
    schema:
      $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/schemas/exception/schema.yaml
  text/html:
    schema:
      type: string

```

Links to the schema:

* YAML version: [schema.yaml](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/responses/ServerError/schema.json)
* JSON version: [schema.json](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/responses/ServerError/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/GeoLabs/bblocks-ogcapi-common](https://github.com/GeoLabs/bblocks-ogcapi-common)
* Path: `_sources/v1/responses/ServerError`

