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
  /userprofiles/{profileId}/ads:
    get:
      summary: Get Ads
      description: Retrieves a list of ads, possibly filtered
      operationId: dfareporting.ads.list
      parameters:
      - in: query
        name: active
        description: Select only active ads
      - in: query
        name: advertiserId
        description: Select only ads with this advertiser ID
      - in: query
        name: archived
        description: Select only archived ads
      - in: query
        name: audienceSegmentIds
        description: Select only ads with these audience segment IDs
      - in: query
        name: campaignIds
        description: Select only ads with these campaign IDs
      - in: query
        name: compatibility
        description: Select default ads with the specified compatibility
      - in: query
        name: creativeIds
        description: Select only ads with these creative IDs assigned
      - in: query
        name: creativeOptimizationConfigurationIds
        description: Select only ads with these creative optimization configuration
          IDs
      - in: query
        name: dynamicClickTracker
        description: Select only dynamic click trackers
      - in: query
        name: ids
        description: Select only ads with these IDs
      - in: query
        name: landingPageIds
        description: Select only ads with these landing page IDs
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: overriddenEventTagId
        description: Select only ads with this event tag override ID
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: query
        name: placementIds
        description: Select only ads with these placement IDs assigned
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: remarketingListIds
        description: Select only ads whose list targeting expression use these remarketing
          list IDs
      - in: query
        name: searchString
        description: Allows searching for objects by name or ID
      - in: query
        name: sizeIds
        description: Select only ads with these size IDs
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      - in: query
        name: sslCompliant
        description: Select only ads that are SSL-compliant
      - in: query
        name: sslRequired
        description: Select only ads that require SSL
      - in: query
        name: type
        description: Select only ads with these types
      responses:
        200:
          description: OK
      tags:
      - ad
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