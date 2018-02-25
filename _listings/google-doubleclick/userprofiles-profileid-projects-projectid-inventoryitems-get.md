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
  /userprofiles/{profileId}/projects/{projectId}/inventoryItems:
    get:
      summary: Get Inventory Items
      description: Retrieves a list of inventory items, possibly filtered
      operationId: dfareporting.inventoryItems.list
      parameters:
      - in: query
        name: ids
        description: Select only inventory items with these IDs
      - in: query
        name: inPlan
        description: Select only inventory items that are in plan
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: orderId
        description: Select only inventory items that belong to specified orders
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: path
        name: projectId
        description: Project ID for order documents
      - in: query
        name: siteId
        description: Select only inventory items that are associated with these sites
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      - in: query
        name: type
        description: Select only inventory items with this type
      responses:
        200:
          description: OK
      tags:
      - inventory item
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