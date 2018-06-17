{
  "info": {
    "name": "Google Doubleclick API Get Billing Info",
    "_postman_id": "4016494f-eef3-4f45-bbea-53806cd21062",
    "description": "Retrieves a list of billing information for all accounts of the authenticated user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Advertising",
      "item": [
        {
          "id": "9dae197c-2d59-4ada-9c86-995302055821",
          "name": "adexchangebuyer.billingInfo.list",
          "request": {
            "url": "http://example.com/api/billinginfo",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a list of billing information for all accounts of the authenticated user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ba228343-3767-4f7f-9a0b-184b6f28c1d2"
            }
          ]
        }
      ]
    }
  ]
}