---
swagger: "2.0"
info:
  title: Ad Exchange Seller
  description: Accesses the inventory of Ad Exchange seller users and generates reports.
  contact:
    name: Google
    url: https://google.com
  version: v2.0
host: www.googleapis.com
basePath: /adexchangeseller/v2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{accountId}/preferreddeals/{dealId}:
    get:
      summary: Get Preferred Deal
      description: Get information about the selected Ad Exchange Preferred Deal
      operationId: adexchangeseller.accounts.preferreddeals.get
      parameters:
      - in: path
        name: accountId
        description: Account owning the deal
      - in: path
        name: dealId
        description: Preferred deal to get information about
      responses:
        200:
          description: OK
      tags:
      - deal
definitions:
  Account:
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
  Alert:
    properties:
      id:
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
  PreferredDeal:
    properties:
      advertiserName:
        description: This is a default description.
        type: parameters
      buyerNetworkName:
        description: This is a default description.
        type: parameters
      currencyCode:
        description: This is a default description.
        type: parameters
      endTime:
        description: This is a default description.
        type: parameters
      fixedCpm:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      startTime:
        description: This is a default description.
        type: parameters
  PreferredDeals:
    properties:
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  Report:
    properties:
      averages:
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
      totalMatchedRows:
        description: This is a default description.
        type: parameters
      totals:
        description: This is a default description.
        type: parameters
      warnings:
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