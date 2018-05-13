---
swagger: "2.0"
info:
  title: Google Doubleclick API Get Directory Site Contact
  version: 1.0.0
  description: Gets one directory site contact by ID.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/directorySiteContacts/{id}:
    get:
      summary: Get Directory Site Contact
      description: Gets one directory site contact by ID
      operationId: dfareporting.directorySiteContacts.get
      parameters:
      - in: path
        name: id
        description: Directory site contact ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - advertising
      - contact
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