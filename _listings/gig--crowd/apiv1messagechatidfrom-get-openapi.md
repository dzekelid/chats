---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Get Message Chat From
  version: 1.0.0
  description: Get message chat from.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/message/chats/{pageNumber}/{search}:
    get:
      summary: Get Message Chats Pagenumber Search
      description: Get message chats pagenumber search.
      operationId: getApiV1MessageChatsPagenumberSearch
      x-api-path-slug: apiv1messagechatspagenumbersearch-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: pageNumber
      - in: path
        name: search
      - in: query
        name: unread
      responses:
        200:
          description: OK
      tags:
      - Message
      - Chats
      - Pagenumber
      - Search
  /api/v1/message/chat/{id}/{from}:
    get:
      summary: Get Message Chat From
      description: Get message chat from.
      operationId: getApiV1MessageChatFrom
      x-api-path-slug: apiv1messagechatidfrom-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: from
        description: "20"
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Message
      - Chat
      - From
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