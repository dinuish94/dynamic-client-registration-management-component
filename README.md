# Dynamic Client Registation Management

This sample component is implemented as an extension to Dynamic Client Registration in WSO2 Identity Server.

This implementation uses [Dynamic Client Registration Management Protocol](https://tools.ietf.org/html/rfc7592).

### Added Functionalities

  - Ability to query Client Registration Information
  - Update Client Registration Information
  - Delete Client Registration

##### Retrieve Client Information

GET request to /identity/register/{client_id}.
Replace `{client_id}` with the id of the client application you want to retrieve details of. 

Example:
```sh
$ curl -H 'Authorization: Basic: YWRtaW46YWRtaW4=' -X GET 'https://localhost:9443/identity/register/8VF3iYpzF9LkxDff4MEmwRKxt7Ua' -k -v

```

### To Be Implemented
- Update Client Information
- Delete Client Registration
