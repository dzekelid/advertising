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
  /userprofiles/{profileId}/dynamicTargetingKeys/{objectId}:
    delete:
      summary: Delete Dynamic Targeting Key
      description: Deletes an existing dynamic targeting key
      operationId: dfareporting.dynamicTargetingKeys.delete
      parameters:
      - in: query
        name: name
        description: Name of this dynamic targeting key
      - in: path
        name: objectId
        description: ID of the object of this dynamic targeting key
      - in: query
        name: objectType
        description: Type of the object of this dynamic targeting key
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - advertising
      - dynamic targeting key
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