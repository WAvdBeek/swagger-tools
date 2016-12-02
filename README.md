The project provides various tools for integrating and interacting with Swagger.  This project is in its infancy but
what is within the repository should be fully tested and reusable.  Please visit the [issue tracker][project-issues] to
see what issues we are aware of and what features/enhancements we are working on.  Otherwise, feel free to review the
[Release Notes][release-notes] to see what is new and improved.

## Supported Swagger Versions

* [1.2][swagger-docs-v1_2]
* [2.0][swagger-docs-v2_0]  - with json anyOf and oneOff construct added to the schema.

## Features

* Simple CLI
    * Validate Swagger document(s)
    * Convert Swagger 1.2 documents to Swagger 2.0
* Schema validation: For the file(s) supported by the Swagger specification, ensure they pass structural validation
based on the [JSON Schema][json-schema] associated with that version of the specification _(Browser and Node)_
* Semantic validation: Validates Swagger files above and beyond the structure of the file _(Browser and Node)_
* Connect middleware for adding pertinent Swagger information to your requests _(Node only)_
* Connect middleware for wiring up security handlers for requests based on Swagger documentation _(Node only)_
* Connect middleware for wiring request handlers to requests based on Swagger documentation _(Node only)_
* Connect middleware for serving your Swagger documents and [Swagger UI][swagger-ui] _(Node only)_
* Connect middleware for using Swagger resource documents for pre-route validation _(Node only)_
    * Validate the request/response Content-Type based on the operation's `consumes/produces` value(s)
    * Validate the request parameter types
    * Validate the request parameter values
    * Validate the response values

## Installation

Installation for Node.js applications 

```
npm i -g git+https://github.com/WAvdBeek/wb-swagger-tools.git
```

## Documentation

swagger-tools is heavily documented so head on over to the project  [documentation][documentation] or jump straight to
the [Quick Start][quick-start].

## Contributing

