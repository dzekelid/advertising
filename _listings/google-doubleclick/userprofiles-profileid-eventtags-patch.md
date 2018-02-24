---
swagger: "2.0"
info:
  title: DCM/DFA Reporting And Trafficking
  description: Manages your DoubleClick Campaign Manager ad campaigns and reports.
  contact:
    name: Google
    url: https://google.com
  version: v2.7
host: www.googleapis.com
basePath: /dfareporting/v2.7
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/eventTags:
    patch:
      summary: Update Event Tag
      description: Updates an existing event tag
      operationId: dfareporting.eventTags.patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: id
        description: Event tag ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - event tag
definitions:
  Account:
    properties:
      accountPermissionIds:
        description: This is a default description.
        type: parameters
      accountProfile:
        description: This is a default description.
        type: parameters
      active:
        description: This is a default description.
        type: parameters
      activeAdsLimitTier:
        description: This is a default description.
        type: parameters
      activeViewOptOut:
        description: This is a default description.
        type: parameters
      availablePermissionIds:
        description: This is a default description.
        type: parameters
      countryId:
        description: This is a default description.
        type: parameters
      currencyId:
        description: This is a default description.
        type: parameters
      defaultCreativeSizeId:
        description: This is a default description.
        type: parameters
      description:
        description: This is a default description.
        type: parameters
  AccountActiveAdSummary:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      activeAds:
        description: This is a default description.
        type: parameters
      activeAdsLimitTier:
        description: This is a default description.
        type: parameters
      availableAds:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  AccountPermission:
    properties:
      accountProfiles:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      level:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      permissionGroupId:
        description: This is a default description.
        type: parameters
  AccountPermissionGroup:
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
  AccountPermissionGroupsListResponse:
    properties:
      accountPermissionGroups:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  AccountPermissionsListResponse:
    properties:
      accountPermissions:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  AccountUserProfile:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      active:
        description: This is a default description.
        type: parameters
      comments:
        description: This is a default description.
        type: parameters
      email:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      locale:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      subaccountId:
        description: This is a default description.
        type: parameters
      traffickerType:
        description: This is a default description.
        type: parameters
  AccountUserProfilesListResponse:
    properties:
      accountUserProfiles:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  AccountsListResponse:
    properties:
      accounts:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  Activities:
    properties:
      filters:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      metricNames:
        description: This is a default description.
        type: parameters
  Ad:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      active:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      archived:
        description: This is a default description.
        type: parameters
      audienceSegmentId:
        description: This is a default description.
        type: parameters
      campaignId:
        description: This is a default description.
        type: parameters
      comments:
        description: This is a default description.
        type: parameters
      compatibility:
        description: This is a default description.
        type: parameters
      creativeGroupAssignments:
        description: This is a default description.
        type: parameters
      dynamicClickTracker:
        description: This is a default description.
        type: parameters
  AdSlot:
    properties:
      comment:
        description: This is a default description.
        type: parameters
      compatibility:
        description: This is a default description.
        type: parameters
      height:
        description: This is a default description.
        type: parameters
      linkedPlacementId:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      paymentSourceType:
        description: This is a default description.
        type: parameters
      primary:
        description: This is a default description.
        type: parameters
      width:
        description: This is a default description.
        type: parameters
  AdsListResponse:
    properties:
      ads:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  Advertiser:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      advertiserGroupId:
        description: This is a default description.
        type: parameters
      clickThroughUrlSuffix:
        description: This is a default description.
        type: parameters
      defaultClickThroughEventTagId:
        description: This is a default description.
        type: parameters
      defaultEmail:
        description: This is a default description.
        type: parameters
      floodlightConfigurationId:
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
      originalFloodlightConfigurationId:
        description: This is a default description.
        type: parameters
  AdvertiserGroup:
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
      name:
        description: This is a default description.
        type: parameters
  AdvertiserGroupsListResponse:
    properties:
      advertiserGroups:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  AdvertisersListResponse:
    properties:
      advertisers:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  AudienceSegment:
    properties:
      allocation:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  AudienceSegmentGroup:
    properties:
      audienceSegments:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  Browser:
    properties:
      browserVersionId:
        description: This is a default description.
        type: parameters
      dartId:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      majorVersion:
        description: This is a default description.
        type: parameters
      minorVersion:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  BrowsersListResponse:
    properties:
      browsers:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  Campaign:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      additionalCreativeOptimizationConfigurations:
        description: This is a default description.
        type: parameters
      advertiserGroupId:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      archived:
        description: This is a default description.
        type: parameters
      audienceSegmentGroups:
        description: This is a default description.
        type: parameters
      billingInvoiceCode:
        description: This is a default description.
        type: parameters
      comment:
        description: This is a default description.
        type: parameters
      creativeGroupIds:
        description: This is a default description.
        type: parameters
      endDate:
        description: This is a default description.
        type: parameters
  CampaignCreativeAssociation:
    properties:
      creativeId:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  CampaignCreativeAssociationsListResponse:
    properties:
      campaignCreativeAssociations:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  CampaignsListResponse:
    properties:
      campaigns:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  ChangeLog:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      action:
        description: This is a default description.
        type: parameters
      changeTime:
        description: This is a default description.
        type: parameters
      fieldName:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      newValue:
        description: This is a default description.
        type: parameters
      objectId:
        description: This is a default description.
        type: parameters
      objectType:
        description: This is a default description.
        type: parameters
      oldValue:
        description: This is a default description.
        type: parameters
  ChangeLogsListResponse:
    properties:
      changeLogs:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  CitiesListResponse:
    properties:
      cities:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  City:
    properties:
      countryCode:
        description: This is a default description.
        type: parameters
      countryDartId:
        description: This is a default description.
        type: parameters
      dartId:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      metroCode:
        description: This is a default description.
        type: parameters
      metroDmaId:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      regionCode:
        description: This is a default description.
        type: parameters
      regionDartId:
        description: This is a default description.
        type: parameters
  ClickTag:
    properties:
      eventName:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  ClickThroughUrl:
    properties:
      computedClickThroughUrl:
        description: This is a default description.
        type: parameters
      customClickThroughUrl:
        description: This is a default description.
        type: parameters
      defaultLandingPage:
        description: This is a default description.
        type: parameters
      landingPageId:
        description: This is a default description.
        type: parameters
  ClickThroughUrlSuffixProperties:
    properties:
      clickThroughUrlSuffix:
        description: This is a default description.
        type: parameters
      overrideInheritedSuffix:
        description: This is a default description.
        type: parameters
  CompanionClickThroughOverride:
    properties:
      creativeId:
        description: This is a default description.
        type: parameters
  CompanionSetting:
    properties:
      companionsDisabled:
        description: This is a default description.
        type: parameters
      enabledSizes:
        description: This is a default description.
        type: parameters
      imageOnly:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  CompatibleFields:
    properties:
      kind:
        description: This is a default description.
        type: parameters
  ConnectionType:
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
  ConnectionTypesListResponse:
    properties:
      connectionTypes:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  ContentCategoriesListResponse:
    properties:
      contentCategories:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  ContentCategory:
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
      name:
        description: This is a default description.
        type: parameters
  Conversion:
    properties:
      childDirectedTreatment:
        description: This is a default description.
        type: parameters
      customVariables:
        description: This is a default description.
        type: parameters
      encryptedUserId:
        description: This is a default description.
        type: parameters
      encryptedUserIdCandidates:
        description: This is a default description.
        type: parameters
      floodlightActivityId:
        description: This is a default description.
        type: parameters
      floodlightConfigurationId:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      limitAdTracking:
        description: This is a default description.
        type: parameters
      mobileDeviceId:
        description: This is a default description.
        type: parameters
      ordinal:
        description: This is a default description.
        type: parameters
  ConversionError:
    properties:
      code:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      message:
        description: This is a default description.
        type: parameters
  ConversionStatus:
    properties:
      errors:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  ConversionsBatchInsertRequest:
    properties:
      conversions:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  ConversionsBatchInsertResponse:
    properties:
      hasFailures:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      status:
        description: This is a default description.
        type: parameters
  CountriesListResponse:
    properties:
      countries:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  Country:
    properties:
      countryCode:
        description: This is a default description.
        type: parameters
      dartId:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      sslEnabled:
        description: This is a default description.
        type: parameters
  Creative:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      active:
        description: This is a default description.
        type: parameters
      adParameters:
        description: This is a default description.
        type: parameters
      adTagKeys:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      allowScriptAccess:
        description: This is a default description.
        type: parameters
      archived:
        description: This is a default description.
        type: parameters
      artworkType:
        description: This is a default description.
        type: parameters
      authoringSource:
        description: This is a default description.
        type: parameters
      authoringTool:
        description: This is a default description.
        type: parameters
  CreativeAsset:
    properties:
      actionScript3:
        description: This is a default description.
        type: parameters
      active:
        description: This is a default description.
        type: parameters
      alignment:
        description: This is a default description.
        type: parameters
      artworkType:
        description: This is a default description.
        type: parameters
      bitRate:
        description: This is a default description.
        type: parameters
      childAssetType:
        description: This is a default description.
        type: parameters
      companionCreativeIds:
        description: This is a default description.
        type: parameters
      customStartTimeValue:
        description: This is a default description.
        type: parameters
      detectedFeatures:
        description: This is a default description.
        type: parameters
      displayType:
        description: This is a default description.
        type: parameters
  CreativeAssetId:
    properties:
      name:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
  CreativeAssetMetadata:
    properties:
      clickTags:
        description: This is a default description.
        type: parameters
      detectedFeatures:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      warnedValidationRules:
        description: This is a default description.
        type: parameters
  CreativeAssetSelection:
    properties:
      defaultAssetId:
        description: This is a default description.
        type: parameters
      rules:
        description: This is a default description.
        type: parameters
  CreativeAssignment:
    properties:
      active:
        description: This is a default description.
        type: parameters
      applyEventTags:
        description: This is a default description.
        type: parameters
      companionCreativeOverrides:
        description: This is a default description.
        type: parameters
      creativeGroupAssignments:
        description: This is a default description.
        type: parameters
      creativeId:
        description: This is a default description.
        type: parameters
      endTime:
        description: This is a default description.
        type: parameters
      richMediaExitOverrides:
        description: This is a default description.
        type: parameters
      sequence:
        description: This is a default description.
        type: parameters
      sslCompliant:
        description: This is a default description.
        type: parameters
      startTime:
        description: This is a default description.
        type: parameters
  CreativeCustomEvent:
    properties:
      advertiserCustomEventId:
        description: This is a default description.
        type: parameters
      advertiserCustomEventName:
        description: This is a default description.
        type: parameters
      advertiserCustomEventType:
        description: This is a default description.
        type: parameters
      artworkLabel:
        description: This is a default description.
        type: parameters
      artworkType:
        description: This is a default description.
        type: parameters
      exitUrl:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      targetType:
        description: This is a default description.
        type: parameters
      videoReportingId:
        description: This is a default description.
        type: parameters
  CreativeField:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      advertiserId:
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
      subaccountId:
        description: This is a default description.
        type: parameters
  CreativeFieldAssignment:
    properties:
      creativeFieldId:
        description: This is a default description.
        type: parameters
      creativeFieldValueId:
        description: This is a default description.
        type: parameters
  CreativeFieldValue:
    properties:
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  CreativeFieldValuesListResponse:
    properties:
      creativeFieldValues:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  CreativeFieldsListResponse:
    properties:
      creativeFields:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  CreativeGroup:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      groupNumber:
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
      subaccountId:
        description: This is a default description.
        type: parameters
  CreativeGroupAssignment:
    properties:
      creativeGroupId:
        description: This is a default description.
        type: parameters
      creativeGroupNumber:
        description: This is a default description.
        type: parameters
  CreativeGroupsListResponse:
    properties:
      creativeGroups:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  CreativeOptimizationConfiguration:
    properties:
      id:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      optimizationActivitys:
        description: This is a default description.
        type: parameters
      optimizationModel:
        description: This is a default description.
        type: parameters
  CreativeRotation:
    properties:
      creativeAssignments:
        description: This is a default description.
        type: parameters
      creativeOptimizationConfigurationId:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
      weightCalculationStrategy:
        description: This is a default description.
        type: parameters
  CreativeSettings:
    properties:
      iFrameFooter:
        description: This is a default description.
        type: parameters
      iFrameHeader:
        description: This is a default description.
        type: parameters
  CreativesListResponse:
    properties:
      creatives:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  CrossDimensionReachReportCompatibleFields:
    properties:
      breakdown:
        description: This is a default description.
        type: parameters
      dimensionFilters:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      metrics:
        description: This is a default description.
        type: parameters
      overlapMetrics:
        description: This is a default description.
        type: parameters
  CustomFloodlightVariable:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  CustomRichMediaEvents:
    properties:
      filteredEventIds:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  DateRange:
    properties:
      endDate:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      relativeDateRange:
        description: This is a default description.
        type: parameters
      startDate:
        description: This is a default description.
        type: parameters
  DayPartTargeting:
    properties:
      daysOfWeek:
        description: This is a default description.
        type: parameters
      hoursOfDay:
        description: This is a default description.
        type: parameters
      userLocalTime:
        description: This is a default description.
        type: parameters
  DefaultClickThroughEventTagProperties:
    properties:
      defaultClickThroughEventTagId:
        description: This is a default description.
        type: parameters
      overrideInheritedEventTag:
        description: This is a default description.
        type: parameters
  DeliverySchedule:
    properties:
      hardCutoff:
        description: This is a default description.
        type: parameters
      impressionRatio:
        description: This is a default description.
        type: parameters
      priority:
        description: This is a default description.
        type: parameters
  DfpSettings:
    properties:
      dfp_network_code:
        description: This is a default description.
        type: parameters
      dfp_network_name:
        description: This is a default description.
        type: parameters
      programmaticPlacementAccepted:
        description: This is a default description.
        type: parameters
      pubPaidPlacementAccepted:
        description: This is a default description.
        type: parameters
      publisherPortalOnly:
        description: This is a default description.
        type: parameters
  Dimension:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  DimensionFilter:
    properties:
      dimensionName:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  DimensionValue:
    properties:
      dimensionName:
        description: This is a default description.
        type: parameters
      etag:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      matchType:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  DimensionValueList:
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
  DimensionValueRequest:
    properties:
      dimensionName:
        description: This is a default description.
        type: parameters
      endDate:
        description: This is a default description.
        type: parameters
      filters:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      startDate:
        description: This is a default description.
        type: parameters
  DirectorySite:
    properties:
      active:
        description: This is a default description.
        type: parameters
      contactAssignments:
        description: This is a default description.
        type: parameters
      countryId:
        description: This is a default description.
        type: parameters
      currencyId:
        description: This is a default description.
        type: parameters
      description:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      inpageTagFormats:
        description: This is a default description.
        type: parameters
      interstitialTagFormats:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  DirectorySiteContact:
    properties:
      address:
        description: This is a default description.
        type: parameters
      email:
        description: This is a default description.
        type: parameters
      firstName:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      lastName:
        description: This is a default description.
        type: parameters
      phone:
        description: This is a default description.
        type: parameters
      role:
        description: This is a default description.
        type: parameters
      title:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
  DirectorySiteContactAssignment:
    properties:
      contactId:
        description: This is a default description.
        type: parameters
      visibility:
        description: This is a default description.
        type: parameters
  DirectorySiteContactsListResponse:
    properties:
      directorySiteContacts:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  DirectorySiteSettings:
    properties:
      activeViewOptOut:
        description: This is a default description.
        type: parameters
      instream_video_placement_accepted:
        description: This is a default description.
        type: parameters
      interstitialPlacementAccepted:
        description: This is a default description.
        type: parameters
      nielsenOcrOptOut:
        description: This is a default description.
        type: parameters
      verificationTagOptOut:
        description: This is a default description.
        type: parameters
      videoActiveViewOptOut:
        description: This is a default description.
        type: parameters
  DirectorySitesListResponse:
    properties:
      directorySites:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  DynamicTargetingKey:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      objectId:
        description: This is a default description.
        type: parameters
      objectType:
        description: This is a default description.
        type: parameters
  DynamicTargetingKeysListResponse:
    properties:
      dynamicTargetingKeys:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  EncryptionInfo:
    properties:
      encryptionEntityId:
        description: This is a default description.
        type: parameters
      encryptionEntityType:
        description: This is a default description.
        type: parameters
      encryptionSource:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  EventTag:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      campaignId:
        description: This is a default description.
        type: parameters
      enabledByDefault:
        description: This is a default description.
        type: parameters
      excludeFromAdxRequests:
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
      siteFilterType:
        description: This is a default description.
        type: parameters
      siteIds:
        description: This is a default description.
        type: parameters
  EventTagOverride:
    properties:
      enabled:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
  EventTagsListResponse:
    properties:
      eventTags:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  File:
    properties:
      etag:
        description: This is a default description.
        type: parameters
      fileName:
        description: This is a default description.
        type: parameters
      format:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      lastModifiedTime:
        description: This is a default description.
        type: parameters
      reportId:
        description: This is a default description.
        type: parameters
      status:
        description: This is a default description.
        type: parameters
      urls:
        description: This is a default description.
        type: parameters
  FileList:
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
  Flight:
    properties:
      endDate:
        description: This is a default description.
        type: parameters
      rateOrCost:
        description: This is a default description.
        type: parameters
      startDate:
        description: This is a default description.
        type: parameters
      units:
        description: This is a default description.
        type: parameters
  FloodlightActivitiesGenerateTagResponse:
    properties:
      floodlightActivityTag:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  FloodlightActivitiesListResponse:
    properties:
      floodlightActivities:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  FloodlightActivity:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      cacheBustingType:
        description: This is a default description.
        type: parameters
      countingMethod:
        description: This is a default description.
        type: parameters
      defaultTags:
        description: This is a default description.
        type: parameters
      expectedUrl:
        description: This is a default description.
        type: parameters
      floodlightActivityGroupId:
        description: This is a default description.
        type: parameters
      floodlightActivityGroupName:
        description: This is a default description.
        type: parameters
      floodlightActivityGroupTagString:
        description: This is a default description.
        type: parameters
      floodlightActivityGroupType:
        description: This is a default description.
        type: parameters
  FloodlightActivityDynamicTag:
    properties:
      id:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      tag:
        description: This is a default description.
        type: parameters
  FloodlightActivityGroup:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      floodlightConfigurationId:
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
      subaccountId:
        description: This is a default description.
        type: parameters
      tagString:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
  FloodlightActivityGroupsListResponse:
    properties:
      floodlightActivityGroups:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  FloodlightActivityPublisherDynamicTag:
    properties:
      clickThrough:
        description: This is a default description.
        type: parameters
      directorySiteId:
        description: This is a default description.
        type: parameters
      siteId:
        description: This is a default description.
        type: parameters
      viewThrough:
        description: This is a default description.
        type: parameters
  FloodlightConfiguration:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      analyticsDataSharingEnabled:
        description: This is a default description.
        type: parameters
      exposureToConversionEnabled:
        description: This is a default description.
        type: parameters
      firstDayOfWeek:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      inAppAttributionTrackingEnabled:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      naturalSearchConversionAttributionOption:
        description: This is a default description.
        type: parameters
      standardVariableTypes:
        description: This is a default description.
        type: parameters
  FloodlightConfigurationsListResponse:
    properties:
      floodlightConfigurations:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  FloodlightReportCompatibleFields:
    properties:
      dimensionFilters:
        description: This is a default description.
        type: parameters
      dimensions:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      metrics:
        description: This is a default description.
        type: parameters
  FrequencyCap:
    properties:
      duration:
        description: This is a default description.
        type: parameters
      impressions:
        description: This is a default description.
        type: parameters
  FsCommand:
    properties:
      left:
        description: This is a default description.
        type: parameters
      positionOption:
        description: This is a default description.
        type: parameters
      top:
        description: This is a default description.
        type: parameters
      windowHeight:
        description: This is a default description.
        type: parameters
      windowWidth:
        description: This is a default description.
        type: parameters
  GeoTargeting:
    properties:
      cities:
        description: This is a default description.
        type: parameters
      countries:
        description: This is a default description.
        type: parameters
      excludeCountries:
        description: This is a default description.
        type: parameters
      metros:
        description: This is a default description.
        type: parameters
      postalCodes:
        description: This is a default description.
        type: parameters
      regions:
        description: This is a default description.
        type: parameters
  InventoryItem:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      adSlots:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      contentCategoryId:
        description: This is a default description.
        type: parameters
      estimatedClickThroughRate:
        description: This is a default description.
        type: parameters
      estimatedConversionRate:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      inPlan:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  InventoryItemsListResponse:
    properties:
      inventoryItems:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  KeyValueTargetingExpression:
    properties:
      expression:
        description: This is a default description.
        type: parameters
  LandingPage:
    properties:
      default:
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
      url:
        description: This is a default description.
        type: parameters
  LandingPagesListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      landingPages:
        description: This is a default description.
        type: parameters
  Language:
    properties:
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      languageCode:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  LanguageTargeting:
    properties:
      languages:
        description: This is a default description.
        type: parameters
  LanguagesListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      languages:
        description: This is a default description.
        type: parameters
  LastModifiedInfo:
    properties:
      time:
        description: This is a default description.
        type: parameters
  ListPopulationClause:
    properties:
      terms:
        description: This is a default description.
        type: parameters
  ListPopulationRule:
    properties:
      floodlightActivityId:
        description: This is a default description.
        type: parameters
      floodlightActivityName:
        description: This is a default description.
        type: parameters
      listPopulationClauses:
        description: This is a default description.
        type: parameters
  ListPopulationTerm:
    properties:
      contains:
        description: This is a default description.
        type: parameters
      negation:
        description: This is a default description.
        type: parameters
      operator:
        description: This is a default description.
        type: parameters
      remarketingListId:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
      variableFriendlyName:
        description: This is a default description.
        type: parameters
      variableName:
        description: This is a default description.
        type: parameters
  ListTargetingExpression:
    properties:
      expression:
        description: This is a default description.
        type: parameters
  LookbackConfiguration:
    properties:
      clickDuration:
        description: This is a default description.
        type: parameters
      postImpressionActivitiesDuration:
        description: This is a default description.
        type: parameters
  Metric:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  Metro:
    properties:
      countryCode:
        description: This is a default description.
        type: parameters
      countryDartId:
        description: This is a default description.
        type: parameters
      dartId:
        description: This is a default description.
        type: parameters
      dmaId:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      metroCode:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  MetrosListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      metros:
        description: This is a default description.
        type: parameters
  MobileCarrier:
    properties:
      countryCode:
        description: This is a default description.
        type: parameters
      countryDartId:
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
  MobileCarriersListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      mobileCarriers:
        description: This is a default description.
        type: parameters
  ObjectFilter:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      objectIds:
        description: This is a default description.
        type: parameters
      status:
        description: This is a default description.
        type: parameters
  OffsetPosition:
    properties:
      left:
        description: This is a default description.
        type: parameters
      top:
        description: This is a default description.
        type: parameters
  OmnitureSettings:
    properties:
      omnitureCostDataEnabled:
        description: This is a default description.
        type: parameters
      omnitureIntegrationEnabled:
        description: This is a default description.
        type: parameters
  OperatingSystem:
    properties:
      dartId:
        description: This is a default description.
        type: parameters
      desktop:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      mobile:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  OperatingSystemVersion:
    properties:
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      majorVersion:
        description: This is a default description.
        type: parameters
      minorVersion:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  OperatingSystemVersionsListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      operatingSystemVersions:
        description: This is a default description.
        type: parameters
  OperatingSystemsListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      operatingSystems:
        description: This is a default description.
        type: parameters
  OptimizationActivity:
    properties:
      floodlightActivityId:
        description: This is a default description.
        type: parameters
      weight:
        description: This is a default description.
        type: parameters
  Order:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      approverUserProfileIds:
        description: This is a default description.
        type: parameters
      buyerInvoiceId:
        description: This is a default description.
        type: parameters
      buyerOrganizationName:
        description: This is a default description.
        type: parameters
      comments:
        description: This is a default description.
        type: parameters
      contacts:
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
  OrderContact:
    properties:
      contactInfo:
        description: This is a default description.
        type: parameters
      contactName:
        description: This is a default description.
        type: parameters
      contactTitle:
        description: This is a default description.
        type: parameters
      contactType:
        description: This is a default description.
        type: parameters
      signatureUserProfileId:
        description: This is a default description.
        type: parameters
  OrderDocument:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      amendedOrderDocumentId:
        description: This is a default description.
        type: parameters
      approvedByUserProfileIds:
        description: This is a default description.
        type: parameters
      cancelled:
        description: This is a default description.
        type: parameters
      effectiveDate:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      lastSentRecipients:
        description: This is a default description.
        type: parameters
      lastSentTime:
        description: This is a default description.
        type: parameters
  OrderDocumentsListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
      orderDocuments:
        description: This is a default description.
        type: parameters
  OrdersListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
      orders:
        description: This is a default description.
        type: parameters
  PathToConversionReportCompatibleFields:
    properties:
      conversionDimensions:
        description: This is a default description.
        type: parameters
      customFloodlightVariables:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      metrics:
        description: This is a default description.
        type: parameters
      perInteractionDimensions:
        description: This is a default description.
        type: parameters
  Placement:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      archived:
        description: This is a default description.
        type: parameters
      campaignId:
        description: This is a default description.
        type: parameters
      comment:
        description: This is a default description.
        type: parameters
      compatibility:
        description: This is a default description.
        type: parameters
      contentCategoryId:
        description: This is a default description.
        type: parameters
      directorySiteId:
        description: This is a default description.
        type: parameters
      externalId:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
  PlacementAssignment:
    properties:
      active:
        description: This is a default description.
        type: parameters
      placementId:
        description: This is a default description.
        type: parameters
      sslRequired:
        description: This is a default description.
        type: parameters
  PlacementGroup:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      archived:
        description: This is a default description.
        type: parameters
      campaignId:
        description: This is a default description.
        type: parameters
      childPlacementIds:
        description: This is a default description.
        type: parameters
      comment:
        description: This is a default description.
        type: parameters
      contentCategoryId:
        description: This is a default description.
        type: parameters
      directorySiteId:
        description: This is a default description.
        type: parameters
      externalId:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
  PlacementGroupsListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
      placementGroups:
        description: This is a default description.
        type: parameters
  PlacementStrategiesListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
      placementStrategies:
        description: This is a default description.
        type: parameters
  PlacementStrategy:
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
      name:
        description: This is a default description.
        type: parameters
  PlacementTag:
    properties:
      placementId:
        description: This is a default description.
        type: parameters
      tagDatas:
        description: This is a default description.
        type: parameters
  PlacementsGenerateTagsResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      placementTags:
        description: This is a default description.
        type: parameters
  PlacementsListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
      placements:
        description: This is a default description.
        type: parameters
  PlatformType:
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
  PlatformTypesListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      platformTypes:
        description: This is a default description.
        type: parameters
  PopupWindowProperties:
    properties:
      positionType:
        description: This is a default description.
        type: parameters
      showAddressBar:
        description: This is a default description.
        type: parameters
      showMenuBar:
        description: This is a default description.
        type: parameters
      showScrollBar:
        description: This is a default description.
        type: parameters
      showStatusBar:
        description: This is a default description.
        type: parameters
      showToolBar:
        description: This is a default description.
        type: parameters
      title:
        description: This is a default description.
        type: parameters
  PostalCode:
    properties:
      code:
        description: This is a default description.
        type: parameters
      countryCode:
        description: This is a default description.
        type: parameters
      countryDartId:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  PostalCodesListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      postalCodes:
        description: This is a default description.
        type: parameters
  Pricing:
    properties:
      capCostType:
        description: This is a default description.
        type: parameters
      endDate:
        description: This is a default description.
        type: parameters
      flights:
        description: This is a default description.
        type: parameters
      groupType:
        description: This is a default description.
        type: parameters
      pricingType:
        description: This is a default description.
        type: parameters
      startDate:
        description: This is a default description.
        type: parameters
  PricingSchedule:
    properties:
      capCostOption:
        description: This is a default description.
        type: parameters
      disregardOverdelivery:
        description: This is a default description.
        type: parameters
      endDate:
        description: This is a default description.
        type: parameters
      flighted:
        description: This is a default description.
        type: parameters
      floodlightActivityId:
        description: This is a default description.
        type: parameters
      pricingPeriods:
        description: This is a default description.
        type: parameters
      pricingType:
        description: This is a default description.
        type: parameters
      startDate:
        description: This is a default description.
        type: parameters
      testingStartDate:
        description: This is a default description.
        type: parameters
  PricingSchedulePricingPeriod:
    properties:
      endDate:
        description: This is a default description.
        type: parameters
      pricingComment:
        description: This is a default description.
        type: parameters
      rateOrCostNanos:
        description: This is a default description.
        type: parameters
      startDate:
        description: This is a default description.
        type: parameters
      units:
        description: This is a default description.
        type: parameters
  Project:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      audienceAgeGroup:
        description: This is a default description.
        type: parameters
      audienceGender:
        description: This is a default description.
        type: parameters
      budget:
        description: This is a default description.
        type: parameters
      clientBillingCode:
        description: This is a default description.
        type: parameters
      clientName:
        description: This is a default description.
        type: parameters
      endDate:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  ProjectsListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
      projects:
        description: This is a default description.
        type: parameters
  ReachReportCompatibleFields:
    properties:
      dimensionFilters:
        description: This is a default description.
        type: parameters
      dimensions:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      metrics:
        description: This is a default description.
        type: parameters
      pivotedActivityMetrics:
        description: This is a default description.
        type: parameters
      reachByFrequencyMetrics:
        description: This is a default description.
        type: parameters
  Recipient:
    properties:
      deliveryType:
        description: This is a default description.
        type: parameters
      email:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  Region:
    properties:
      countryCode:
        description: This is a default description.
        type: parameters
      countryDartId:
        description: This is a default description.
        type: parameters
      dartId:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      regionCode:
        description: This is a default description.
        type: parameters
  RegionsListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      regions:
        description: This is a default description.
        type: parameters
  RemarketingList:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      active:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      description:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      lifeSpan:
        description: This is a default description.
        type: parameters
      listSize:
        description: This is a default description.
        type: parameters
      listSource:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  RemarketingListShare:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      remarketingListId:
        description: This is a default description.
        type: parameters
      sharedAccountIds:
        description: This is a default description.
        type: parameters
      sharedAdvertiserIds:
        description: This is a default description.
        type: parameters
  RemarketingListsListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
      remarketingLists:
        description: This is a default description.
        type: parameters
  Report:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      criteria:
        description: This is a default description.
        type: parameters
      crossDimensionReachCriteria:
        description: This is a default description.
        type: parameters
      delivery:
        description: This is a default description.
        type: parameters
      etag:
        description: This is a default description.
        type: parameters
      fileName:
        description: This is a default description.
        type: parameters
      floodlightCriteria:
        description: This is a default description.
        type: parameters
      format:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  ReportCompatibleFields:
    properties:
      dimensionFilters:
        description: This is a default description.
        type: parameters
      dimensions:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      metrics:
        description: This is a default description.
        type: parameters
      pivotedActivityMetrics:
        description: This is a default description.
        type: parameters
  ReportList:
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
  ReportsConfiguration:
    properties:
      exposureToConversionEnabled:
        description: This is a default description.
        type: parameters
      reportGenerationTimeZoneId:
        description: This is a default description.
        type: parameters
  RichMediaExitOverride:
    properties:
      enabled:
        description: This is a default description.
        type: parameters
      exitId:
        description: This is a default description.
        type: parameters
  Rule:
    properties:
      assetId:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      targetingTemplateId:
        description: This is a default description.
        type: parameters
  Site:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      approved:
        description: This is a default description.
        type: parameters
      directorySiteId:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      keyName:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      siteContacts:
        description: This is a default description.
        type: parameters
      subaccountId:
        description: This is a default description.
        type: parameters
  SiteContact:
    properties:
      address:
        description: This is a default description.
        type: parameters
      contactType:
        description: This is a default description.
        type: parameters
      email:
        description: This is a default description.
        type: parameters
      firstName:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      lastName:
        description: This is a default description.
        type: parameters
      phone:
        description: This is a default description.
        type: parameters
      title:
        description: This is a default description.
        type: parameters
  SiteSettings:
    properties:
      activeViewOptOut:
        description: This is a default description.
        type: parameters
      disableBrandSafeAds:
        description: This is a default description.
        type: parameters
      disableNewCookie:
        description: This is a default description.
        type: parameters
      videoActiveViewOptOutTemplate:
        description: This is a default description.
        type: parameters
      vpaidAdapterChoiceTemplate:
        description: This is a default description.
        type: parameters
  SitesListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
      sites:
        description: This is a default description.
        type: parameters
  Size:
    properties:
      height:
        description: This is a default description.
        type: parameters
      iab:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      width:
        description: This is a default description.
        type: parameters
  SizesListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      sizes:
        description: This is a default description.
        type: parameters
  SkippableSetting:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      skippable:
        description: This is a default description.
        type: parameters
  SortedDimension:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      sortOrder:
        description: This is a default description.
        type: parameters
  Subaccount:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      availablePermissionIds:
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
  SubaccountsListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
      subaccounts:
        description: This is a default description.
        type: parameters
  TagData:
    properties:
      adId:
        description: This is a default description.
        type: parameters
      clickTag:
        description: This is a default description.
        type: parameters
      creativeId:
        description: This is a default description.
        type: parameters
      format:
        description: This is a default description.
        type: parameters
      impressionTag:
        description: This is a default description.
        type: parameters
  TagSetting:
    properties:
      additionalKeyValues:
        description: This is a default description.
        type: parameters
      includeClickThroughUrls:
        description: This is a default description.
        type: parameters
      includeClickTracking:
        description: This is a default description.
        type: parameters
      keywordOption:
        description: This is a default description.
        type: parameters
  TagSettings:
    properties:
      dynamicTagEnabled:
        description: This is a default description.
        type: parameters
      imageTagEnabled:
        description: This is a default description.
        type: parameters
  TargetWindow:
    properties:
      customHtml:
        description: This is a default description.
        type: parameters
      targetWindowOption:
        description: This is a default description.
        type: parameters
  TargetableRemarketingList:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      active:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      description:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      lifeSpan:
        description: This is a default description.
        type: parameters
      listSize:
        description: This is a default description.
        type: parameters
      listSource:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  TargetableRemarketingListsListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
      targetableRemarketingLists:
        description: This is a default description.
        type: parameters
  TargetingTemplate:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      advertiserId:
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
      subaccountId:
        description: This is a default description.
        type: parameters
  TargetingTemplatesListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
      targetingTemplates:
        description: This is a default description.
        type: parameters
  TechnologyTargeting:
    properties:
      browsers:
        description: This is a default description.
        type: parameters
      connectionTypes:
        description: This is a default description.
        type: parameters
      mobileCarriers:
        description: This is a default description.
        type: parameters
      operatingSystemVersions:
        description: This is a default description.
        type: parameters
      operatingSystems:
        description: This is a default description.
        type: parameters
      platformTypes:
        description: This is a default description.
        type: parameters
  ThirdPartyAuthenticationToken:
    properties:
      name:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  ThirdPartyTrackingUrl:
    properties:
      thirdPartyUrlType:
        description: This is a default description.
        type: parameters
      url:
        description: This is a default description.
        type: parameters
  TranscodeSetting:
    properties:
      enabledVideoFormats:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  UserDefinedVariableConfiguration:
    properties:
      dataType:
        description: This is a default description.
        type: parameters
      reportName:
        description: This is a default description.
        type: parameters
      variableType:
        description: This is a default description.
        type: parameters
  UserProfile:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      accountName:
        description: This is a default description.
        type: parameters
      etag:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      profileId:
        description: This is a default description.
        type: parameters
      subAccountId:
        description: This is a default description.
        type: parameters
      subAccountName:
        description: This is a default description.
        type: parameters
      userName:
        description: This is a default description.
        type: parameters
  UserProfileList:
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
  UserRole:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      defaultUserRole:
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
      parentUserRoleId:
        description: This is a default description.
        type: parameters
      permissions:
        description: This is a default description.
        type: parameters
      subaccountId:
        description: This is a default description.
        type: parameters
  UserRolePermission:
    properties:
      availability:
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
      permissionGroupId:
        description: This is a default description.
        type: parameters
  UserRolePermissionGroup:
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
  UserRolePermissionGroupsListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      userRolePermissionGroups:
        description: This is a default description.
        type: parameters
  UserRolePermissionsListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      userRolePermissions:
        description: This is a default description.
        type: parameters
  UserRolesListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
      userRoles:
        description: This is a default description.
        type: parameters
  VideoFormat:
    properties:
      fileType:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      targetBitRate:
        description: This is a default description.
        type: parameters
  VideoFormatsListResponse:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      videoFormats:
        description: This is a default description.
        type: parameters
  VideoOffset:
    properties:
      offsetPercentage:
        description: This is a default description.
        type: parameters
      offsetSeconds:
        description: This is a default description.
        type: parameters
  VideoSettings:
    properties:
      kind:
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