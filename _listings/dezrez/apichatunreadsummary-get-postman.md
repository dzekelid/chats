{
  "info": {
    "name": "Dezrez Get a count of unread chat messages for the negotiator plus a list of corresponding message id's which are unread.",
    "_postman_id": "fe6da665-26f0-43e8-bfb0-f382938b89b9",
    "description": "Get a count of unread chat messages for the negotiator plus a list of corresponding message id's which are unread..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Count",
      "item": [
        {
          "id": "6c9a18ae-cfc6-4b0b-9bbf-d9780154487d",
          "name": "Chat_UnreadSummary",
          "request": {
            "url": "http://api.dezrez.com/api/chat/unreadsummary",
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
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
            "description": "Get a count of unread chat messages for the negotiator plus a list of corresponding message id's which are unread.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ac5398ee-8dd9-43ae-b7fa-ed106d6442a3"
            }
          ]
        }
      ]
    }
  ]
}