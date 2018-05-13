---
swagger: "2.0"
info:
  title: Google Doubleclick API Update Pretargeting Config
  version: 1.0.0
  description: Updates an existing pretargeting config. This method supports patch
    semantics.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /pretargetingconfigs/{accountId}/{configId}:
    patch:
      summary: Update Pretargeting Config
      description: Updates an existing pretargeting config
      operationId: adexchangebuyer.pretargetingConfig.patch
      parameters:
      - in: path
        name: accountId
        description: The account id to update the pretargeting config for
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: configId
        description: The specific id of the configuration to update
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