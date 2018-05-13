---
swagger: "2.0"
info:
  title: Google Doubleclick API Get Account
  version: 1.0.0
  description: Gets one account by ID.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{id}:
    get:
      summary: Get Account
      description: Gets one account by ID
      operationId: adexchangebuyer.accounts.get
      parameters:
      - in: path
        name: id
        description: The account id
      responses:
        200:
          description: OK
      tags:
      - advertising
      - account
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