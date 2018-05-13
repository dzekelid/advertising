---
swagger: "2.0"
info:
  title: Google Doubleclick API Get Event Tags
  version: 1.0.0
  description: Retrieves a list of event tags, possibly filtered.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/eventTags:
    get:
      summary: Get Event Tags
      description: Retrieves a list of event tags, possibly filtered
      operationId: dfareporting.eventTags.list
      parameters:
      - in: query
        name: adId
        description: Select only event tags that belong to this ad
      - in: query
        name: advertiserId
        description: Select only event tags that belong to this advertiser
      - in: query
        name: campaignId
        description: Select only event tags that belong to this campaign
      - in: query
        name: definitionsOnly
        description: Examine only the specified campaign or advertiser's event tags
          for matching selector criteria
      - in: query
        name: enabled
        description: Select only enabled event tags
      - in: query
        name: eventTagTypes
        description: Select only event tags with the specified event tag types
      - in: query
        name: ids
        description: Select only event tags with these IDs
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