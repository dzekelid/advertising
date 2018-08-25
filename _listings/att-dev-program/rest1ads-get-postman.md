{
  "info": {
    "name": "AT&T API Get Ads",
    "_postman_id": "97b44af8-d196-4dc2-a416-9064378859bc",
    "description": "/rest/1/ads",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devicecapabilities",
      "item": [
        {
          "id": "3927b651-6837-45d2-abdb-ece48560e89f",
          "name": "1devicecapabilitiesacrauthorizationcapabilities",
          "request": {
            "url": "http://api.att.com/1/devicecapabilities/acr:authorization/capabilities",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/1/devicecapabilities/acr:authorization/capabilities"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41421dd1-2efc-4d77-bd4a-b8a4d54bebb1"
            }
          ]
        }
      ]
    },
    {
      "name": "Messaging",
      "item": [
        {
          "id": "ae6e7cc6-010a-4b40-b591-f144af80608a",
          "name": "3messagingoutboundsenderaddressrequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/messaging/outbound/:senderAddress/requests"
              ],
              "variable": [
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/3/messaging/outbound/{senderAddress}/requests"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a52ed84b-8e5e-4a80-85a8-c862a88a6e2e"
            }
          ]
        },
        {
          "id": "85c0a15a-1395-4d03-adea-f16c28c87bc0",
          "name": "3messagingoutboundsenderaddressrequestiddeliveryinfos",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/messaging/outbound/:senderAddress/:requestId/deliveryInfos"
              ],
              "variable": [
                {
                  "id": "requestId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/3/messaging/outbound/{senderAddress}/{requestId}/deliveryInfos"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb39d6cb-2434-4845-b646-3484eaeedb00"
            }
          ]
        }
      ]
    },
    {
      "name": "Smsmessaging",
      "item": [
        {
          "id": "77733533-597e-4df2-923e-da7b62dc5891",
          "name": "3smsmessaginginboundregistrationsregistrationidmessages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/smsmessaging/inbound/registrations/:registrationId/messages"
              ],
              "variable": [
                {
                  "id": "registrationId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/3/smsmessaging/inbound/registrations/{registrationId}/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9094c3bb-2b90-4fd0-8884-3a53271af425"
            }
          ]
        },
        {
          "id": "95d9e3e9-53c7-43a6-904c-8e14827a5013",
          "name": "3smsmessagingoutboundrequestssenderaddressrequestiddeliveryinfos",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/smsmessaging/outbound/requests/:senderAddress/:requestId/deliveryInfos"
              ],
              "variable": [
                {
                  "id": "requestId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/3/smsmessaging/outbound/requests/{senderAddress}/{requestId}/deliveryInfos"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dea45456-d5dc-4932-b9f9-024055f9a971"
            }
          ]
        },
        {
          "id": "24b2a51b-caee-41c1-9d41-838d8cc93411",
          "name": "3smsmessagingoutboundsenderaddressrequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/smsmessaging/outbound/:senderAddress/requests"
              ],
              "variable": [
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/3/smsmessaging/outbound/{senderAddress}/requests"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e8038c0b-878a-4263-97ee-b267545c4660"
            }
          ]
        }
      ]
    },
    {
      "name": "Mms",
      "item": [
        {
          "id": "3ea65c3b-75b3-4cd5-9905-6a2f1a08fb00",
          "name": "mmsv3messagingoutbox",
          "request": {
            "url": "http://api.att.com/mms/v3/messaging/outbox",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/mms/v3/messaging/outbox"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb490969-697b-4b51-9e86-b7dd099c4392"
            }
          ]
        },
        {
          "id": "4bf3ce22-ab60-4938-b8b0-b11c0f0d3b52",
          "name": "mmsv3messagingoutboxmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "mms/v3/messaging/outbox/:messageId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/mms/v3/messaging/outbox/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9996fa85-b64f-44cf-9d6f-2e11e7991b10"
            }
          ]
        }
      ]
    },
    {
      "name": "MyMessages",
      "item": [
        {
          "id": "23ce33ce-f24b-477d-b556-83a558663127",
          "name": "mymessagesv2delta",
          "request": {
            "url": "http://api.att.com/myMessages/v2/delta",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/delta"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a62effe-a4fc-44cb-b226-f3c93c2171d0"
            }
          ]
        },
        {
          "id": "5b33f8bf-78c2-4a45-8133-5f38fc0db4f9",
          "name": "mymessagesv2messages",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30bc77f6-81aa-48a5-8120-3e57dad2108f"
            }
          ]
        },
        {
          "id": "bf6f00bd-5eda-4848-bc9e-a651a4b5d6d7",
          "name": "mymessagesv2messages",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "591755e0-1ec5-4bcf-822c-4afc349036d2"
            }
          ]
        },
        {
          "id": "afc5fbf9-a855-4a63-b550-d1f89523000a",
          "name": "mymessagesv2messages",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1868de0f-4c2e-44a6-9e17-436ca5b1e579"
            }
          ]
        },
        {
          "id": "16627f99-f620-4c98-8c44-94620f325a35",
          "name": "mymessagesv2messagesindex",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages/index",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/index"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a18326b-b437-48bf-a6e5-ea93a87fa14e"
            }
          ]
        },
        {
          "id": "dc1d40d2-9bbe-4a55-9d02-a4e8f898dbb7",
          "name": "mymessagesv2messagesindexinfo",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages/index/info",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/index/info"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ec2791e-20ca-4aac-b0f3-d3135e696781"
            }
          ]
        },
        {
          "id": "f2963c6a-955a-4ccb-8528-6779d54b4878",
          "name": "mymessagesv2messagesmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "myMessages/v2/messages/:messageId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "790d8b8e-b136-4fe4-8523-4b9ac5da2a27"
            }
          ]
        },
        {
          "id": "32434263-ab4f-4da8-a36c-9dab40b0d5af",
          "name": "mymessagesv2messagesmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "myMessages/v2/messages/:messageId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ba9f91e-b83d-4ae2-9fcc-f71706f8261b"
            }
          ]
        },
        {
          "id": "598b2415-18fb-4039-b185-dfbd3012646b",
          "name": "mymessagesv2messagesmessageidpartspartid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "myMessages/v2/messages/:messageId/parts/:partId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "partId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/{messageId}/parts/{partId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71f5d5c5-bf14-4178-ba66-70f9e8eee44e"
            }
          ]
        },
        {
          "id": "28d72b5e-ec39-4135-b328-b985854d07a2",
          "name": "mymessagesv2notificationconnectiondetails",
          "request": {
            "url": "http://api.att.com/myMessages/v2/notificationConnectionDetails",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/notificationConnectionDetails"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ba473e45-9909-49da-bb57-d955b9979aa2"
            }
          ]
        }
      ]
    },
    {
      "name": "Rest",
      "item": [
        {
          "id": "78bf4b22-fb8c-4860-a51b-2d76c670a4c2",
          "name": "rest1ads",
          "request": {
            "url": "http://api.att.com/rest/1/ads",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/rest/1/ads"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2005d35e-b5e7-47b3-ac69-ce80e185bd24"
            }
          ]
        }
      ]
    }
  ]
}