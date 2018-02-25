---
swagger: "2.0"
info:
  title: Google Doubleclick Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /billinginfo/{accountId}/{billingId}:
    patch:
      summary: Get Budget Amount
      description: Updates the budget amount for the budget of the adgroup specified
        by the accountId and billingId, with the budget amount in the request
      operationId: adexchangebuyer.budget.patch
      parameters:
      - in: path
        name: accountId
        description: The account id associated with the budget being updated
      - in: path
        name: billingId
        description: The billing id associated with the budget being updated
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - budget
definitions: []
x-collection-name: Google Doubleclick
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