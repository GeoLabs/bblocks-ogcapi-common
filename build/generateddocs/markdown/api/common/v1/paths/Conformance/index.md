
# Conformance Path (Path)

`ogc.api.common.v1.paths.Conformance` *v0.1*

This building block corresponds to the conformance declaration path (/conformance) from OGC API - Common - Part 1: Core

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
get:
  summary: API conformance definition
  description: A list of all conformance classes specified in a standard that the
    server conforms to.
  operationId: getConformanceDeclaration
  tags:
  - server
  parameters:
  - $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/parameters/f-openapi/schema.yaml
  responses:
    '200':
      $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/responses/ConformanceDeclaration/schema.yaml
    '400':
      $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/responses/InvalidParameter/schema.yaml
    '500':
      $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/responses/ServerError/schema.yaml

```

Links to the schema:

* YAML version: [schema.yaml](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/paths/Conformance/schema.json)
* JSON version: [schema.json](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/paths/Conformance/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)
* [OGC API - Common - Part 1: Core - Landing Page Requirements Class](https://docs.ogc.org/is/19-072/19-072.html#_addb3c12-4aef-46cb-a6d9-834883ebed97)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/GeoLabs/bblocks-ogcapi-common](https://github.com/GeoLabs/bblocks-ogcapi-common)
* Path: `_sources/v1/paths/Conformance`

