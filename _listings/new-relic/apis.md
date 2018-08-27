---
name: New Relic
x-slug: new-relic
description: New Relic???s digital intelligence platform lets developers, ops, and
  tech teams measure and monitor the performance of their applications and infrastructure.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
x-kinRank: "8"
x-alexaRank: "10322"
tags: Chats
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/chats/master/_listings/new-relic/apis.md
specificationVersion: "0.14"
apis:
- name: New Relic - Add Alerts Channels. Format
  x-api-slug: alerts-channels-format-post
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/chats/master/_listings/new-relic/alerts-channels-format-post-openapi.md
- name: New Relic - Add Alerts Channels. Format
  x-api-slug: alerts-channels-format-post
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/chats/master/_listings/new-relic/alerts-channels-format-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://netlicensing.api.gallery.streamdata.io
- type: x-api-stack
  url: http://new.relic.stack.network
- type: x-blog
  url: https://blog.newrelic.com/
- type: x-blog-rss
  url: https://blog.newrelic.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/new-relic
- type: x-developer
  url: https://rpm.newrelic.com/api/explore/
- type: x-email
  url: billing@newrelic.com
- type: x-email
  url: resume@newrelic.com
- type: x-email
  url: PR@newrelic.com
- type: x-email
  url: copyright@newrelic.com
- type: x-email
  url: dataprivacy@newrelic.com
- type: x-email
  url: PersonalDataRequest@newrelic.com
- type: x-email
  url: support@newrelic.com
- type: x-email
  url: compliance@newrelic.com
- type: x-github
  url: https://github.com/newrelic
- type: x-twitter
  url: https://twitter.com/NewRelic
- type: x-website
  url: https://newrelic.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---