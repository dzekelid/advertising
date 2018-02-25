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
  /reports:
    post:
      summary: Insert Report
      description: Inserts a report request into the reporting system
      operationId: doubleclicksearch.reports.request
      parameters:
      - in: body
        name: reportRequest
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - report
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