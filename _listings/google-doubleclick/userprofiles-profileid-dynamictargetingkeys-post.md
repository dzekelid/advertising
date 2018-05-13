---
swagger: "2.0"
info:
  title: Google Doubleclick API Insert Dynamic Targeting Key
  version: 1.0.0
  description: Inserts a new dynamic targeting key. Keys must be created at the advertiser
    level before being assigned to the advertiser's ads, creatives, or placements.
    There is a maximum of 1000 keys per advertiser, out of which a maximum of 20 keys
    can be assigned per ad, creative, or placement.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/dynamicTargetingKeys:
    post:
      summary: Insert Dynamic Targeting Key
      description: Inserts a new dynamic targeting key
      operationId: dfareporting.dynamicTargetingKeys.insert
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
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