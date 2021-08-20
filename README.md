# Turnitin Core Api (TCA)
Turnitin provides RESTful APIs to support third party integration with our market-leading originality check services. To help facilitate you in developing your integration, we have provided an OpenAPI document, Postman collection, and example TCA Client libraries. If you haven't already done so, please start with our [Developer Portal](https://developers.turnitin.com/turnitin-core-api) first, including reading our more verbose [API Documentation](https://developers.turnitin.com/docs/tca#introduction)

# OpenAPI documentation

> The OpenAPI Specification (OAS) defines a standard, language-agnostic
> interface to RESTful APIs which allows both humans and computers to
> discover and understand the capabilities of the service without access
> to source code, documentation, or through network traffic inspection.
> When properly defined, a consumer can understand and interact with the
> remote service with a minimal amount of implementation logic.
> -[Swagger.io](https://swagger.io/resources/open-api/)

We have created [TCA's OpenAPI specification](tca-openapi.yaml) so that you can take advantage of these features, including generating Postman collections, generating client libraries, and viewing the API documentation.

To learn more about OpenAPI, visit [https://swagger.io/specification/](https://swagger.io/specification/)

### Swagger Editor and Viewer
To view a user friendly UI representation of TCA's API, copy and paste the [TCA OpenAPI specification](tca-openapi.yaml) into the [Swagger Editor](https://editor.swagger.io/) and it will automatically load and display the API in their viewer. *(Note: You can generate client libraries within this editor by clicking the menu option "Generate Client")

# Postman

> Postman is an API platform for building and using APIs. Postman
> simplifies each step of the API lifecycle and streamlines
> collaboration so you can create better APIs—faster
> -[Postman](https://www.postman.com/)

Postman is great for making REST calls directly to TCA, allowing you to set the request parameters and view the responses in their app. To get started, download Postman and import [TCA's Postman Collection](tca-postman-collection.json). This will import TCA's API allowing you to start making requests against TCA. It also provides example requests code snippets, allows you to set environments, store variables, and much more.

To learn more about Postman, visit [https://www.postman.com/](https://www.postman.com/)

# Client Libraries
We have provided a few example client libraries that you can use, copy, or fork. These libraries are generated automatically based on our [TCA OpenAPI specification](tca-openapi.yaml) using either the [Swagger Editor](https://editor.swagger.io/) or the [OpenAPI generator](https://openapi-generator.tech/). To view the full list of supported languages, go to this [generators list](https://openapi-generator.tech/docs/generators).

 - [TCA Java Client](https://github.com/turnitin/tca-client-java)
 - [TCA Javascript Client](https://github.com/turnitin/tca-client-javascript)

Each client library repository has a README that explains how to build and implement the library, including code examples for making requests to TCA.
