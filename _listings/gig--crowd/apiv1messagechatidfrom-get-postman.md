{
  "info": {
    "name": "GIGANDCROWD Get Message Chat From",
    "_postman_id": "3f93c2f1-5d29-4d12-837a-f4f1a9bb99d1",
    "description": "Get message chat from.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Message",
      "item": [
        {
          "id": "b9245a48-4628-4e5d-8805-3a16275b46b0",
          "name": "getApiV1MessageChatsPagenumberSearch",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/message/chats/:pageNumber/:search"
              ],
              "query": [
                {
                  "key": "unread",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "pageNumber",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "search",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
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
            "description": "Get message chats pagenumber search."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab571c1f-3e91-4436-82c1-88a695a39002"
            }
          ]
        },
        {
          "id": "99def839-fa54-44da-93c9-d2cecde20e0b",
          "name": "getApiV1MessageChatFrom",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/message/chat/:id/:from"
              ],
              "variable": [
                {
                  "id": "from",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
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
            "description": "Get message chat from."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "756b3839-80d8-4b8c-8ae7-37011fcca611"
            }
          ]
        }
      ]
    }
  ]
}