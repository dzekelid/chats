---
swagger: "2.0"
x-collection-name: LiveChat
x-complete: 0
info:
  title: LiveChat Number of simultaneous chats
  description: This request shows the maximum number of concurrent chats that happened
    at the same hour on a particular day.
  version: 1.0.0
host: api.livechatinc.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /reports/chats/agents_occupancy:
    get:
      summary: Number of simultaneous chats
      description: This request shows the maximum number of concurrent chats that
        happened at the same hour on a particular day.
      operationId: ReportsChatsAgentsOccupancyGet
      x-api-path-slug: reportschatsagents-occupancy-get
      parameters:
      - in: query
        name: weekday
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Number
      - Of
      - Simultaneous
      - Chats
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