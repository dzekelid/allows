---
swagger: "2.0"
x-collection-name: Context.IO
x-complete: 0
info:
  title: Context.IO Post Accounts Messages Message
  description: Copies or moves a message. Allows you to copy or move a message between
    folders. If there are more than one sources on the account, you can use this call
    to copy/move the message between these sources. In this case, the dst_label parameter
    must identify the source you want to message to be copied/moved to.
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---