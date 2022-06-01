# OpenAPI Specification

1. *openapi* `string` `required` - The openapi field SHOULD be used by tooling specifications and clients to interpret the OpenAPI document. This is not related to the API info.version string.
2. *info* (6) `required` - Provides metadata about the API. The metadata MAY be used by tooling as required.
    * title
    * description
    * termsOfService
    * contact
      * name
      * url
      * email
    * license
      * name
      * url
    * version
 3. *servers* (3) `opetional` - If the servers property is not provided, or is an empty array, the default value would be a Server Object with a url value of /.
    * url
    * description
    * variables
      * enum
      * default
      * description
4. *paths* `reqired` - The available paths and operations for the API.
    * Path Item (13) - A relative path to an individual endpoint. The field name MUST begin with a forward slash (/)
      * $ref	
      * summary
      * description
      * get
      * put
      * post
      * delete
      * options
      * head
      * patch
      * trace
      * servers
      * parameters (4) (There are four possible parameter locations specified by the `in` field:)
        * path 
        * query
        * header
        * cookie
5. *components* (9) - An element to hold various schemas for the specification.
    * schemas
      * Type
      * Format
    * responses
      * description
      * headers
      * content
      * links
    * parameters
    * examples
    * requestBodies
      * description
      * content
      * required
    * headers
    * [securitySchemes](securitySchemes.md)
    * links
      * operationRef
      * operationId
      * parameters
      * requestBody
      * description
      * server
    * callbacks
6. *security* - A declaration of which security mechanisms can be used across the API.
   * {name} - Each name MUST correspond to a security scheme which is declared in the Security Schemes under the Components Object.
8. *tags* - A list of tags used by the specification with additional metadata.
    * name
    * description
    * externalDocs
9. *externalDocs* - Additional external documentation.
    * description
    * url


