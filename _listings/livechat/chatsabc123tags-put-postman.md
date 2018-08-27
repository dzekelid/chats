{
  "info": {
    "name": "LiveChat Update chat tags",
    "_postman_id": "c2b1ab78-e6a3-416e-8cf1-67e996f15df9",
    "description": "This method updates the tags assigned to a chat.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Webhook",
      "item": [
        {
          "id": "152c284b-79b5-417d-a864-9cf8f5b4229f",
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
              "id": "ef72e7e1-3c26-4f90-9c5f-b965072ef28c"
            }
          ]
        }
      ]
    },
    {
      "name": "Chat",
      "item": [
        {
          "id": "66d62151-cbe2-4171-a931-ed7b1af0283e",
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
              "id": "517b3be0-9858-4c3a-81fb-662157d4860f"
            }
          ]
        },
        {
          "id": "84d9cd9b-b0e6-4dea-a0a8-957e475de472",
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
              "id": "c50f7a18-a3cc-4492-a386-a2ed13a66e51"
            }
          ]
        },
        {
          "id": "e7c1dc8c-6ad6-46f2-a552-54c800db01ab",
          "name": "ReportsChatsRatingsRankingGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/ratings/ranking",
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
            "description": "Shows the ratio of good to bad ratings for each operator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91201008-a20a-4315-9771-a2864ce5b97f"
            }
          ]
        },
        {
          "id": "39da6b9f-eb69-4bc5-9ed7-857e0e78dd1f",
          "name": "ChatsABC123TagsPut",
          "request": {
            "url": "http://api.livechatinc.com/chats/ABC123/tags",
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
                  "key": "tag[0]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "tag[1]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "This method updates the tags assigned to a chat."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59dd16a9-dfe5-458a-86d8-d00b0bb98d58"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "eac04131-ded6-4c02-9c92-a6c956668368",
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
              "id": "e7f93b53-f539-4f1d-87a7-146f3c6ac14e"
            }
          ]
        },
        {
          "id": "0862c641-0ba9-4594-97da-7ac40454884e",
          "name": "GreetingsGet",
          "request": {
            "url": "http://api.livechatinc.com/greetings?groups=%7B%7D",
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
            "description": "Returns the list of all greetings."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b8ffde65-d8ce-4a3d-a951-e4af3df28b3d"
            }
          ]
        },
        {
          "id": "ab1ef9fb-e7d8-4624-806a-2e601aa4ebb0",
          "name": "TagsGet",
          "request": {
            "url": "http://api.livechatinc.com/tags?group=%7B%7D",
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
            "description": "Returns tags from all groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ada23d3b-6e10-4823-8f4d-e56b738d8b47"
            }
          ]
        },
        {
          "id": "e12bca90-37f6-4229-bd37-17b068a0e234",
          "name": "TicketsGet",
          "request": {
            "url": "http://api.livechatinc.com/tickets?date_from=%7B%7D&status=%7B%7D",
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
            "description": "Returns all tickets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0912129-af63-4d13-95e1-83f04b8f3cee"
            }
          ]
        },
        {
          "id": "616a18ae-88b2-4656-878e-69459ef43ef9",
          "name": "CannedResponsesGet",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses",
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
              "id": "5a3eb5ed-a605-4b6a-96da-d52c77831d1e"
            }
          ]
        },
        {
          "id": "b3378d14-d7f1-4d27-84dd-217918740a6e",
          "name": "GroupsGet",
          "request": {
            "url": "http://api.livechatinc.com/groups",
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
            "description": "Returns all created groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33d3609c-da6d-459c-b34b-c23e92620aea"
            }
          ]
        },
        {
          "id": "e1629760-6342-4351-b91a-c5a2dccfe1e3",
          "name": "GoalsGet",
          "request": {
            "url": "http://api.livechatinc.com/goals",
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
            "description": "Returns all currently set goals. The active parameter indicates whether a goal is enabled or not."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06a95c83-ab75-468d-b7c3-2a050e0ab073"
            }
          ]
        },
        {
          "id": "e95734cf-e991-4ba0-8512-414d38bb3583",
          "name": "ChatsGet",
          "request": {
            "url": "http://api.livechatinc.com/chats",
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
            "description": "Returns all ended chats."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "edfba360-34ba-4721-a0f6-8f65e4ded052"
            }
          ]
        },
        {
          "id": "ec84e27c-72cc-4607-8e01-bd16abd79fe6",
          "name": "AgentsGet",
          "request": {
            "url": "http://api.livechatinc.com/agents",
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
            "description": "Returns all LiveChat agents list"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ce2202e-e1de-44f2-84ac-4027a9d14597"
            }
          ]
        }
      ]
    },
    {
      "name": "Canned",
      "item": [
        {
          "id": "06ab994e-26f6-4d2f-b355-32a045f91909",
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
              "id": "4485c31c-ea7e-4b44-be3f-6920e8d593ce"
            }
          ]
        }
      ]
    },
    {
      "name": "Remove",
      "item": [
        {
          "id": "a5f00834-5a56-455f-b77c-8249b9f203ab",
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
              "id": "533771d0-dccc-4aef-a13c-058b4d499b33"
            }
          ]
        },
        {
          "id": "b21f5f56-ab2a-46f8-be3c-441f19357ae8",
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
              "id": "d567b111-051c-40ca-b9fe-9f439b34fc72"
            }
          ]
        },
        {
          "id": "8555f7f1-ce73-4318-8a67-347a457ef2fa",
          "name": "AgentsJohnPublicComDelete",
          "request": {
            "url": "http://api.livechatinc.com/agents/john@public.com",
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
            "description": "Removes an agent."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0a9d7e4-b2b1-43f6-9fb1-ac040d3a554a"
            }
          ]
        },
        {
          "id": "6ad0d5fe-a804-4d4e-a7e4-9568a822a969",
          "name": "GreetingsABC123Delete",
          "request": {
            "url": "http://api.livechatinc.com/greetings/ABC123",
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
            "description": "Removes a greeting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "58b35bdf-10b6-453f-8560-58be370e1049"
            }
          ]
        },
        {
          "id": "58aed530-8454-4337-8c1e-4482da1fa462",
          "name": "GoalsABC123Delete",
          "request": {
            "url": "http://api.livechatinc.com/goals/ABC123",
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
            "description": "Removes a goal with the given GOAL_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "898386dd-8c21-4063-9564-a6e5571a14e9"
            }
          ]
        }
      ]
    },
    {
      "name": "Group",
      "item": [
        {
          "id": "3339f0e4-2b1a-493b-82da-80b65445e235",
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
              "id": "42f06f5a-4dfc-4b21-857f-ef81f731d0b7"
            }
          ]
        }
      ]
    },
    {
      "name": "New",
      "item": [
        {
          "id": "9a6d4669-eb59-454d-acfb-19f812b89916",
          "name": "GreetingsPost",
          "request": {
            "url": "http://api.livechatinc.com/greetings",
            "method": "POST",
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
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[0][operator]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[0][type]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[0][value]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[1][operator]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[1][type]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[1][value]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Use this function to create a new greeting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5bf8d51-5493-4729-8b85-9a1d88e318a2"
            }
          ]
        },
        {
          "id": "b56df9e5-6c7f-4da4-ad50-087f378f1b46",
          "name": "WebhooksPost",
          "request": {
            "url": "http://api.livechatinc.com/webhooks",
            "method": "POST",
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
                  "key": "data_types",
                  "value": "[{}]",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "event_type",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "url",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new webhook."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f9e8527-f5b5-4940-a680-2a378f17e1b2"
            }
          ]
        },
        {
          "id": "d19a7b9f-fd6a-44a3-99cf-c321afba9c87",
          "name": "CannedResponsesPost",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses",
            "method": "POST",
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
                },
                {
                  "key": "tags[1]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "text",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new canned response."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0dabf5b7-0186-4f94-9af6-cfd780f0a14d"
            }
          ]
        },
        {
          "id": "bc5517f8-9c02-4c6d-ab24-f9e5b90d2bd1",
          "name": "GroupsPost",
          "request": {
            "url": "http://api.livechatinc.com/groups",
            "method": "POST",
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
            "description": "Creates a new group in your license."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c490ae25-46f4-4baf-97f0-5abb2291e845"
            }
          ]
        },
        {
          "id": "dca7cce5-041a-4431-82c8-f7321450a775",
          "name": "GoalsPost",
          "request": {
            "url": "http://api.livechatinc.com/goals",
            "method": "POST",
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
                  "key": "match_type",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "type",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "url",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new goal."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92ab36ee-d5d4-4543-8523-9531f4c6cd7c"
            }
          ]
        },
        {
          "id": "0bae1fab-2d53-448b-86e4-1e4b8d9f7d83",
          "name": "AgentsPost",
          "request": {
            "url": "http://api.livechatinc.com/agents",
            "method": "POST",
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
                  "key": "login",
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
            "description": "Creates a new agent in your license."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ad1aca7-13ca-4575-ba06-2aff2fe36f9e"
            }
          ]
        }
      ]
    },
    {
      "name": "Display",
      "item": [
        {
          "id": "56490270-4def-47ad-8649-4e8f7268b8ed",
          "name": "WebhooksGet",
          "request": {
            "url": "http://api.livechatinc.com/webhooks",
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
            "description": "Returns a list of webhooks that have been created in a LiveChat account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5dcd2f49-7292-4ca1-8411-3a83112e2bc1"
            }
          ]
        }
      ]
    },
    {
      "name": "Greetings",
      "item": [
        {
          "id": "4f6a3b33-27fd-4364-8a07-32be1b20ae04",
          "name": "ReportsChatsGreetingsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/greetings?date_from=%7B%7D&date_to=%7B%7D&group_by=%7B%7D",
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
            "description": "Returns the “greetings to chats to goals” conversion rates report.\n\ndisplayed is the number of displayed greetings. accepted tells you how many chats resulted from these greetings. goals tells you how many goals resulted from these greetings."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f95b0e0-ca77-45cd-a436-6ec25e8ac25a"
            }
          ]
        }
      ]
    },
    {
      "name": "Tag",
      "item": [
        {
          "id": "751278c2-b201-4af7-a245-30139ed66984",
          "name": "TagsPost",
          "request": {
            "url": "http://api.livechatinc.com/tags",
            "method": "POST",
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
                  "key": "author",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "group",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "tag",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Adds a new tag. Note that only the owner and the admins are authorized to use this."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "328cdd75-6edc-4bbe-8ba5-afcc86cf3e80"
            }
          ]
        }
      ]
    },
    {
      "name": "Single",
      "item": [
        {
          "id": "d50348ac-47e8-4b6d-93c0-27da4f388139",
          "name": "AgentsJohnPublicComGet",
          "request": {
            "url": "http://api.livechatinc.com/agents/john@public.com",
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
            "description": "Returns complete details of the agent for the given LOGIN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dfba6578-0c20-4029-8a23-72dd8c1cf1ff"
            }
          ]
        },
        {
          "id": "a3d909be-3816-4bce-b3e5-044993a608d7",
          "name": "AgentsJohnPublicComPut",
          "request": {
            "url": "http://api.livechatinc.com/agents/john@public.com",
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
                  "key": "job_title",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Returns complete details of the agent for the given LOGIN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "97e774ca-08b5-4f88-8909-54d993095b94"
            }
          ]
        },
        {
          "id": "3f4ec75b-73b1-47fe-94c5-470305ebda74",
          "name": "ChatsABC123Get",
          "request": {
            "url": "http://api.livechatinc.com/chats/ABC123",
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
            "description": "Returns a single chat item for the given CHAT_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fef14d9-b4cd-49a8-86df-0be8b50cdbeb"
            }
          ]
        },
        {
          "id": "659edd69-2c8e-4c98-a7af-2b4052176420",
          "name": "GreetingsABC123Get",
          "request": {
            "url": "http://api.livechatinc.com/greetings/ABC123",
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
            "description": "Returns the specified greeting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b6aec2f-7aa2-49c4-91fb-6550af2b5e8d"
            }
          ]
        },
        {
          "id": "d7ca2974-b3e2-4c04-b34b-361b174b6786",
          "name": "GroupsByGroupIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.livechatinc.com",
              "path": [
                "groups/:group_id"
              ],
              "variable": [
                {
                  "id": "group_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Returns group details for the given GROUP_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f9107bc-8caa-44f3-a254-2311241dd498"
            }
          ]
        },
        {
          "id": "4149b247-e63d-4fa1-8472-d61d2f1fd78d",
          "name": "GoalsABC123Get",
          "request": {
            "url": "http://api.livechatinc.com/goals/ABC123",
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
            "description": "Returns the goal details for the given GOAL_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1725b9cd-f3af-4b2b-bb45-4600bd852f3d"
            }
          ]
        }
      ]
    },
    {
      "name": "Ticket",
      "item": [
        {
          "id": "2ec0afdb-ead4-4f76-8a26-fa14f76d2c8f",
          "name": "TicketsPost",
          "request": {
            "url": "http://api.livechatinc.com/tickets",
            "method": "POST",
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
                  "key": "message",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "requester[mail]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "requester[name]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "subject",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new ticket."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "24d23ee0-f6bc-4b19-9707-9d61ec779a75"
            }
          ]
        },
        {
          "id": "94bafa60-e1b4-4de3-9030-101bbfc2a13f",
          "name": "ReportsTicketsTicketSourcesGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/tickets/ticket_sources?date_from=%7B%7D&date_to=%7B%7D",
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
            "description": "Shows the distribution of the tickets between various channels."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0edbbdef-f801-4b38-973e-c6962bf92770"
            }
          ]
        },
        {
          "id": "27904a4a-4dd0-4df3-9cf3-949a75cf40c9",
          "name": "ReportsTicketsRatingsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/tickets/ratings?date_from=%7B%7D&date_to=%7B%7D&group=%7B%7D&group_by=%7B%7D",
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
            "description": "Shows the tickets that were rated during the specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "22efcf26-6978-4368-93c9-ec5c0c42f0c8"
            }
          ]
        },
        {
          "id": "c8d6672a-4804-45ce-b195-96daef92d91b",
          "name": "Tickets5FUEDTagsPut",
          "request": {
            "url": "http://api.livechatinc.com/tickets/5FUED/tags",
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
                  "key": "tag",
                  "value": "[{}]",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Updates tags associated with the ticket."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb229d29-1fd1-4711-bf4b-9ee7a21692de"
            }
          ]
        },
        {
          "id": "9d946907-3bb5-4747-b7d9-4bef766c79fc",
          "name": "ReportsTicketsRatingsRankingGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/tickets/ratings/ranking",
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
            "description": "Shows the ratio of good to bad ratings for each operator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96e5fb0d-4dc7-4236-b9b5-fe2fb36ad6b2"
            }
          ]
        }
      ]
    },
    {
      "name": "Solved",
      "item": [
        {
          "id": "7faacd26-7468-4ffe-8017-80623718d6bf",
          "name": "ReportsTicketsSolvedTicketsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/tickets/solved_tickets?date_from=%7B%7D&date_to=%7B%7D",
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
            "description": "Shows the number of the tickets solved during the specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68b88344-6343-42fc-bd79-e35104f2473e"
            }
          ]
        }
      ]
    },
    {
      "name": "Chats",
      "item": [
        {
          "id": "61b1ec91-e993-4a86-821b-af7a31831e51",
          "name": "ReportsChatsFirstResponseTimeGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/first_response_time",
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
            "description": "The average amount of time it takes the agents to respond to a new chat over a specified period of time."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9311655a-2313-4ef0-a797-d7394fadebda"
            }
          ]
        },
        {
          "id": "c3112aa3-3b50-4d6e-a4ce-fb321418c5d0",
          "name": "ReportsChatsResponseTimeGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/response_time",
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
            "description": "The average amount of time it takes the agents to respond to a new message in a chat during a specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51626bec-0e3a-4d11-8587-af4f7dc930c9"
            }
          ]
        }
      ]
    },
    {
      "name": "Total",
      "item": [
        {
          "id": "3ec49011-a43a-4bb3-8c85-020309032cad",
          "name": "ReportsChatsTotalChatsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/total_chats?agent=%7B%7D&date_from=%7B%7D&date_to=%7B%7D&group_by=%7B%7D",
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
            "description": "Shows how many chats occurred during the specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "702ba4c6-6fc8-463a-9f22-f7fa0b3fd7ca"
            }
          ]
        }
      ]
    },
    {
      "name": "Goal",
      "item": [
        {
          "id": "bc5043eb-068a-4bd9-9759-172cf233f2c1",
          "name": "GoalsABC123Put",
          "request": {
            "url": "http://api.livechatinc.com/goals/ABC123",
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
                  "key": "active",
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
            "description": "Updates the specified goal by setting the values of the parameters passed. Any parameters not provided will be left unchanged.\n\nThe GOAL_ID is obtained from the goals list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "424de059-1980-45a1-9b0f-5c575317d6be"
            }
          ]
        }
      ]
    },
    {
      "name": "Availability",
      "item": [
        {
          "id": "7a4dde92-8472-43ed-b561-6fafcd24ac62",
          "name": "ReportsAvailabilityGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/availability",
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
            "description": "Shows how long an agent (or a group or the whole account) was available for chatting during a specified period. When querying for one day, the results are shown in minutes per every hour, otherwise in hours for each day."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "35824f18-aecb-492d-9312-464a0cb2166c"
            }
          ]
        }
      ]
    }
  ]
}