---
swagger: "2.0"
x-collection-name: YouTube
x-complete: 0
info:
  title: Youtube Get Superchatevents
  description: Lists Super Chat events for a channel.
  termsOfService: https://developers.google.com/terms/
  contact:
    name: Google
    url: https://google.com
  version: 1.0.0
host: www.googleapis.com
basePath: /youtube/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /liveChat/bans:
    delete:
      summary: Delete Live Chat Bans
      description: Delete livechat bans
      operationId: deleteLivechatBans
      x-api-path-slug: livechatbans-delete
      parameters:
      - in: query
        name: id
        description: The id parameter identifies the chat ban to remove
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Bans
    post:
      summary: Add Live Chat Bans
      description: Adds a new ban to the chat.
      operationId: postLivechatBans
      x-api-path-slug: livechatbans-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter serves two purposes in this operation
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Bans
  /liveChat/messages:
    delete:
      summary: Delete Live Chat Messages
      description: Delete livechat messages
      operationId: deleteLivechatMessages
      x-api-path-slug: livechatmessages-delete
      parameters:
      - in: query
        name: id
        description: The id parameter specifies the YouTube chat message ID of the
          resource that is being deleted
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Messages
    get:
      summary: Get Live Chat Messages
      description: Lists live chat messages for a specific chat.
      operationId: getLivechatMessages
      x-api-path-slug: livechatmessages-get
      parameters:
      - in: query
        name: hl
        description: The hl parameter instructs the API to retrieve localized resource
          metadata for a specific application language that the YouTube website supports
      - in: query
        name: liveChatId
        description: The liveChatId parameter specifies the ID of the chat whose messages
          will be returned
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of messages
          that should be returned in the result set
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: part
        description: The part parameter specifies the liveChatComment resource parts
          that the API response will include
      - in: query
        name: profileImageSize
        description: The profileImageSize parameter specifies the size of the user
          profile pictures that should be returned in the result set
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Messages
    post:
      summary: Add Live Chat Messages
      description: Adds a message to a live chat.
      operationId: postLivechatMessages
      x-api-path-slug: livechatmessages-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter serves two purposes
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Messages
  /liveChat/moderators:
    delete:
      summary: Delete Live Chat Moderators
      description: Delete livechat moderators
      operationId: deleteLivechatModerators
      x-api-path-slug: livechatmoderators-delete
      parameters:
      - in: query
        name: id
        description: The id parameter identifies the chat moderator to remove
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Moderators
    get:
      summary: Get Live Chat Moderators
      description: Lists moderators for a live chat.
      operationId: getLivechatModerators
      x-api-path-slug: livechatmoderators-get
      parameters:
      - in: query
        name: liveChatId
        description: The liveChatId parameter specifies the YouTube live chat for
          which the API should return moderators
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of items
          that should be returned in the result set
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: part
        description: The part parameter specifies the liveChatModerator resource parts
          that the API response will include
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Moderators
    post:
      summary: Add Live Chat Moderators
      description: Adds a new moderator for the chat.
      operationId: postLivechatModerators
      x-api-path-slug: livechatmoderators-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter serves two purposes in this operation
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Moderators
  /superChatEvents:
    get:
      summary: Get Superchatevents
      description: Lists Super Chat events for a channel.
      operationId: getSuperchatevents
      x-api-path-slug: superchatevents-get
      parameters:
      - in: query
        name: hl
        description: The hl parameter instructs the API to retrieve localized resource
          metadata for a specific application language that the YouTube website supports
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of items
          that should be returned in the result set
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: part
        description: The part parameter specifies the superChatEvent resource parts
          that the API response will include
      responses:
        200:
          description: OK
      tags:
      - Chat
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