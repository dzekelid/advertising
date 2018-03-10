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
  /userprofiles/{profileId}/targetableRemarketingLists:
    get:
      summary: Get Targetable Remarketing Lists
      description: Retrieves a list of targetable remarketing lists, possibly filtered
      operationId: dfareporting.targetableRemarketingLists.list
      parameters:
      - in: query
        name: active
        description: Select only active or only inactive targetable remarketing lists
      - in: query
        name: advertiserId
        description: Select only targetable remarketing lists targetable by these
          advertisers
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: name
        description: Allows searching for objects by name or ID
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      responses:
        200:
          description: OK
      tags:
      - advertising
      - remarketing list
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