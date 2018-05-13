---
swagger: "2.0"
info:
  title: Google Doubleclick API Update Pretargeting Config
  version: 1.0.0
  description: Inserts a new pretargeting configuration.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /pretargetingconfigs/{accountId}:
    post:
      summary: Update Pretargeting Config
      description: Inserts a new pretargeting configuration
      operationId: adexchangebuyer.pretargetingConfig.insert
      parameters:
      - in: path
        name: accountId
        description: The account id to insert the pretargeting config for
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - advertising
      - pretargeting config
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