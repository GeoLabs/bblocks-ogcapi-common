
# Exception (Schema)

`ogc.api.common.v1.schemas.exception` *v0.1*

This building block corresponds to the exception schema from OGC API - Common - Part 1: Core

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
title: Exception Schema
description: JSON schema for exceptions based on RFC 7807
type: object
required:
- type
properties:
  type:
    type: string
  title:
    type: string
  status:
    type: integer
  detail:
    type: string
  instance:
    type: string

```

Links to the schema:

* YAML version: [schema.yaml](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/schemas/exception/schema.json)
* JSON version: [schema.json](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/schemas/exception/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/GeoLabs/bblocks-ogcapi-common](https://github.com/GeoLabs/bblocks-ogcapi-common)
* Path: `_sources/v1/schemas/exception`

