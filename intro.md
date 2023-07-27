
# Introduction

An HTTP REST API to allow 3rd party application to communicate with LaylaElectric cloud. This API can be used to access some basic information about properties, devices and features offered my LaylaElectric products. 

# Authentication

**Getting your access token**: You can e-mail at info@laylaelectric.com and we will provide you with the access token.

**Using your access token:** Every call should use and authorization header containing the access token in form of JSON Web Token (JWT).

## Error States

The common  [HTTP Response Status Codes](https://github.com/for-GET/know-your-http-well/blob/master/status-codes.md)  are used.

In general:

-   **200's**: everything is ok. You may need to check the message with the 200 anyway in some cases to do certain thing.