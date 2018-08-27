swagger: "2.0"
x-collection-name: 3scale
x-complete: 1
info:
  title: 3scale Service Management API
  description: the-api-for-managing-3scale-services-
  termsOfService: http://www.3scale.net/terms-and-conditions/
  contact:
    name: 3Scale
    url: https://support.3scale.net/
  version: "1"
host: su1.3scale.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  //{hostname}/client-admins:
    post:
      summary: POST client admin
      description: |-
        Allows users to add another user to the client's list of admins. It is assumed that when posting to this route that the current client (based on `x-client-auth`) is the client of which the user is adding a client admin.

        (unless the user is a system admin)
      operationId: ClientAdminsByHostnamePost
      x-api-path-slug: hostnameclientadmins-post
      parameters:
      - in: formData
        name: client
      - in: path
        name: hostname
      - in: formData
        name: user
      - in: header
        name: x-client-auth
      - in: header
        name: x-client-bearer-token
      responses:
        200:
          description: OK
      tags:
      - ""
  //{hostname}/client-admins/5:
    delete:
      summary: DELETE client admin
      description: Allows users to delete a mapping from user to client that represents
        the user being a client admin.
      operationId: ClientAdmins5ByHostnameDelete
      x-api-path-slug: hostnameclientadmins5-delete
      parameters:
      - in: path
        name: hostname
      - in: formData
        name: user
      - in: header
        name: x-client-auth
      - in: header
        name: x-client-bearer-token
      responses:
        200:
          description: OK
      tags:
      - ""