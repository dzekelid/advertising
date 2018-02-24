---
swagger: "2.0"
info:
  title: Ad Exchange Buyer
  description: Accesses your bidding-account information, submits creatives for validation,
    finds available direct deals, and retrieves performance reports.
  contact:
    name: Google
    url: https://google.com
  version: v1.4
host: www.googleapis.com
basePath: /adexchangebuyer/v1.4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /proposals/{proposalId}/setupcomplete:
    post:
      summary: Update Proposal To Complete
      description: Update the given proposal to indicate that setup has been completed
      operationId: adexchangebuyer.proposals.setupcomplete
      parameters:
      - in: path
        name: proposalId
        description: The proposal id for which the setup is complete
      responses:
        200:
          description: OK
      tags:
      - proposal
definitions:
  Account:
    properties:
      bidderLocation:
        description: This is a default description.
        type: parameters
      cookieMatchingNid:
        description: This is a default description.
        type: parameters
      cookieMatchingUrl:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      maximumActiveCreatives:
        description: This is a default description.
        type: parameters
      maximumTotalQps:
        description: This is a default description.
        type: parameters
      numberActiveCreatives:
        description: This is a default description.
        type: parameters
  AccountsList:
    properties:
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  AddOrderDealsRequest:
    properties:
      deals:
        description: This is a default description.
        type: parameters
      proposalRevisionNumber:
        description: This is a default description.
        type: parameters
      updateAction:
        description: This is a default description.
        type: parameters
  AddOrderDealsResponse:
    properties:
      deals:
        description: This is a default description.
        type: parameters
      proposalRevisionNumber:
        description: This is a default description.
        type: parameters
  AddOrderNotesRequest:
    properties:
      notes:
        description: This is a default description.
        type: parameters
  AddOrderNotesResponse:
    properties:
      notes:
        description: This is a default description.
        type: parameters
  BillingInfo:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      accountName:
        description: This is a default description.
        type: parameters
      billingId:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  BillingInfoList:
    properties:
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  Budget:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      billingId:
        description: This is a default description.
        type: parameters
      budgetAmount:
        description: This is a default description.
        type: parameters
      currencyCode:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  Buyer:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
  ContactInformation:
    properties:
      email:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
  CreateOrdersRequest:
    properties:
      proposals:
        description: This is a default description.
        type: parameters
      webPropertyCode:
        description: This is a default description.
        type: parameters
  CreateOrdersResponse:
    properties:
      proposals:
        description: This is a default description.
        type: parameters
  Creative:
    properties:
      HTMLSnippet:
        description: This is a default description.
        type: parameters
      accountId:
        description: This is a default description.
        type: parameters
      adChoicesDestinationUrl:
        description: This is a default description.
        type: parameters
      advertiserId:
        description: This is a default description.
        type: parameters
      advertiserName:
        description: This is a default description.
        type: parameters
      agencyId:
        description: This is a default description.
        type: parameters
      apiUploadTimestamp:
        description: This is a default description.
        type: parameters
      attribute:
        description: This is a default description.
        type: parameters
      buyerCreativeId:
        description: This is a default description.
        type: parameters
      clickThroughUrl:
        description: This is a default description.
        type: parameters
  CreativeDealIds:
    properties:
      dealStatuses:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  CreativesList:
    properties:
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
  DealServingMetadata:
    properties: []
  DealServingMetadataDealPauseStatus:
    properties:
      buyerPauseReason:
        description: This is a default description.
        type: parameters
      firstPausedBy:
        description: This is a default description.
        type: parameters
      hasBuyerPaused:
        description: This is a default description.
        type: parameters
      hasSellerPaused:
        description: This is a default description.
        type: parameters
      sellerPauseReason:
        description: This is a default description.
        type: parameters
  DealTerms:
    properties:
      brandingType:
        description: This is a default description.
        type: parameters
      crossListedExternalDealIdType:
        description: This is a default description.
        type: parameters
      description:
        description: This is a default description.
        type: parameters
      estimatedImpressionsPerDay:
        description: This is a default description.
        type: parameters
      sellerTimeZone:
        description: This is a default description.
        type: parameters
  DealTermsGuaranteedFixedPriceTerms:
    properties:
      fixedPrices:
        description: This is a default description.
        type: parameters
      guaranteedImpressions:
        description: This is a default description.
        type: parameters
      guaranteedLooks:
        description: This is a default description.
        type: parameters
      minimumDailyLooks:
        description: This is a default description.
        type: parameters
  DealTermsGuaranteedFixedPriceTermsBillingInfo:
    properties:
      currencyConversionTimeMs:
        description: This is a default description.
        type: parameters
      dfpLineItemId:
        description: This is a default description.
        type: parameters
      originalContractedQuantity:
        description: This is a default description.
        type: parameters
  DealTermsNonGuaranteedAuctionTerms:
    properties:
      autoOptimizePrivateAuction:
        description: This is a default description.
        type: parameters
      reservePricePerBuyers:
        description: This is a default description.
        type: parameters
  DealTermsNonGuaranteedFixedPriceTerms:
    properties:
      fixedPrices:
        description: This is a default description.
        type: parameters
  DealTermsRubiconNonGuaranteedTerms:
    properties: []
  DeleteOrderDealsRequest:
    properties:
      dealIds:
        description: This is a default description.
        type: parameters
      proposalRevisionNumber:
        description: This is a default description.
        type: parameters
      updateAction:
        description: This is a default description.
        type: parameters
  DeleteOrderDealsResponse:
    properties:
      deals:
        description: This is a default description.
        type: parameters
      proposalRevisionNumber:
        description: This is a default description.
        type: parameters
  DeliveryControl:
    properties:
      creativeBlockingLevel:
        description: This is a default description.
        type: parameters
      deliveryRateType:
        description: This is a default description.
        type: parameters
      frequencyCaps:
        description: This is a default description.
        type: parameters
  DeliveryControlFrequencyCap:
    properties:
      maxImpressions:
        description: This is a default description.
        type: parameters
      numTimeUnits:
        description: This is a default description.
        type: parameters
      timeUnitType:
        description: This is a default description.
        type: parameters
  Dimension:
    properties:
      dimensionType:
        description: This is a default description.
        type: parameters
      dimensionValues:
        description: This is a default description.
        type: parameters
  DimensionDimensionValue:
    properties:
      id:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      percentage:
        description: This is a default description.
        type: parameters
  EditAllOrderDealsRequest:
    properties:
      deals:
        description: This is a default description.
        type: parameters
      proposalRevisionNumber:
        description: This is a default description.
        type: parameters
      updateAction:
        description: This is a default description.
        type: parameters
  EditAllOrderDealsResponse:
    properties:
      deals:
        description: This is a default description.
        type: parameters
      orderRevisionNumber:
        description: This is a default description.
        type: parameters
  GetOffersResponse:
    properties:
      products:
        description: This is a default description.
        type: parameters
  GetOrderDealsResponse:
    properties:
      deals:
        description: This is a default description.
        type: parameters
  GetOrderNotesResponse:
    properties:
      notes:
        description: This is a default description.
        type: parameters
  GetOrdersResponse:
    properties:
      proposals:
        description: This is a default description.
        type: parameters
  GetPublisherProfilesByAccountIdResponse:
    properties:
      profiles:
        description: This is a default description.
        type: parameters
  MarketplaceDeal:
    properties:
      creationTimeMs:
        description: This is a default description.
        type: parameters
      creativePreApprovalPolicy:
        description: This is a default description.
        type: parameters
      creativeSafeFrameCompatibility:
        description: This is a default description.
        type: parameters
      dealId:
        description: This is a default description.
        type: parameters
      externalDealId:
        description: This is a default description.
        type: parameters
      flightEndTimeMs:
        description: This is a default description.
        type: parameters
      flightStartTimeMs:
        description: This is a default description.
        type: parameters
      inventoryDescription:
        description: This is a default description.
        type: parameters
      isRfpTemplate:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  MarketplaceDealParty:
    properties: []
  MarketplaceLabel:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      createTimeMs:
        description: This is a default description.
        type: parameters
      label:
        description: This is a default description.
        type: parameters
  MarketplaceNote:
    properties:
      creatorRole:
        description: This is a default description.
        type: parameters
      dealId:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      note:
        description: This is a default description.
        type: parameters
      noteId:
        description: This is a default description.
        type: parameters
      proposalId:
        description: This is a default description.
        type: parameters
      proposalRevisionNumber:
        description: This is a default description.
        type: parameters
      timestampMs:
        description: This is a default description.
        type: parameters
  PerformanceReport:
    properties:
      bidRate:
        description: This is a default description.
        type: parameters
      bidRequestRate:
        description: This is a default description.
        type: parameters
      calloutStatusRate:
        description: This is a default description.
        type: parameters
      cookieMatcherStatusRate:
        description: This is a default description.
        type: parameters
      creativeStatusRate:
        description: This is a default description.
        type: parameters
      filteredBidRate:
        description: This is a default description.
        type: parameters
      hostedMatchStatusRate:
        description: This is a default description.
        type: parameters
      inventoryMatchRate:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      latency50thPercentile:
        description: This is a default description.
        type: parameters
  PerformanceReportList:
    properties:
      kind:
        description: This is a default description.
        type: parameters
      performanceReport:
        description: This is a default description.
        type: parameters
  PretargetingConfig:
    properties:
      billingId:
        description: This is a default description.
        type: parameters
      configId:
        description: This is a default description.
        type: parameters
      configName:
        description: This is a default description.
        type: parameters
      creativeType:
        description: This is a default description.
        type: parameters
      dimensions:
        description: This is a default description.
        type: parameters
      excludedContentLabels:
        description: This is a default description.
        type: parameters
      excludedGeoCriteriaIds:
        description: This is a default description.
        type: parameters
      excludedPlacements:
        description: This is a default description.
        type: parameters
      excludedUserLists:
        description: This is a default description.
        type: parameters
      excludedVerticals:
        description: This is a default description.
        type: parameters
  PretargetingConfigList:
    properties:
      items:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
  Price:
    properties:
      amountMicros:
        description: This is a default description.
        type: parameters
      currencyCode:
        description: This is a default description.
        type: parameters
      expectedCpmMicros:
        description: This is a default description.
        type: parameters
      pricingType:
        description: This is a default description.
        type: parameters
  PricePerBuyer:
    properties:
      auctionTier:
        description: This is a default description.
        type: parameters
  PrivateData:
    properties:
      referenceId:
        description: This is a default description.
        type: parameters
      referencePayload:
        description: This is a default description.
        type: parameters
  Product:
    properties:
      creationTimeMs:
        description: This is a default description.
        type: parameters
      creatorContacts:
        description: This is a default description.
        type: parameters
      flightEndTimeMs:
        description: This is a default description.
        type: parameters
      flightStartTimeMs:
        description: This is a default description.
        type: parameters
      hasCreatorSignedOff:
        description: This is a default description.
        type: parameters
      inventorySource:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      labels:
        description: This is a default description.
        type: parameters
      lastUpdateTimeMs:
        description: This is a default description.
        type: parameters
      legacyOfferId:
        description: This is a default description.
        type: parameters
  Proposal:
    properties:
      buyerContacts:
        description: This is a default description.
        type: parameters
      dbmAdvertiserIds:
        description: This is a default description.
        type: parameters
      hasBuyerSignedOff:
        description: This is a default description.
        type: parameters
      hasSellerSignedOff:
        description: This is a default description.
        type: parameters
      inventorySource:
        description: This is a default description.
        type: parameters
      isRenegotiating:
        description: This is a default description.
        type: parameters
      isSetupComplete:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      labels:
        description: This is a default description.
        type: parameters
      lastUpdaterOrCommentorRole:
        description: This is a default description.
        type: parameters
  PublisherProfileApiProto:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      audience:
        description: This is a default description.
        type: parameters
      buyerPitchStatement:
        description: This is a default description.
        type: parameters
      directContact:
        description: This is a default description.
        type: parameters
      exchange:
        description: This is a default description.
        type: parameters
      googlePlusLink:
        description: This is a default description.
        type: parameters
      isParent:
        description: This is a default description.
        type: parameters
      isPublished:
        description: This is a default description.
        type: parameters
      kind:
        description: This is a default description.
        type: parameters
      logoUrl:
        description: This is a default description.
        type: parameters
  PublisherProvidedForecast:
    properties:
      dimensions:
        description: This is a default description.
        type: parameters
      weeklyImpressions:
        description: This is a default description.
        type: parameters
      weeklyUniques:
        description: This is a default description.
        type: parameters
  Seller:
    properties:
      accountId:
        description: This is a default description.
        type: parameters
      subAccountId:
        description: This is a default description.
        type: parameters
  SharedTargeting:
    properties:
      exclusions:
        description: This is a default description.
        type: parameters
      inclusions:
        description: This is a default description.
        type: parameters
      key:
        description: This is a default description.
        type: parameters
  TargetingValue:
    properties:
      longValue:
        description: This is a default description.
        type: parameters
      stringValue:
        description: This is a default description.
        type: parameters
  TargetingValueCreativeSize:
    properties:
      companionSizes:
        description: This is a default description.
        type: parameters
      creativeSizeType:
        description: This is a default description.
        type: parameters
      skippableAdType:
        description: This is a default description.
        type: parameters
  TargetingValueDayPartTargeting:
    properties:
      dayParts:
        description: This is a default description.
        type: parameters
      timeZoneType:
        description: This is a default description.
        type: parameters
  TargetingValueDayPartTargetingDayPart:
    properties:
      dayOfWeek:
        description: This is a default description.
        type: parameters
      endHour:
        description: This is a default description.
        type: parameters
      endMinute:
        description: This is a default description.
        type: parameters
      startHour:
        description: This is a default description.
        type: parameters
      startMinute:
        description: This is a default description.
        type: parameters
  TargetingValueSize:
    properties:
      height:
        description: This is a default description.
        type: parameters
      width:
        description: This is a default description.
        type: parameters
  UpdatePrivateAuctionProposalRequest:
    properties:
      externalDealId:
        description: This is a default description.
        type: parameters
      proposalRevisionNumber:
        description: This is a default description.
        type: parameters
      updateAction:
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