
# Conformance Classes (Schema)

`ogc.api.common.v1.schemas.confClasses` *v0.1*

This building block corresponds to the conformance declaration schema from OGC API - Common - Part 1: Core

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
type: object
required:
- conformsTo
properties:
  conformsTo:
    type: array
    items:
      type: string
      example: http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/core

```

Links to the schema:

* YAML version: [schema.yaml](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/schemas/confClasses/schema.json)
* JSON version: [schema.json](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/schemas/confClasses/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/GeoLabs/bblocks-ogcapi-common](https://github.com/GeoLabs/bblocks-ogcapi-common)
* Path: `_sources/v1/schemas/confClasses`

