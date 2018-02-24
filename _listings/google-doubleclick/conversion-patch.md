---
swagger: "2.0"
info:
  title: DoubleClick Search
  description: Reports and modifies your advertising data in DoubleClick Search (for
    example, campaigns, ad groups, keywords, and conversions).
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /doubleclicksearch/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /conversion:
    patch:
      summary: Update Conversions
      description: Updates a batch of conversions in DoubleClick Search
      operationId: doubleclicksearch.conversion.patch
      parameters:
      - in: query
        name: advertiserId
        description: Numeric ID of the advertiser
      - in: query
        name: agencyId
        description: Numeric ID of the agency
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: endDate
        description: Last date (inclusive) on which to retrieve conversions
      - in: query
        name: engineAccountId
        description: Numeric ID of the engine account
      - in: query
        name: rowCount
        description: The number of conversions to return per call
      - in: query
        name: startDate
        description: First date (inclusive) on which to retrieve conversions
      - in: query
        name: startRow
        description: The 0-based starting index for retrieving conversions results
      responses:
        200:
          description: OK
      tags:
      - conversion
definitions:
  Availability:
    properties:
      advertiserId:
        description: This is a default description.
        type: parameters
      agencyId:
        description: This is a default description.
        type: parameters
      availabilityTimestamp:
        description: This is a default description.
        type: parameters
      segmentationId:
        description: This is a default description.
        type: parameters
      segmentationName:
        description: This is a default description.
        type: parameters
      segmentationType:
        description: This is a default description.
        type: parameters
  Conversion:
    properties:
      adGroupId:
        description: This is a default description.
        type: parameters
      adId:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      agencyId:
        description: This is a default description.
        type: parameters
      attributionModel:
        description: This is a default description.
        type: parameters
      campaignId:
        description: This is a default description.
        type: parameters
      channel:
        description: This is a default description.
        type: parameters
      clickId:
        description: This is a default description.
        type: parameters
      conversionId:
        description: This is a default description.
        type: parameters
      conversionModifiedTimestamp:
        description: This is a default description.
        type: parameters
  ConversionList:
    properties:
      conversion:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  CustomDimension:
    properties:
      name:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  CustomMetric:
    properties:
      name:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  Report:
    properties:
      files:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      isReportReady:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      rowCount:
        description: This is a default description.
        type: parameters
      rows:
        description: This is a default description.
        type: parameters
      statisticsCurrencyCode:
        description: This is a default description.
        type: parameters
      statisticsTimeZone:
        description: This is a default description.
        type: parameters
  ReportApiColumnSpec:
    properties:
      columnName:
        description: This is a default description.
        type: parameters
      customDimensionName:
        description: This is a default description.
        type: parameters
      customMetricName:
        description: This is a default description.
        type: parameters
      endDate:
        description: This is a default description.
        type: parameters
      groupByColumn:
        description: This is a default description.
        type: parameters
      headerText:
        description: This is a default description.
        type: parameters
      platformSource:
        description: This is a default description.
        type: parameters
      productReportPerspective:
        description: This is a default description.
        type: parameters
      savedColumnName:
        description: This is a default description.
        type: parameters
      startDate:
        description: This is a default description.
        type: parameters
  ReportRequest:
    properties:
      columns:
        description: This is a default description.
        type: parameters
      downloadFormat:
        description: This is a default description.
        type: parameters
      filters:
        description: This is a default description.
        type: parameters
      includeDeletedEntities:
        description: This is a default description.
        type: parameters
      includeRemovedEntities:
        description: This is a default description.
        type: parameters
      maxRowsPerFile:
        description: This is a default description.
        type: parameters
      orderBy:
        description: This is a default description.
        type: parameters
      reportScope:
        description: This is a default description.
        type: parameters
      reportType:
        description: This is a default description.
        type: parameters
      rowCount:
        description: This is a default description.
        type: parameters
  SavedColumn:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      savedColumnName:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
  SavedColumnList:
    properties:
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  UpdateAvailabilityRequest:
    properties:
      availabilities:
        description: This is a default description.
        type: parameters
  UpdateAvailabilityResponse:
    properties:
      availabilities:
        description: This is a default description.
        type: parameters
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