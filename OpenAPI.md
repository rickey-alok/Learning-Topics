# OpenAPI Specification

1. openapi
2. info (6)
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
 3. servers (3)
    * url
    * description
    * variables
      * enum
      * default
      * description
4. paths
    * Path Item (13)
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
5. components (9)
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
    * securitySchemes
    * links
      * operationRef
      * operationId
      * parameters
      * requestBody
      * description
      * server
    * callbacks
6. security
7. tags
    * name
    * description
    * externalDocs
8. externalDocs
    * description
    * url


