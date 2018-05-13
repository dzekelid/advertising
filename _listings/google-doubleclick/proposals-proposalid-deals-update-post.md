---
swagger: "2.0"
info:
  title: Google Doubleclick API Update Proposal Deal
  version: 1.0.0
  description: Replaces all the deals in the proposal with the passed in deals
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /proposals/{proposalId}/deals/update:
    post:
      summary: Update Proposal Deal
      description: Replaces all the deals in the proposal with the passed in deals
      operationId: adexchangebuyer.marketplacedeals.update
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: proposalId
        description: The proposalId to edit deals on
      responses:
        200:
          description: OK
      tags:
      - advertising
      - deal
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