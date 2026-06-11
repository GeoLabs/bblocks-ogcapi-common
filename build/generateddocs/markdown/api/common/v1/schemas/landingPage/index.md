
# Landing Page (Schema)

`ogc.api.common.v1.schemas.landingPage` *v0.1*

This building block corresponds to the landing page schema from OGC API - Common - Part 1: Core

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
type: object
required:
- links
properties:
  title:
    type: string
    title: The title of the API.
    description: While a title is not required, implementers are strongly advised
      to include one.
    example: Buildings in Bonn
  description:
    type: string
    example: Access to data about buildings in the city of Bonn via a Web API that
      conforms to the OGC API Common specification.
  attribution:
    type: string
    title: attribution for the API
    description: The `attribution` should be short and intended for presentation to
      a user, for example, in a corner of a map. Parts of the text can be links to
      other resources if additional information is needed. The string can include
      HTML markup.
  links:
    type: array
    items:
      $ref: https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/schemas/link/schema.yaml

```

Links to the schema:

* YAML version: [schema.yaml](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/schemas/landingPage/schema.json)
* JSON version: [schema.json](https://geolabs.github.io/bblocks-ogcapi-common/build/annotated/api/common/v1/schemas/landingPage/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/GeoLabs/bblocks-ogcapi-common](https://github.com/GeoLabs/bblocks-ogcapi-common)
* Path: `_sources/v1/schemas/landingPage`

