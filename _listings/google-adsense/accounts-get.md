---
swagger: "2.0"
info:
  title: AdSense Host
  description: Generates performance reports, generates ad codes, and provides publisher
    management capabilities for AdSense Hosts.
  contact:
    name: Google
    url: https://google.com
  version: v4.1
host: www.googleapis.com
basePath: /adsensehost/v4.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts:
    get:
      summary: Get Accounts
      description: List hosted accounts associated with this AdSense account by ad
        client id
      operationId: adsensehost.accounts.list
      parameters:
      - in: query
        name: filterAdClientId
        description: Ad clients to list accounts for
      responses:
        200:
          description: OK
      tags:
      - account
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
      status:
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
  AssociationSession:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      productCodes:
        description: This is a default description.
        type: parameters
      redirectUrl:
        description: This is a default description.
        type: parameters
      status:
        description: This is a default description.
        type: parameters
      userLocale:
        description: This is a default description.
        type: parameters
      websiteLocale:
        description: This is a default description.
        type: parameters
      websiteUrl:
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