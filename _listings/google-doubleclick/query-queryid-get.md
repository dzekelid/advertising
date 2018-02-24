---
swagger: "2.0"
info:
  title: DoubleClick Bid Manager
  description: API for viewing and managing your reports in DoubleClick Bid Manager.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /doubleclickbidmanager/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /query/{queryId}:
    get:
      summary: 'Get Stored Query '
      description: Retrieves a stored query
      operationId: doubleclickbidmanager.queries.getquery
      parameters:
      - in: path
        name: queryId
        description: Query ID to retrieve
      responses:
        200:
          description: OK
      tags:
      - query
definitions:
  DownloadLineItemsRequest:
    properties:
      fileSpec:
        description: This is a default description.
        type: post
      filterIds:
        description: This is a default description.
        type: post
      filterType:
        description: This is a default description.
        type: post
      format:
        description: This is a default description.
        type: post
  DownloadLineItemsResponse:
    properties:
      lineItems:
        description: This is a default description.
        type: post
  DownloadRequest:
    properties:
      fileTypes:
        description: This is a default description.
        type: post
      filterIds:
        description: This is a default description.
        type: post
      filterType:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  DownloadResponse:
    properties:
      adGroups:
        description: This is a default description.
        type: post
      ads:
        description: This is a default description.
        type: post
      insertionOrders:
        description: This is a default description.
        type: post
      lineItems:
        description: This is a default description.
        type: post
  FilterPair:
    properties:
      type:
        description: This is a default description.
        type: post
      value:
        description: This is a default description.
        type: post
  ListQueriesResponse:
    properties:
      kind:
        description: This is a default description.
        type: post
      queries:
        description: This is a default description.
        type: post
  ListReportsResponse:
    properties:
      kind:
        description: This is a default description.
        type: post
      reports:
        description: This is a default description.
        type: post
  Parameters:
    properties:
      filters:
        description: This is a default description.
        type: post
      groupBys:
        description: This is a default description.
        type: post
      includeInviteData:
        description: This is a default description.
        type: post
      metrics:
        description: This is a default description.
        type: post
      type:
        description: This is a default description.
        type: post
  Query:
    properties:
      kind:
        description: This is a default description.
        type: post
      queryId:
        description: This is a default description.
        type: post
      reportDataEndTimeMs:
        description: This is a default description.
        type: post
      reportDataStartTimeMs:
        description: This is a default description.
        type: post
      timezoneCode:
        description: This is a default description.
        type: post
  QueryMetadata:
    properties:
      dataRange:
        description: This is a default description.
        type: post
      format:
        description: This is a default description.
        type: post
      googleCloudStoragePathForLatestReport:
        description: This is a default description.
        type: post
      googleDrivePathForLatestReport:
        description: This is a default description.
        type: post
      latestReportRunTimeMs:
        description: This is a default description.
        type: post
      locale:
        description: This is a default description.
        type: post
      reportCount:
        description: This is a default description.
        type: post
      running:
        description: This is a default description.
        type: post
      sendNotification:
        description: This is a default description.
        type: post
      shareEmailAddress:
        description: This is a default description.
        type: post
  QuerySchedule:
    properties:
      endTimeMs:
        description: This is a default description.
        type: post
      frequency:
        description: This is a default description.
        type: post
      nextRunMinuteOfDay:
        description: This is a default description.
        type: post
      nextRunTimezoneCode:
        description: This is a default description.
        type: post
  Report:
    properties: []
  ReportFailure:
    properties:
      errorCode:
        description: This is a default description.
        type: post
  ReportKey:
    properties:
      queryId:
        description: This is a default description.
        type: post
      reportId:
        description: This is a default description.
        type: post
  ReportMetadata:
    properties:
      googleCloudStoragePath:
        description: This is a default description.
        type: post
      reportDataEndTimeMs:
        description: This is a default description.
        type: post
      reportDataStartTimeMs:
        description: This is a default description.
        type: post
  ReportStatus:
    properties:
      finishTimeMs:
        description: This is a default description.
        type: post
      format:
        description: This is a default description.
        type: post
      state:
        description: This is a default description.
        type: post
  RowStatus:
    properties:
      changed:
        description: This is a default description.
        type: post
      entityId:
        description: This is a default description.
        type: post
      entityName:
        description: This is a default description.
        type: post
      errors:
        description: This is a default description.
        type: post
      persisted:
        description: This is a default description.
        type: post
      rowNumber:
        description: This is a default description.
        type: post
  RunQueryRequest:
    properties:
      dataRange:
        description: This is a default description.
        type: post
      reportDataEndTimeMs:
        description: This is a default description.
        type: post
      reportDataStartTimeMs:
        description: This is a default description.
        type: post
      timezoneCode:
        description: This is a default description.
        type: post
  UploadLineItemsRequest:
    properties:
      dryRun:
        description: This is a default description.
        type: post
      format:
        description: This is a default description.
        type: post
      lineItems:
        description: This is a default description.
        type: post
  UploadLineItemsResponse:
    properties: []
  UploadStatus:
    properties:
      errors:
        description: This is a default description.
        type: post
      rowStatus:
        description: This is a default description.
        type: post
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