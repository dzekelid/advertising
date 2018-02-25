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
  /userprofiles/{profileId}/dynamicTargetingKeys:
    get:
      summary: Get Dynamic Targeting Keys
      description: Retrieves a list of dynamic targeting keys
      operationId: dfareporting.dynamicTargetingKeys.list
      parameters:
      - in: query
        name: advertiserId
        description: Select only dynamic targeting keys whose object has this advertiser
          ID
      - in: query
        name: names
        description: Select only dynamic targeting keys exactly matching these names
      - in: query
        name: objectId
        description: Select only dynamic targeting keys with this object ID
      - in: query
        name: objectType
        description: Select only dynamic targeting keys with this object type
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
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