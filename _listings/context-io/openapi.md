---
swagger: "2.0"
x-collection-name: Context.IO
x-complete: 1
info:
  title: Context.IO
  description: context-io-is-the-missing-email-api-that-makes-it-easy-and-fast-to-integrate-your-users-email-data-in-your-application-
  version: 1.0.0
host: api.context.io
basePath: /2.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{id}/messages/{message_id}:
    post:
      summary: Post Accounts Messages Message
      description: Copies or moves a message. Allows you to copy or move a message
        between folders. If there are more than one sources on the account, you can
        use this call to copy/move the message between these sources. In this case,
        the dst_label parameter must identify the source you want to message to be
        copied/moved to.
      operationId: Create_copyMoveAccountMessage_
      x-api-path-slug: accountsidmessagesmessage-id-post
      parameters:
      - in: query
        name: dst_folder
        description: The folder within dst_source the message should be copied to
      - in: query
        name: dst_source
        description: Label of the source you want the message copied to
      - in: path
        name: id
        description: Unique id of an account accessible through your API key
      - in: path
        name: message_id
        description: Unique id of a message
      - in: query
        name: move
        description: By default, this calls copies the original message in the destination
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - Messages
      - Message
---