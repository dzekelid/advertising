---
swagger: "2.0"
info:
  title: Google Doubleclick API Get Saved Report
  version: 1.0.0
  description: Generate an Ad Exchange report based on the saved report ID sent in
    the query parameters.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{accountId}/reports/{savedReportId}:
    get:
      summary: Get Saved Report
      description: Generate an Ad Exchange report based on the saved report ID sent
        in the query parameters
      operationId: adexchangeseller.accounts.reports.saved.generate
      parameters:
      - in: path
        name: accountId
        description: Account owning the saved report
      - in: query
        name: locale
        description: Optional locale to use for translating report output to a local
          language
      - in: query
        name: maxResults
        description: The maximum number of rows of report data to return
      - in: path
        name: savedReportId
        description: The saved report to retrieve
      - in: query
        name: startIndex
        description: Index of the first row of report data to return
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