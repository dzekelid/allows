---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 1
info:
  title: AWS Cognito Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ConfirmForgotPassword:
    get:
      summary: Confirm Forgot Password
      description: |-
        Allows a user to enter a code provided when they reset their password to update
                    their password.
      operationId: confirmForgotPassword
      x-api-path-slug: actionconfirmforgotpassword-get
      parameters:
      - in: query
        name: ClientId
        description: The ID of the client associated with the user pool
        type: string
      - in: query
        name: ConfirmationCode
        description: The confirmation code sent by a users request to retrieve a forgotten            password
        type: string
      - in: query
        name: Password
        description: The password sent by sent by a users request to retrieve a forgotten            password
        type: string
      - in: query
        name: SecretHash
        description: A keyed-hash message authentication code (HMAC) calculated using
          the secret key of            a user pool client and username plus the client
          ID in the message
        type: string
      - in: query
        name: Username
        description: The user name of the user for whom you want to enter a code to
          retrieve a forgotten            password
        type: string
      responses:
        200:
          description: OK
      tags:
      - Passwords
  /?Action=DeleteUser:
    get:
      summary: Delete User
      description: Allows a user to delete one's self.
      operationId: deleteUser
      x-api-path-slug: actiondeleteuser-get
      parameters:
      - in: query
        name: AccessToken
        description: The access token from a request to delete a user
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
  /?Action=DeleteUserPoolClient:
    get:
      summary: Delete User Pool Client
      description: Allows the developer to delete the user pool client.
      operationId: deleteUserPoolClient
      x-api-path-slug: actiondeleteuserpoolclient-get
      parameters:
      - in: query
        name: ClientId
        description: The ID of the client associated with the user pool
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool where you want to delete the
          client
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Pools
  /?Action=UpdateUserAttributes:
    get:
      summary: Update User Attributes
      description: Allows a user to update a specific attribute (one at a time).
      operationId: updateUserAttributes
      x-api-path-slug: actionupdateuserattributes-get
      parameters:
      - in: query
        name: AccessToken
        description: The access token for the request to update user attributes
        type: string
      - in: query
        name: UserAttributes
        description: An array of name-value pairs representing user attributes
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
  /?Action=UpdateUserPoolClient:
    get:
      summary: Update User Pool Client
      description: |-
        Allows the developer to update the specified user pool client and password
                    policy.
      operationId: updateUserPoolClient
      x-api-path-slug: actionupdateuserpoolclient-get
      parameters:
      - in: query
        name: ClientId
        description: The ID of the client associated with the user pool
        type: string
      - in: query
        name: ClientName
        description: The client name from the update user pool client request
        type: string
      - in: query
        name: ExplicitAuthFlows
        description: Explicit authentication flows
        type: string
      - in: query
        name: ReadAttributes
        description: The read-only attributes of the user pool
        type: string
      - in: query
        name: RefreshTokenValidity
        description: The validity of the refresh token, in days
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool where you want to update the
          user pool            client
        type: string
      - in: query
        name: WriteAttributes
        description: The writeable attributes of the user pool
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Pool Clients
---