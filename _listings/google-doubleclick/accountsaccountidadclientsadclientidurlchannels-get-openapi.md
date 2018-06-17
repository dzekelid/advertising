---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API Get URL Channels
  version: 1.0.0
  description: List all URL channels in the specified ad client for this Ad Exchange
    account.
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
      description: Retrieves the authenticated user's list of accounts.
      operationId: adexchangebuyer.accounts.list
      x-api-path-slug: accounts-get
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
  /accounts/{id}:
    get:
      summary: Get Account
      description: Gets one account by ID.
      operationId: adexchangebuyer.accounts.get
      x-api-path-slug: accountsid-get
      parameters:
      - in: path
        name: id
        description: The account id
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
    patch:
      summary: Update Account
      description: Updates an existing account. This method supports patch semantics.
      operationId: adexchangebuyer.accounts.patch
      x-api-path-slug: accountsid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: confirmUnsafeAccountChange
        description: Confirmation for erasing bidder and cookie matching urls
      - in: path
        name: id
        description: The account id
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
    put:
      summary: Update Account
      description: Updates an existing account.
      operationId: adexchangebuyer.accounts.update
      x-api-path-slug: accountsid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: confirmUnsafeAccountChange
        description: Confirmation for erasing bidder and cookie matching urls
      - in: path
        name: id
        description: The account id
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
  /billinginfo:
    get:
      summary: Get Billing Info
      description: Retrieves a list of billing information for all accounts of the
        authenticated user.
      operationId: adexchangebuyer.billingInfo.list
      x-api-path-slug: billinginfo-get
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Billing
  /billinginfo/{accountId}:
    get:
      summary: Get Billing Info
      description: Returns the billing information for one account specified by account
        ID.
      operationId: adexchangebuyer.billingInfo.get
      x-api-path-slug: billinginfoaccountid-get
      parameters:
      - in: path
        name: accountId
        description: The account id
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Billing
  /billinginfo/{accountId}/{billingId}:
    get:
      summary: Get Budget Info
      description: Returns the budget information for the adgroup specified by the
        accountId and billingId.
      operationId: adexchangebuyer.budget.get
      x-api-path-slug: billinginfoaccountidbillingid-get
      parameters:
      - in: path
        name: accountId
        description: The account id to get the budget information for
      - in: path
        name: billingId
        description: The billing id to get the budget information for
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Budget
    patch:
      summary: Get Budget Amount
      description: Updates the budget amount for the budget of the adgroup specified
        by the accountId and billingId, with the budget amount in the request. This
        method supports patch semantics.
      operationId: adexchangebuyer.budget.patch
      x-api-path-slug: billinginfoaccountidbillingid-patch
      parameters:
      - in: path
        name: accountId
        description: The account id associated with the budget being updated
      - in: path
        name: billingId
        description: The billing id associated with the budget being updated
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Budget
    put:
      summary: Update Budget Amount
      description: Updates the budget amount for the budget of the adgroup specified
        by the accountId and billingId, with the budget amount in the request.
      operationId: adexchangebuyer.budget.update
      x-api-path-slug: billinginfoaccountidbillingid-put
      parameters:
      - in: path
        name: accountId
        description: The account id associated with the budget being updated
      - in: path
        name: billingId
        description: The billing id associated with the budget being updated
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Budget
  /creatives:
    get:
      summary: Get Creatives
      description: Retrieves a list of the authenticated user's active creatives.
        A creative will be available 30-40 minutes after submission.
      operationId: adexchangebuyer.creatives.list
      x-api-path-slug: creatives-get
      parameters:
      - in: query
        name: accountId
        description: When specified, only creatives for the given account ids are
          returned
      - in: query
        name: buyerCreativeId
        description: When specified, only creatives for the given buyer creative ids
          are returned
      - in: query
        name: dealsStatusFilter
        description: When specified, only creatives having the given deals status
          are returned
      - in: query
        name: maxResults
        description: Maximum number of entries returned on one result page
      - in: query
        name: openAuctionStatusFilter
        description: When specified, only creatives having the given open auction
          status are returned
      - in: query
        name: pageToken
        description: A continuation token, used to page through ad clients
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Creative
    post:
      summary: Submit Creative
      description: Submit a new creative.
      operationId: adexchangebuyer.creatives.insert
      x-api-path-slug: creatives-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Creative
  /creatives/{accountId}/{buyerCreativeId}:
    get:
      summary: Get Creative Status
      description: Gets the status for a single creative. A creative will be available
        30-40 minutes after submission.
      operationId: adexchangebuyer.creatives.get
      x-api-path-slug: creativesaccountidbuyercreativeid-get
      parameters:
      - in: path
        name: accountId
        description: The id for the account that will serve this creative
      - in: path
        name: buyerCreativeId
        description: The buyer-specific id for this creative
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Creative
  /creatives/{accountId}/{buyerCreativeId}/addDeal/{dealId}:
    post:
      summary: Create Deal
      description: Add a deal id association for the creative.
      operationId: adexchangebuyer.creatives.addDeal
      x-api-path-slug: creativesaccountidbuyercreativeidadddealdealid-post
      parameters:
      - in: path
        name: accountId
        description: The id for the account that will serve this creative
      - in: path
        name: buyerCreativeId
        description: The buyer-specific id for this creative
      - in: path
        name: dealId
        description: The id of the deal id to associate with this creative
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Deal
  /creatives/{accountId}/{buyerCreativeId}/listDeals:
    get:
      summary: List Deals
      description: Lists the external deal ids associated with the creative.
      operationId: adexchangebuyer.creatives.listDeals
      x-api-path-slug: creativesaccountidbuyercreativeidlistdeals-get
      parameters:
      - in: path
        name: accountId
        description: The id for the account that will serve this creative
      - in: path
        name: buyerCreativeId
        description: The buyer-specific id for this creative
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Deal
  /creatives/{accountId}/{buyerCreativeId}/removeDeal/{dealId}:
    post:
      summary: Remove Deal
      description: Remove a deal id associated with the creative.
      operationId: adexchangebuyer.creatives.removeDeal
      x-api-path-slug: creativesaccountidbuyercreativeidremovedealdealid-post
      parameters:
      - in: path
        name: accountId
        description: The id for the account that will serve this creative
      - in: path
        name: buyerCreativeId
        description: The buyer-specific id for this creative
      - in: path
        name: dealId
        description: The id of the deal id to disassociate with this creative
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Deal
  /performancereport:
    get:
      summary: Get Performance Report
      description: Retrieves the authenticated user's list of performance metrics.
      operationId: adexchangebuyer.performanceReport.list
      x-api-path-slug: performancereport-get
      parameters:
      - in: query
        name: accountId
        description: The account id to get the reports
      - in: query
        name: endDateTime
        description: The end time of the report in ISO 8601 timestamp format using
          UTC
      - in: query
        name: maxResults
        description: Maximum number of entries returned on one result page
      - in: query
        name: pageToken
        description: A continuation token, used to page through performance reports
      - in: query
        name: startDateTime
        description: The start time of the report in ISO 8601 timestamp format using
          UTC
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Performance Report
  /pretargetingconfigs/{accountId}:
    get:
      summary: Get Pretargeting Configs
      description: Retrieves a list of the authenticated user's pretargeting configurations.
      operationId: adexchangebuyer.pretargetingConfig.list
      x-api-path-slug: pretargetingconfigsaccountid-get
      parameters:
      - in: path
        name: accountId
        description: The account id to get the pretargeting configs for
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Pretargeting Config
    post:
      summary: Update Pretargeting Config
      description: Inserts a new pretargeting configuration.
      operationId: adexchangebuyer.pretargetingConfig.insert
      x-api-path-slug: pretargetingconfigsaccountid-post
      parameters:
      - in: path
        name: accountId
        description: The account id to insert the pretargeting config for
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Pretargeting Config
  /pretargetingconfigs/{accountId}/{configId}:
    delete:
      summary: Delete Pretargeting Config
      description: Deletes an existing pretargeting config.
      operationId: adexchangebuyer.pretargetingConfig.delete
      x-api-path-slug: pretargetingconfigsaccountidconfigid-delete
      parameters:
      - in: path
        name: accountId
        description: The account id to delete the pretargeting config for
      - in: path
        name: configId
        description: The specific id of the configuration to delete
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Pretargeting Config
    get:
      summary: Get Pretargeting Config
      description: Gets a specific pretargeting configuration
      operationId: adexchangebuyer.pretargetingConfig.get
      x-api-path-slug: pretargetingconfigsaccountidconfigid-get
      parameters:
      - in: path
        name: accountId
        description: The account id to get the pretargeting config for
      - in: path
        name: configId
        description: The specific id of the configuration to retrieve
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Pretargeting Config
    patch:
      summary: Update Pretargeting Config
      description: Updates an existing pretargeting config. This method supports patch
        semantics.
      operationId: adexchangebuyer.pretargetingConfig.patch
      x-api-path-slug: pretargetingconfigsaccountidconfigid-patch
      parameters:
      - in: path
        name: accountId
        description: The account id to update the pretargeting config for
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: configId
        description: The specific id of the configuration to update
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Pretargeting Config
    put:
      summary: Update Pretargeting Config
      description: Updates an existing pretargeting config.
      operationId: adexchangebuyer.pretargetingConfig.update
      x-api-path-slug: pretargetingconfigsaccountidconfigid-put
      parameters:
      - in: path
        name: accountId
        description: The account id to update the pretargeting config for
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: configId
        description: The specific id of the configuration to update
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Pretargeting Config
  /privateauction/{privateAuctionId}/updateproposal:
    post:
      summary: Update Proposal
      description: Update a given private auction proposal
      operationId: adexchangebuyer.marketplaceprivateauction.updateproposal
      x-api-path-slug: privateauctionprivateauctionidupdateproposal-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: privateAuctionId
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Proposal
  /products/search:
    get:
      summary: Search
      description: Gets the requested product.
      operationId: adexchangebuyer.products.search
      x-api-path-slug: productssearch-get
      parameters:
      - in: query
        name: pqlQuery
        description: The pql query used to query for products
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Search
  /products/{productId}:
    get:
      summary: Get Product
      description: Gets the requested product by id.
      operationId: adexchangebuyer.products.get
      x-api-path-slug: productsproductid-get
      parameters:
      - in: path
        name: productId
        description: The id for the product to get the head revision for
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Product
  /proposals/insert:
    post:
      summary: Insert Proposal
      description: Create the given list of proposals
      operationId: adexchangebuyer.proposals.insert
      x-api-path-slug: proposalsinsert-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Proposal
  /proposals/search:
    get:
      summary: Search Proposal
      description: Search for proposals using pql query
      operationId: adexchangebuyer.proposals.search
      x-api-path-slug: proposalssearch-get
      parameters:
      - in: query
        name: pqlQuery
        description: Query string to retrieve specific proposals
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Proposal
  /proposals/{proposalId}:
    get:
      summary: Get Proposal
      description: Get a proposal given its id
      operationId: adexchangebuyer.proposals.get
      x-api-path-slug: proposalsproposalid-get
      parameters:
      - in: path
        name: proposalId
        description: Id of the proposal to retrieve
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Proposal
  /proposals/{proposalId}/deals:
    get:
      summary: Get Proposal Deals
      description: List all the deals for a given proposal
      operationId: adexchangebuyer.marketplacedeals.list
      x-api-path-slug: proposalsproposaliddeals-get
      parameters:
      - in: query
        name: pqlQuery
        description: Query string to retrieve specific deals
      - in: path
        name: proposalId
        description: The proposalId to get deals for
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Deal
  /proposals/{proposalId}/deals/delete:
    post:
      summary: Delete Proposal Deal
      description: Delete the specified deals from the proposal
      operationId: adexchangebuyer.marketplacedeals.delete
      x-api-path-slug: proposalsproposaliddealsdelete-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: proposalId
        description: The proposalId to delete deals from
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Deal
  /proposals/{proposalId}/deals/insert:
    post:
      summary: Insert Proposal Deal
      description: Add new deals for the specified proposal
      operationId: adexchangebuyer.marketplacedeals.insert
      x-api-path-slug: proposalsproposaliddealsinsert-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: proposalId
        description: proposalId for which deals need to be added
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Deal
  /proposals/{proposalId}/deals/update:
    post:
      summary: Update Proposal Deal
      description: Replaces all the deals in the proposal with the passed in deals
      operationId: adexchangebuyer.marketplacedeals.update
      x-api-path-slug: proposalsproposaliddealsupdate-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: proposalId
        description: The proposalId to edit deals on
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Deal
  /proposals/{proposalId}/notes:
    get:
      summary: Get Proposal Notes
      description: Get all the notes associated with a proposal
      operationId: adexchangebuyer.marketplacenotes.list
      x-api-path-slug: proposalsproposalidnotes-get
      parameters:
      - in: query
        name: pqlQuery
        description: Query string to retrieve specific notes
      - in: path
        name: proposalId
        description: The proposalId to get notes for
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Note
  /proposals/{proposalId}/notes/insert:
    post:
      summary: Insert Proposal Notes
      description: Add notes to the proposal
      operationId: adexchangebuyer.marketplacenotes.insert
      x-api-path-slug: proposalsproposalidnotesinsert-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: proposalId
        description: The proposalId to add notes for
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Note
  /proposals/{proposalId}/setupcomplete:
    post:
      summary: Update Proposal To Complete
      description: Update the given proposal to indicate that setup has been completed.
      operationId: adexchangebuyer.proposals.setupcomplete
      x-api-path-slug: proposalsproposalidsetupcomplete-post
      parameters:
      - in: path
        name: proposalId
        description: The proposal id for which the setup is complete
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Proposal
  /proposals/{proposalId}/{revisionNumber}/{updateAction}:
    patch:
      summary: Update Proposal Revision Number
      description: Update the given proposal. This method supports patch semantics.
      operationId: adexchangebuyer.proposals.patch
      x-api-path-slug: proposalsproposalidrevisionnumberupdateaction-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: proposalId
        description: The proposal id to update
      - in: path
        name: revisionNumber
        description: The last known revision number to update
      - in: path
        name: updateAction
        description: The proposed action to take on the proposal
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Proposal
    put:
      summary: Update Proposal Revision Number
      description: Update the given proposal
      operationId: adexchangebuyer.proposals.update
      x-api-path-slug: proposalsproposalidrevisionnumberupdateaction-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: proposalId
        description: The proposal id to update
      - in: path
        name: revisionNumber
        description: The last known revision number to update
      - in: path
        name: updateAction
        description: The proposed action to take on the proposal
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Proposal
  /publisher/{accountId}/profiles:
    get:
      summary: Get Publish Profiles
      description: Gets the requested publisher profile(s) by publisher accountId.
      operationId: adexchangebuyer.pubprofiles.list
      x-api-path-slug: publisheraccountidprofiles-get
      parameters:
      - in: path
        name: accountId
        description: The accountId of the publisher to get profiles for
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Profile
  /accounts/{accountId}:
    get:
      summary: Get Account
      description: Get information about the selected Ad Exchange account.
      operationId: adexchangeseller.accounts.get
      x-api-path-slug: accountsaccountid-get
      parameters:
      - in: path
        name: accountId
        description: Account to get information about
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
  /accounts/{accountId}/adclients:
    get:
      summary: Get Ad Clients
      description: List all ad clients in this Ad Exchange account.
      operationId: adexchangeseller.accounts.adclients.list
      x-api-path-slug: accountsaccountidadclients-get
      parameters:
      - in: path
        name: accountId
        description: Account to which the ad client belongs
      - in: query
        name: maxResults
        description: The maximum number of ad clients to include in the response,
          used for paging
      - in: query
        name: pageToken
        description: A continuation token, used to page through ad clients
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Clients
  /accounts/{accountId}/adclients/{adClientId}/customchannels:
    get:
      summary: Get Custom Channels
      description: List all custom channels in the specified ad client for this Ad
        Exchange account.
      operationId: adexchangeseller.accounts.customchannels.list
      x-api-path-slug: accountsaccountidadclientsadclientidcustomchannels-get
      parameters:
      - in: path
        name: accountId
        description: Account to which the ad client belongs
      - in: path
        name: adClientId
        description: Ad client for which to list custom channels
      - in: query
        name: maxResults
        description: The maximum number of custom channels to include in the response,
          used for paging
      - in: query
        name: pageToken
        description: A continuation token, used to page through custom channels
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Channels
  /accounts/{accountId}/adclients/{adClientId}/customchannels/{customChannelId}:
    get:
      summary: Get Custom Channels
      description: Get the specified custom channel from the specified ad client.
      operationId: adexchangeseller.accounts.customchannels.get
      x-api-path-slug: accountsaccountidadclientsadclientidcustomchannelscustomchannelid-get
      parameters:
      - in: path
        name: accountId
        description: Account to which the ad client belongs
      - in: path
        name: adClientId
        description: Ad client which contains the custom channel
      - in: path
        name: customChannelId
        description: Custom channel to retrieve
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Channels
  /accounts/{accountId}/adclients/{adClientId}/urlchannels:
    get:
      summary: Get URL Channels
      description: List all URL channels in the specified ad client for this Ad Exchange
        account.
      operationId: adexchangeseller.accounts.urlchannels.list
      x-api-path-slug: accountsaccountidadclientsadclientidurlchannels-get
      parameters:
      - in: path
        name: accountId
        description: Account to which the ad client belongs
      - in: path
        name: adClientId
        description: Ad client for which to list URL channels
      - in: query
        name: maxResults
        description: The maximum number of URL channels to include in the response,
          used for paging
      - in: query
        name: pageToken
        description: A continuation token, used to page through URL channels
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Channels
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