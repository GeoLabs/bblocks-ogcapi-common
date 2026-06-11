
# Format Parameter (OpenAPI) (Parameter)

`ogc.api.common.v1.parameters.f-openapi` *v0.1*

This building block corresponds to the format parameter for requesting OpenAPI formats

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
name: f
in: query
description: The optional f parameter indicates the output format that the server
  shall provide as part of the response document. The default format is JSON.
explode: false
required: false
style: form
schema:
  type: string
  default: json
  enum:
  - json
  - html

```

Links to the schema:

* YAML version: [schema.yaml](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/parameters/f-openapi/schema.json)
* JSON version: [schema.json](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/parameters/f-openapi/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/GeoLabs/bblocks-ogcapi-common](https://github.com/GeoLabs/bblocks-ogcapi-common)
* Path: `_sources/v1/parameters/f-openapi`

