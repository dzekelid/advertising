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
  /userprofiles/{profileId}/advertisers:
    get:
      summary: Get Advertisers
      description: Retrieves a list of advertisers, possibly filtered
      operationId: dfareporting.advertisers.list
      parameters:
      - in: query
        name: advertiserGroupIds
        description: Select only advertisers with these advertiser group IDs
      - in: query
        name: floodlightConfigurationIds
        description: Select only advertisers with these floodlight configuration IDs
      - in: query
        name: ids
        description: Select only advertisers with these IDs
      - in: query
        name: includeAdvertisersWithoutGroupsOnly
        description: Select only advertisers which do not belong to any advertiser
          group
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: onlyParent
        description: Select only advertisers which use another advertiser's floodlight
          configuration
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for objects by name or ID
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      - in: query
        name: status
        description: Select only advertisers with the specified status
      - in: query
        name: subaccountId
        description: Select only advertisers with these subaccount IDs
      responses:
        200:
          description: OK
      tags:
      - advertising
      - advertiser
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