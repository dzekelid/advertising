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
  /userprofiles/{profileId}/changeLogs:
    get:
      summary: Get Change Logs
      description: Retrieves a list of change logs
      operationId: dfareporting.changeLogs.list
      parameters:
      - in: query
        name: action
        description: Select only change logs with the specified action
      - in: query
        name: ids
        description: Select only change logs with these IDs
      - in: query
        name: maxChangeTime
        description: Select only change logs whose change time is before the specified
          maxChangeTime
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: minChangeTime
        description: Select only change logs whose change time is before the specified
          minChangeTime
      - in: query
        name: objectIds
        description: Select only change logs with these object IDs
      - in: query
        name: objectType
        description: Select only change logs with the specified object type
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Select only change logs whose object ID, user name, old or new
          values match the search string
      - in: query
        name: userProfileIds
        description: Select only change logs with these user profile IDs
      responses:
        200:
          description: OK
      tags:
      - advertising
      - change log
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