---
swagger: "2.0"
info:
  title: Google Doubleclick API Update Event Tag
  version: 1.0.0
  description: Updates an existing event tag. This method supports patch semantics.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/eventTags:
    patch:
      summary: Update Event Tag
      description: Updates an existing event tag
      operationId: dfareporting.eventTags.patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: id
        description: Event tag ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - advertising
      - event tag
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