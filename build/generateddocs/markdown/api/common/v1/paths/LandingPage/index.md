
# Landing Page Path (Path)

`ogc.api.common.v1.paths.LandingPage` *v0.1*

This building block corresponds to the landing page path (/) from OGC API - Common - Part 1: Core

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
get:
  summary: Landing page
  description: The landing page provides links to the API definition and the conformance
    statements for this API.
  operationId: getLandingPage
  tags:
  - server
  parameters:
  - $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/parameters/f-openapi/schema.yaml
  responses:
    '200':
      $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/responses/LandingPage/schema.yaml
    '400':
      $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/responses/InvalidParameter/schema.yaml
    '500':
      $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/responses/ServerError/schema.yaml

```

Links to the schema:

* YAML version: [schema.yaml](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/paths/LandingPage/schema.json)
* JSON version: [schema.json](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/paths/LandingPage/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)
* [OGC API - Common - Part 1: Core - Landing Page Requirements Class](https://docs.ogc.org/is/19-072/19-072.html#_65d42b57-7d32-4f4e-963b-ba0d4f190f27)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/GeoLabs/bblocks-ogcapi-common](https://github.com/GeoLabs/bblocks-ogcapi-common)
* Path: `_sources/v1/paths/LandingPage`

