# OGC API - Common - Part 1: Core Building Blocks

This repository contains Building Blocks for [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html).

## Overview

OGC API - Common - Part 1: Core defines the fundamental building blocks that are common to all OGC API standards. This includes:

- **Landing Page** (`/`) - The entry point for an API
- **Conformance Declaration** (`/conformance`) - Declaration of conformance classes supported
- **API Definition** (`/api`) - Machine-readable definition of the API (OpenAPI)
- **Common Formats** - Support for JSON and HTML representations
- **Common Schemas** - Links, exceptions, and other core data structures

## Structure

The Building Blocks are organized as follows:

```
_sources/v1/
├── api/              # Complete API definition
├── paths/            # Path definitions (/, /conformance, /api)
├── responses/        # Response definitions
├── schemas/          # Schema definitions (landingPage, conformance, link, etc.)
└── parameters/       # Common parameters
```

## Usage

These Building Blocks can be referenced using the `bblocks://` URI scheme:

```yaml
paths:
  /:
    $ref: "bblocks://ogc.api.common.v1.paths.LandingPage"
  /conformance:
    $ref: "bblocks://ogc.api.common.v1.paths.Conformance"
  /api:
    $ref: "bblocks://ogc.api.common.v1.paths.ApiDefinition"
```

## Building Blocks

### API Definition
- **ogc.api.common.v1.api** - Complete OGC API - Common Part 1 API

### Paths
- **ogc.api.common.v1.paths.LandingPage** - Landing page path (`/`)
- **ogc.api.common.v1.paths.Conformance** - Conformance declaration path (`/conformance`)
- **ogc.api.common.v1.paths.ApiDefinition** - API definition path (`/api`)

### Responses
- **ogc.api.common.v1.responses.LandingPage** - Landing page response
- **ogc.api.common.v1.responses.ConformanceDeclaration** - Conformance response
- **ogc.api.common.v1.responses.ApiDefinition** - API definition response (OpenAPI)

### Schemas
- **ogc.api.common.v1.schemas.landingPage** - Landing page schema
- **ogc.api.common.v1.schemas.confClasses** - Conformance classes schema
- **ogc.api.common.v1.schemas.link** - Link object schema
- **ogc.api.common.v1.schemas.exception** - Exception schema

## Standards Reference

- [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)

## License

This repository is published under the [OGC Software License](http://www.ogc.org/legal/).


