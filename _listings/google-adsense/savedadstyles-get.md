---
swagger: "2.0"
info:
  title: AdSense Management
  description: Accesses AdSense publishers' inventory and generates performance reports.
  contact:
    name: Google
    url: https://google.com
  version: v1.4
host: www.googleapis.com
basePath: /adsense/v1.4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /savedadstyles:
    get:
      summary: ""
      description: List all saved ad styles in the user's account
      operationId: adsense.savedadstyles.list
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of saved ad styles to include in the response,
          used for paging
      - in: query
        name: pageToken
        description: A continuation token, used to page through saved ad styles
      responses:
        200:
          description: OK
      tags:
      - ""
definitions:
  Account:
    properties:
      creation_time:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      premium:
        description: This is a default description.
        type: parameters
      subAccounts:
        description: This is a default description.
        type: parameters
      timezone:
        description: This is a default description.
        type: parameters
  Accounts:
    properties:
      etag:
        description: This is a default description.
        type: parameters
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  AdClient:
    properties:
      arcOptIn:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      productCode:
        description: This is a default description.
        type: parameters
      supportsReporting:
        description: This is a default description.
        type: parameters
  AdClients:
    properties:
      etag:
        description: This is a default description.
        type: parameters
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  AdCode:
    properties:
      adCode:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  AdStyle:
    properties:
      colors:
        description: This is a default description.
        type: parameters
      corners:
        description: This is a default description.
        type: parameters
      font:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  AdUnit:
    properties:
      code:
        description: This is a default description.
        type: parameters
      contentAdsSettings:
        description: This is a default description.
        type: parameters
      feedAdsSettings:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      mobileContentAdsSettings:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      savedStyleId:
        description: This is a default description.
        type: parameters
      status:
        description: This is a default description.
        type: parameters
  AdUnits:
    properties:
      etag:
        description: This is a default description.
        type: parameters
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  AdsenseReportsGenerateResponse:
    properties:
      averages:
        description: This is a default description.
        type: parameters
      endDate:
        description: This is a default description.
        type: parameters
      headers:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      rows:
        description: This is a default description.
        type: parameters
      startDate:
        description: This is a default description.
        type: parameters
      totalMatchedRows:
        description: This is a default description.
        type: parameters
      totals:
        description: This is a default description.
        type: parameters
      warnings:
        description: This is a default description.
        type: parameters
  Alert:
    properties:
      id:
        description: This is a default description.
        type: parameters
      isDismissible:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      message:
        description: This is a default description.
        type: parameters
      severity:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
  Alerts:
    properties:
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  CustomChannel:
    properties:
      code:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      targetingInfo:
        description: This is a default description.
        type: parameters
  CustomChannels:
    properties:
      etag:
        description: This is a default description.
        type: parameters
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  Metadata:
    properties:
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  Payment:
    properties:
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      paymentAmount:
        description: This is a default description.
        type: parameters
      paymentAmountCurrencyCode:
        description: This is a default description.
        type: parameters
      paymentDate:
        description: This is a default description.
        type: parameters
  Payments:
    properties:
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  ReportingMetadataEntry:
    properties:
      compatibleDimensions:
        description: This is a default description.
        type: parameters
      compatibleMetrics:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      requiredDimensions:
        description: This is a default description.
        type: parameters
      requiredMetrics:
        description: This is a default description.
        type: parameters
      supportedProducts:
        description: This is a default description.
        type: parameters
  SavedAdStyle:
    properties:
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  SavedAdStyles:
    properties:
      etag:
        description: This is a default description.
        type: parameters
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  SavedReport:
    properties:
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  SavedReports:
    properties:
      etag:
        description: This is a default description.
        type: parameters
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  UrlChannel:
    properties:
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      urlPattern:
        description: This is a default description.
        type: parameters
  UrlChannels:
    properties:
      etag:
        description: This is a default description.
        type: parameters
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
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