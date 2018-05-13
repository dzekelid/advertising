---
swagger: "2.0"
info:
  title: Google Doubleclick API Get Directory Sites
  version: 1.0.0
  description: Retrieves a list of directory sites, possibly filtered. This method
    supports paging.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/directorySites:
    get:
      summary: Get Directory Sites
      description: Retrieves a list of directory sites, possibly filtered
      operationId: dfareporting.directorySites.list
      parameters:
      - in: query
        name: acceptsInStreamVideoPlacements
        description: This search filter is no longer supported and will have no effect
          on the results returned
      - in: query
        name: acceptsInterstitialPlacements
        description: This search filter is no longer supported and will have no effect
          on the results returned
      - in: query
        name: acceptsPublisherPaidPlacements
        description: Select only directory sites that accept publisher paid placements
      - in: query
        name: active
        description: Select only active directory sites
      - in: query
        name: countryId
        description: Select only directory sites with this country ID
      - in: query
        name: dfp_network_code
        description: Select only directory sites with this DFP network code
      - in: query
        name: ids
        description: Select only directory sites with these IDs
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: query
        name: parentId
        description: Select only directory sites with this parent ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for objects by name, ID or URL
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
      - directory site
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