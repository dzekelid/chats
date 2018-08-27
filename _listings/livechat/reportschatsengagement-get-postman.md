{
  "info": {
    "name": "LiveChat Chat engagement",
    "_postman_id": "48d4ceac-3aa7-45a7-9c1d-afa48e33af70",
    "description": "This report shows you where you get your chats from. They can come from i.e. automatic invitations, manual invitations or the visitors can start the chats by themselves.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Webhook",
      "item": [
        {
          "id": "9049236b-68bc-4137-9282-f913155aefa9",
          "name": "Webhooks12345Delete",
          "request": {
            "url": "http://api.livechatinc.com/webhooks/12345",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a webhook with the given ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1747284-ab70-4dbc-866c-269b5a7b858a"
            }
          ]
        }
      ]
    },
    {
      "name": "Chat",
      "item": [
        {
          "id": "e906b142-ac4f-4735-a550-db8f2221c715",
          "name": "ReportsChatsRatingsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/ratings?date_from=%7B%7D&date_to=%7B%7D&group=%7B%7D&group_by=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows how many chats have been rated and how they have been rated during a specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ee2769e4-0fa8-4623-b277-57591088ef2f"
            }
          ]
        },
        {
          "id": "c705f7ac-bc63-46a6-9b86-b517a7d45eb1",
          "name": "ReportsChatsEngagementGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/engagement?agent=%7B%7D&date_from=%7B%7D&date_to=%7B%7D&group_by=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This report shows you where you get your chats from. They can come from i.e. automatic invitations, manual invitations or the visitors can start the chats by themselves."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38b77ba3-c5fb-4274-b298-b661a11f34f5"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "7194317e-6b35-48c2-85fb-7b1696b9c0ec",
          "name": "CannedResponsesABC123Get",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses/ABC123",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the list of all currently set canned responses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "771c7cbb-b2b6-48a3-a6bb-365d9851b7f8"
            }
          ]
        }
      ]
    },
    {
      "name": "Canned",
      "item": [
        {
          "id": "64137dfd-0d49-4dac-a3dc-f70ac3f9f116",
          "name": "CannedResponsesABC123Put",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses/ABC123",
            "method": "PUT",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "tags[0]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Updates the specified canned response by setting the values of the parameters passed. Any parameters not provided will be left unchanged."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d750ade-5351-4608-bc9f-e7e6913348df"
            }
          ]
        }
      ]
    },
    {
      "name": "Remove",
      "item": [
        {
          "id": "c87adeb3-8f39-4987-ba46-f94328d74526",
          "name": "CannedResponsesABC123Delete",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses/ABC123",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Removes a canned response with the given CANNED_RESPONSE_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "721fe56b-4267-4bd7-9013-6561a459ec74"
            }
          ]
        },
        {
          "id": "db27cef8-8543-40d7-9f44-717e5b260c5b",
          "name": "GroupsABC123Delete2",
          "request": {
            "url": "http://api.livechatinc.com/groups/ABC123",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Removes a group with the given GROUP_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a4c9b883-7368-42bb-b08b-67eebd7bb61c"
            }
          ]
        }
      ]
    },
    {
      "name": "Group",
      "item": [
        {
          "id": "9ce7dcf7-aceb-4cb1-bb91-e2672be1f192",
          "name": "GroupsABC123Put",
          "request": {
            "url": "http://api.livechatinc.com/groups/ABC123",
            "method": "PUT",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "agents[0]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "agents[1]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Updates the specified group by setting the values of the parameters passed. Any parameters not provided will be left unchanged."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33c7fa70-3e9a-48b8-9708-6544d9d2f260"
            }
          ]
        }
      ]
    }
  ]
}