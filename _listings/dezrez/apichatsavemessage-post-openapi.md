---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Save a new chat message.
  version: 1.0.0
  description: Save a new chat message..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/chat/unreadsummary:
    get:
      summary: Get a count of unread chat messages for the negotiator plus a list
        of corresponding message id's which are unread.
      description: Get a count of unread chat messages for the negotiator plus a list
        of corresponding message id's which are unread..
      operationId: Chat_UnreadSummary
      x-api-path-slug: apichatunreadsummary-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Count
      - Of
      - Unread
      - Chat
      - Messagesthe
      - Negotiator
      - Plus
      - List
      - Of
      - Corresponding
      - Message
      - Ids
      - Which
      - Are
      - Unread
  /api/chat/savemessage:
    post:
      summary: Save a new chat message.
      description: Save a new chat message..
      operationId: Chat_SaveMessageBychatMessageSave
      x-api-path-slug: apichatsavemessage-post
      parameters:
      - in: body
        name: chatMessageSave
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Save
      - New
      - Chat
      - Message
  /api/chat/message/markasread/{messageId}:
    put:
      summary: This will update the cache with a new timestamp for when this chat
        message was last read.
      description: This will update the cache with a new timestamp for when this chat
        message was last read..
      operationId: Chat_MarkMessageAsReadBymessageId
      x-api-path-slug: apichatmessagemarkasreadmessageid-put
      parameters:
      - in: path
        name: messageId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - This
      - Will
      - Update
      - Cache
      - New
      - Timestampwhen
      - This
      - Chat
      - Message
      - Was
      - Last
      - Read
  /api/Chat:
    get:
      summary: Get a previous chat message to append to.
      description: Get a previous chat message to append to..
      operationId: Chat_GetBymessageId
      x-api-path-slug: apichat-get
      parameters:
      - in: query
        name: messageId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Previous
      - Chat
      - Message
      - To
      - Append
      - To
    put:
      summary: Put - to update a chat message.
      description: Put - to update a chat message..
      operationId: Chat_PutBychatMessageSave
      x-api-path-slug: apichat-put
      parameters:
      - in: body
        name: chatMessageSave
        description: The Appointment JSON object
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - '-'
      - To
      - Update
      - Chat
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