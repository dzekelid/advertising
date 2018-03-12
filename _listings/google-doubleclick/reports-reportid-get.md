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
  /reports/{reportId}:
    get:
      summary: Get Report Status
      description: Polls for the status of a report request
      operationId: doubleclicksearch.reports.get
      parameters:
      - in: path
        name: reportId
        description: ID of the report request being polled
      responses:
        200:
          description: OK
      tags:
      - advertising
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