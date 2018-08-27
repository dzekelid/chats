---
swagger: "2.0"
x-collection-name: New Relic
x-complete: 0
info:
  title: New Relic Add Alerts Channels. Format
  version: 1.0.0
  description: "This API endpoint works with new Alerts on alerts.newrelic.com.\n\nIt
    creates a channel associated with your New Relic account.\n\nNote: Admin User???s
    API Key is required.\n\nSee our documentation for a discussion on creating notification
    channels.\n\nChannel type configuration options:\n\n\n  \n    Email\n\n    {\n\n
    \   \"recipients\" : \"test@google.com\",\n\"include_json_attachment\" : true\n\n\n
    \   }\n  \n  \n    HipChat\n\n    {\n\n    \"auth_token\": \"abc123\",\n\"room_id\":
    \"google.com\"\n\n\n    }\n  \n  \n    OpsGenie\n\n    {\n\n    \"api_key\": \"abc123\",\n\"teams\":
    \"team1\",\n\"tags\": \"tag1\",\n\"recipients\": \"me@me.com\"\n\n\n    }\n  \n
    \ \n    Slack\n\n    {\n\n    \"url\": \"http://test.com\",\n\"channel\": \"channel1\"\n\n\n
    \   }\n  \n  \n    Campfire\n\n    {\n\n    \"subdomain\": \"mysubdomain\",\n\"token\":
    \"123abc\",\n\"room\": \"room1\"\n\n\n    }\n  \n  \n    Victorops\n\n    {\n\n
    \   \"key\": \"mykey\",\n\"route_key\": \"theroute\"\n\n\n    }\n  \n  \n    PagerDuty\n\n
    \   {\n\n    \"service_key\": \"myservicekey\"\n\n\n    }\n  \n  \n    Webhook
    (json)\n\n    {\n\n    \"base_url\": \"http://test.com\",\n\"auth_username\":
    \"username\",\n\"auth_password\": \"password\",\n\"payload_type\": \"application/json\",\n\"payload\":
    {\"account_id\": 1, \"account_name\": \"account name\" },\n\"headers\": {\"header1\":
    \"test\", \"header2\": \"test\"}\n\n\n    }\n  \n  \n    Webhook (x-www-form-urlencoded)\n\n
    \   {\n\n    \"base_url\": \"http://test.com\",\n\"auth_username\": \"username\",\n\"auth_password\":
    \"password\",\n\"payload_type\": \"application/x-www-form-urlencoded\",\n\"payload\":
    {\"account_id\": 1, \"account_name\": \"account name\" },\n\"headers\": {\"header1\":
    \"test\", \"header2\": \"test\"}\n\n\n    }"
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /alerts_channels.{format}:
    post:
      summary: Add Alerts Channels. Format
      description: "This API endpoint works with new Alerts on alerts.newrelic.com.\n\nIt
        creates a channel associated with your New Relic account.\n\nNote: Admin User???s
        API Key is required.\n\nSee our documentation for a discussion on creating
        notification channels.\n\nChannel type configuration options:\n\n\n  \n    Email\n\n
        \   {\n\n    \"recipients\" : \"test@google.com\",\n\"include_json_attachment\"
        : true\n\n\n    }\n  \n  \n    HipChat\n\n    {\n\n    \"auth_token\": \"abc123\",\n\"room_id\":
        \"google.com\"\n\n\n    }\n  \n  \n    OpsGenie\n\n    {\n\n    \"api_key\":
        \"abc123\",\n\"teams\": \"team1\",\n\"tags\": \"tag1\",\n\"recipients\": \"me@me.com\"\n\n\n
        \   }\n  \n  \n    Slack\n\n    {\n\n    \"url\": \"http://test.com\",\n\"channel\":
        \"channel1\"\n\n\n    }\n  \n  \n    Campfire\n\n    {\n\n    \"subdomain\":
        \"mysubdomain\",\n\"token\": \"123abc\",\n\"room\": \"room1\"\n\n\n    }\n
        \ \n  \n    Victorops\n\n    {\n\n    \"key\": \"mykey\",\n\"route_key\":
        \"theroute\"\n\n\n    }\n  \n  \n    PagerDuty\n\n    {\n\n    \"service_key\":
        \"myservicekey\"\n\n\n    }\n  \n  \n    Webhook (json)\n\n    {\n\n    \"base_url\":
        \"http://test.com\",\n\"auth_username\": \"username\",\n\"auth_password\":
        \"password\",\n\"payload_type\": \"application/json\",\n\"payload\": {\"account_id\":
        1, \"account_name\": \"account name\" },\n\"headers\": {\"header1\": \"test\",
        \"header2\": \"test\"}\n\n\n    }\n  \n  \n    Webhook (x-www-form-urlencoded)\n\n
        \   {\n\n    \"base_url\": \"http://test.com\",\n\"auth_username\": \"username\",\n\"auth_password\":
        \"password\",\n\"payload_type\": \"application/x-www-form-urlencoded\",\n\"payload\":
        {\"account_id\": 1, \"account_name\": \"account name\" },\n\"headers\": {\"header1\":
        \"test\", \"header2\": \"test\"}\n\n\n    }"
      operationId: postAlertsChannels.Format
      x-api-path-slug: alerts-channels-format-post
      parameters:
      - in: body
        name: channel
        description: channel schema
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: policy_ids
        description: Policy IDs to associate with channel
        type: array
      responses:
        200:
          description: OK
      tags:
      - Alerts
      - Channels.
      - Format
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