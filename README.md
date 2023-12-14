# vo-openapi

`vo-openapi` is an open-source project to provide OpenAPI specifications for [IVOA](https://www.ivoa.net/) service protocols.

## Features

- **OpenAPI Specifications:** The project includes OpenAPI definitions for IVOA protocols. The use of OpenAPI provides a standardized and machine-readable way to describe the IVOA protocols. OpenAPI specifications offer benefits such as automatic documentation generation, and automatic client and server code generation.

- **UWS (Universal Worker Service) version 1.1:**
  - Active development:
    - OpenAPI Models
  - Planned:
    - OpenAPI Service Definition

## Usage
### OpenAPI Schema

OpenAPI schema files representing IVOA protocol transactions can be found in the `openapi` directory.

For each protocol, two files are provided: a `components.yml` file containing the JSON/XML schema definitions for request / response transactions, and a file named after the protocol (e.g. `uws.yml`) containing the OpenAPI specification for the protocol. The schema models, and the OpenAPI specification, are viewable in the [Swagger Editor](https://editor.swagger.io/).

*Note: Currently, the OpenAPI API definition files are not guaranteed to be complete. They are provided as a starting point for future development, and an example of how the schema definitions can be used.*