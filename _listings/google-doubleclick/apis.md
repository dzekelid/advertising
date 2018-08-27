---
name: Google Doubleclick
x-slug: google-doubleclick
description: The Ad Exchange Buyer REST API allows your Real-Time Bidding application
  to access and update account information and to submit creatives. The API also allows
  an application (whether it does static bidding or real-time bidding) to discover
  direct deals that sellers make available.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Advertising
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/apis.md
specificationVersion: "0.14"
apis:
- name: Google Doubleclick Merged API - Get Accounts
  x-api-slug: accounts-get
  description: Retrieves the authenticated user's list of accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accounts-get-openapi.md
- name: Google Doubleclick Merged API - Get Account
  x-api-slug: accountsid-get
  description: Gets one account by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsid-get-openapi.md
- name: Google Doubleclick Merged API - Update Account
  x-api-slug: accountsid-patch
  description: Updates an existing account. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsid-patch-openapi.md
- name: Google Doubleclick Merged API - Update Account
  x-api-slug: accountsid-put
  description: Updates an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsid-put-openapi.md
- name: Google Doubleclick Merged API - Get Billing Info
  x-api-slug: billinginfo-get
  description: Retrieves a list of billing information for all accounts of the authenticated
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/billinginfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/billinginfo-get-openapi.md
- name: Google Doubleclick Merged API - Get Billing Info
  x-api-slug: billinginfoaccountid-get
  description: Returns the billing information for one account specified by account
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/billinginfoaccountid-get-openapi.md
- name: Google Doubleclick Merged API - Get Budget Info
  x-api-slug: billinginfoaccountidbillingid-get
  description: Returns the budget information for the adgroup specified by the accountId
    and billingId.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/billinginfoaccountidbillingid-get-openapi.md
- name: Google Doubleclick Merged API - Get Budget Amount
  x-api-slug: billinginfoaccountidbillingid-patch
  description: Updates the budget amount for the budget of the adgroup specified by
    the accountId and billingId, with the budget amount in the request. This method
    supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/billinginfoaccountidbillingid-patch-openapi.md
- name: Google Doubleclick Merged API - Update Budget Amount
  x-api-slug: billinginfoaccountidbillingid-put
  description: Updates the budget amount for the budget of the adgroup specified by
    the accountId and billingId, with the budget amount in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/billinginfoaccountidbillingid-put-openapi.md
- name: Google Doubleclick Merged API - Get Creatives
  x-api-slug: creatives-get
  description: Retrieves a list of the authenticated user's active creatives. A creative
    will be available 30-40 minutes after submission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/creatives-get-openapi.md
- name: Google Doubleclick Merged API - Submit Creative
  x-api-slug: creatives-post
  description: Submit a new creative.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/creatives-post-openapi.md
- name: Google Doubleclick Merged API - Get Creative Status
  x-api-slug: creativesaccountidbuyercreativeid-get
  description: Gets the status for a single creative. A creative will be available
    30-40 minutes after submission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/creativesaccountidbuyercreativeid-get-openapi.md
- name: Google Doubleclick Merged API - Create Deal
  x-api-slug: creativesaccountidbuyercreativeidadddealdealid-post
  description: Add a deal id association for the creative.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/creativesaccountidbuyercreativeidadddealdealid-post-openapi.md
- name: Google Doubleclick Merged API - List Deals
  x-api-slug: creativesaccountidbuyercreativeidlistdeals-get
  description: Lists the external deal ids associated with the creative.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/creativesaccountidbuyercreativeidlistdeals-get-openapi.md
- name: Google Doubleclick Merged API - Remove Deal
  x-api-slug: creativesaccountidbuyercreativeidremovedealdealid-post
  description: Remove a deal id associated with the creative.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/creativesaccountidbuyercreativeidremovedealdealid-post-openapi.md
- name: Google Doubleclick Merged API - Get Performance Report
  x-api-slug: performancereport-get
  description: Retrieves the authenticated user's list of performance metrics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/performancereport-get-openapi.md
- name: Google Doubleclick Merged API - Get Pretargeting Configs
  x-api-slug: pretargetingconfigsaccountid-get
  description: Retrieves a list of the authenticated user's pretargeting configurations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/pretargetingconfigsaccountid-get-openapi.md
- name: Google Doubleclick Merged API - Update Pretargeting Config
  x-api-slug: pretargetingconfigsaccountid-post
  description: Inserts a new pretargeting configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/pretargetingconfigsaccountid-post-openapi.md
- name: Google Doubleclick Merged API - Delete Pretargeting Config
  x-api-slug: pretargetingconfigsaccountidconfigid-delete
  description: Deletes an existing pretargeting config.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/pretargetingconfigsaccountidconfigid-delete-openapi.md
- name: Google Doubleclick Merged API - Get Pretargeting Config
  x-api-slug: pretargetingconfigsaccountidconfigid-get
  description: Gets a specific pretargeting configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/pretargetingconfigsaccountidconfigid-get-openapi.md
- name: Google Doubleclick Merged API - Update Pretargeting Config
  x-api-slug: pretargetingconfigsaccountidconfigid-patch
  description: Updates an existing pretargeting config. This method supports patch
    semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/pretargetingconfigsaccountidconfigid-patch-openapi.md
- name: Google Doubleclick Merged API - Update Pretargeting Config
  x-api-slug: pretargetingconfigsaccountidconfigid-put
  description: Updates an existing pretargeting config.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/pretargetingconfigsaccountidconfigid-put-openapi.md
- name: Google Doubleclick Merged API - Update Proposal
  x-api-slug: privateauctionprivateauctionidupdateproposal-post
  description: Update a given private auction proposal
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/privateauctionprivateauctionidupdateproposal-post-openapi.md
- name: Google Doubleclick Merged API - Search
  x-api-slug: productssearch-get
  description: Gets the requested product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/productssearch-get-openapi.md
- name: Google Doubleclick Merged API - Get Product
  x-api-slug: productsproductid-get
  description: Gets the requested product by id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/productsproductid-get-openapi.md
- name: Google Doubleclick Merged API - Insert Proposal
  x-api-slug: proposalsinsert-post
  description: Create the given list of proposals
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/proposalsinsert-post-openapi.md
- name: Google Doubleclick Merged API - Search Proposal
  x-api-slug: proposalssearch-get
  description: Search for proposals using pql query
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/proposalssearch-get-openapi.md
- name: Google Doubleclick Merged API - Get Proposal
  x-api-slug: proposalsproposalid-get
  description: Get a proposal given its id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/proposalsproposalid-get-openapi.md
- name: Google Doubleclick Merged API - Get Proposal Deals
  x-api-slug: proposalsproposaliddeals-get
  description: List all the deals for a given proposal
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/proposalsproposaliddeals-get-openapi.md
- name: Google Doubleclick Merged API - Delete Proposal Deal
  x-api-slug: proposalsproposaliddealsdelete-post
  description: Delete the specified deals from the proposal
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/proposalsproposaliddealsdelete-post-openapi.md
- name: Google Doubleclick Merged API - Insert Proposal Deal
  x-api-slug: proposalsproposaliddealsinsert-post
  description: Add new deals for the specified proposal
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/proposalsproposaliddealsinsert-post-openapi.md
- name: Google Doubleclick Merged API - Update Proposal Deal
  x-api-slug: proposalsproposaliddealsupdate-post
  description: Replaces all the deals in the proposal with the passed in deals
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/proposalsproposaliddealsupdate-post-openapi.md
- name: Google Doubleclick Merged API - Get Proposal Notes
  x-api-slug: proposalsproposalidnotes-get
  description: Get all the notes associated with a proposal
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/proposalsproposalidnotes-get-openapi.md
- name: Google Doubleclick Merged API - Insert Proposal Notes
  x-api-slug: proposalsproposalidnotesinsert-post
  description: Add notes to the proposal
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/proposalsproposalidnotesinsert-post-openapi.md
- name: Google Doubleclick Merged API - Update Proposal To Complete
  x-api-slug: proposalsproposalidsetupcomplete-post
  description: Update the given proposal to indicate that setup has been completed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/proposalsproposalidsetupcomplete-post-openapi.md
- name: Google Doubleclick Merged API - Update Proposal Revision Number
  x-api-slug: proposalsproposalidrevisionnumberupdateaction-patch
  description: Update the given proposal. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/proposalsproposalidrevisionnumberupdateaction-patch-openapi.md
- name: Google Doubleclick Merged API - Update Proposal Revision Number
  x-api-slug: proposalsproposalidrevisionnumberupdateaction-put
  description: Update the given proposal
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/proposalsproposalidrevisionnumberupdateaction-put-openapi.md
- name: Google Doubleclick Merged API - Get Publish Profiles
  x-api-slug: publisheraccountidprofiles-get
  description: Gets the requested publisher profile(s) by publisher accountId.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/publisheraccountidprofiles-get-openapi.md
- name: Google Doubleclick Merged API - Get Account
  x-api-slug: accountsaccountid-get
  description: Get information about the selected Ad Exchange account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsaccountid-get-openapi.md
- name: Google Doubleclick Merged API - Get Ad Clients
  x-api-slug: accountsaccountidadclients-get
  description: List all ad clients in this Ad Exchange account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsaccountidadclients-get-openapi.md
- name: Google Doubleclick Merged API - Get Custom Channels
  x-api-slug: accountsaccountidadclientsadclientidcustomchannels-get
  description: List all custom channels in the specified ad client for this Ad Exchange
    account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsaccountidadclientsadclientidcustomchannels-get-openapi.md
- name: Google Doubleclick Merged API - Get Custom Channels
  x-api-slug: accountsaccountidadclientsadclientidcustomchannelscustomchannelid-get
  description: Get the specified custom channel from the specified ad client.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsaccountidadclientsadclientidcustomchannelscustomchannelid-get-openapi.md
- name: Google Doubleclick Merged API - Get URL Channels
  x-api-slug: accountsaccountidadclientsadclientidurlchannels-get
  description: List all URL channels in the specified ad client for this Ad Exchange
    account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsaccountidadclientsadclientidurlchannels-get-openapi.md
- name: Google Doubleclick Merged API - Get Alerts
  x-api-slug: accountsaccountidalerts-get
  description: List the alerts for this Ad Exchange account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsaccountidalerts-get-openapi.md
- name: Google Doubleclick Merged API - Get Dimensions
  x-api-slug: accountsaccountidmetadatadimensions-get
  description: List the metadata for the dimensions available to this AdExchange account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsaccountidmetadatadimensions-get-openapi.md
- name: Google Doubleclick Merged API - Get Metrics
  x-api-slug: accountsaccountidmetadatametrics-get
  description: List the metadata for the metrics available to this AdExchange account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsaccountidmetadatametrics-get-openapi.md
- name: Google Doubleclick Merged API - Get Preferred Deals
  x-api-slug: accountsaccountidpreferreddeals-get
  description: List the preferred deals for this Ad Exchange account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsaccountidpreferreddeals-get-openapi.md
- name: Google Doubleclick Merged API - Get Preferred Deal
  x-api-slug: accountsaccountidpreferreddealsdealid-get
  description: Get information about the selected Ad Exchange Preferred Deal.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsaccountidpreferreddealsdealid-get-openapi.md
- name: Google Doubleclick Merged API - Get Reports
  x-api-slug: accountsaccountidreports-get
  description: Generate an Ad Exchange report based on the report request sent in
    the query parameters. Returns the result as JSON; to retrieve output in CSV format
    specify "alt=csv" as a query parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsaccountidreports-get-openapi.md
- name: Google Doubleclick Merged API - Get Saved Reports
  x-api-slug: accountsaccountidreportssaved-get
  description: List all saved reports in this Ad Exchange account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsaccountidreportssaved-get-openapi.md
- name: Google Doubleclick Merged API - Get Saved Report
  x-api-slug: accountsaccountidreportssavedreportid-get
  description: Generate an Ad Exchange report based on the saved report ID sent in
    the query parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/accountsaccountidreportssavedreportid-get-openapi.md
- name: Google Doubleclick Merged API - Get Report
  x-api-slug: reportsreportidfilesfileid-get
  description: Retrieves a report file by its report ID and file ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/reportsreportidfilesfileid-get-openapi.md
- name: Google Doubleclick Merged API - Get User Profiles
  x-api-slug: userprofiles-get
  description: Retrieves list of user profiles for a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofiles-get-openapi.md
- name: Google Doubleclick Merged API - Get User Profile
  x-api-slug: userprofilesprofileid-get
  description: Gets one user profile by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileid-get-openapi.md
- name: Google Doubleclick Merged API - Get Account Active Ad Summary
  x-api-slug: userprofilesprofileidaccountactiveadsummariessummaryaccountid-get
  description: Gets the account's active ad summary by account ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccountactiveadsummariessummaryaccountid-get-openapi.md
- name: Google Doubleclick Merged API - Get Account Permission Groups
  x-api-slug: userprofilesprofileidaccountpermissiongroups-get
  description: Retrieves the list of account permission groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccountpermissiongroups-get-openapi.md
- name: Google Doubleclick Merged API - Get Account Permission Group
  x-api-slug: userprofilesprofileidaccountpermissiongroupsid-get
  description: Gets one account permission group by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccountpermissiongroupsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Account Permissions
  x-api-slug: userprofilesprofileidaccountpermissions-get
  description: Retrieves the list of account permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccountpermissions-get-openapi.md
- name: Google Doubleclick Merged API - Get Account Permissions
  x-api-slug: userprofilesprofileidaccountpermissionsid-get
  description: Gets one account permission by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccountpermissionsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Account Users
  x-api-slug: userprofilesprofileidaccountuserprofiles-get
  description: Retrieves a list of account user profiles, possibly filtered. This
    method supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccountuserprofiles-get-openapi.md
- name: Google Doubleclick Merged API - Update Account User
  x-api-slug: userprofilesprofileidaccountuserprofiles-patch
  description: Updates an existing account user profile. This method supports patch
    semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccountuserprofiles-patch-openapi.md
- name: Google Doubleclick Merged API - Add Account User
  x-api-slug: userprofilesprofileidaccountuserprofiles-post
  description: Inserts a new account user profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccountuserprofiles-post-openapi.md
- name: Google Doubleclick Merged API - Update Account User
  x-api-slug: userprofilesprofileidaccountuserprofiles-put
  description: Updates an existing account user profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccountuserprofiles-put-openapi.md
- name: Google Doubleclick Merged API - Get Account User
  x-api-slug: userprofilesprofileidaccountuserprofilesid-get
  description: Gets one account user profile by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccountuserprofilesid-get-openapi.md
- name: Google Doubleclick Merged API - Get Accounts
  x-api-slug: userprofilesprofileidaccounts-get
  description: Retrieves the list of accounts, possibly filtered. This method supports
    paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccounts-get-openapi.md
- name: Google Doubleclick Merged API - Update Account
  x-api-slug: userprofilesprofileidaccounts-patch
  description: Updates an existing account. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccounts-patch-openapi.md
- name: Google Doubleclick Merged API - Update Account
  x-api-slug: userprofilesprofileidaccounts-put
  description: Updates an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccounts-put-openapi.md
- name: Google Doubleclick Merged API - Get Account
  x-api-slug: userprofilesprofileidaccountsid-get
  description: Gets one account by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidaccountsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Ads
  x-api-slug: userprofilesprofileidads-get
  description: Retrieves a list of ads, possibly filtered. This method supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidads-get-openapi.md
- name: Google Doubleclick Merged API - Update Ad
  x-api-slug: userprofilesprofileidads-patch
  description: Updates an existing ad. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidads-patch-openapi.md
- name: Google Doubleclick Merged API - Create Ad
  x-api-slug: userprofilesprofileidads-post
  description: Inserts a new ad.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidads-post-openapi.md
- name: Google Doubleclick Merged API - Update Ad
  x-api-slug: userprofilesprofileidads-put
  description: Updates an existing ad.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidads-put-openapi.md
- name: Google Doubleclick Merged API - Get Ad
  x-api-slug: userprofilesprofileidadsid-get
  description: Gets one ad by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidadsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Advertiser Groups
  x-api-slug: userprofilesprofileidadvertisergroups-get
  description: Retrieves a list of advertiser groups, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidadvertisergroups-get-openapi.md
- name: Google Doubleclick Merged API - Update Advertiser Group
  x-api-slug: userprofilesprofileidadvertisergroups-patch
  description: Updates an existing advertiser group. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidadvertisergroups-patch-openapi.md
- name: Google Doubleclick Merged API - Create Advertiser Group
  x-api-slug: userprofilesprofileidadvertisergroups-post
  description: Inserts a new advertiser group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidadvertisergroups-post-openapi.md
- name: Google Doubleclick Merged API - Update Advertiser Group
  x-api-slug: userprofilesprofileidadvertisergroups-put
  description: Updates an existing advertiser group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidadvertisergroups-put-openapi.md
- name: Google Doubleclick Merged API - Update Advertiser Delete
  x-api-slug: userprofilesprofileidadvertisergroupsid-delete
  description: Deletes an existing advertiser group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidadvertisergroupsid-delete-openapi.md
- name: Google Doubleclick Merged API - Get Advertiser Group
  x-api-slug: userprofilesprofileidadvertisergroupsid-get
  description: Gets one advertiser group by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidadvertisergroupsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Advertisers
  x-api-slug: userprofilesprofileidadvertisers-get
  description: Retrieves a list of advertisers, possibly filtered. This method supports
    paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidadvertisers-get-openapi.md
- name: Google Doubleclick Merged API - Update Advertiser
  x-api-slug: userprofilesprofileidadvertisers-patch
  description: Updates an existing advertiser. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidadvertisers-patch-openapi.md
- name: Google Doubleclick Merged API - Create Advertiser
  x-api-slug: userprofilesprofileidadvertisers-post
  description: Inserts a new advertiser.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidadvertisers-post-openapi.md
- name: Google Doubleclick Merged API - Update Advertiser
  x-api-slug: userprofilesprofileidadvertisers-put
  description: Updates an existing advertiser.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidadvertisers-put-openapi.md
- name: Google Doubleclick Merged API - Get Advertiser
  x-api-slug: userprofilesprofileidadvertisersid-get
  description: Gets one advertiser by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidadvertisersid-get-openapi.md
- name: Google Doubleclick Merged API - Get Browsers
  x-api-slug: userprofilesprofileidbrowsers-get
  description: Retrieves a list of browsers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidbrowsers-get-openapi.md
- name: Google Doubleclick Merged API - Get Campaigns
  x-api-slug: userprofilesprofileidcampaigns-get
  description: Retrieves a list of campaigns, possibly filtered. This method supports
    paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcampaigns-get-openapi.md
- name: Google Doubleclick Merged API - Update Campaign
  x-api-slug: userprofilesprofileidcampaigns-patch
  description: Updates an existing campaign. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcampaigns-patch-openapi.md
- name: Google Doubleclick Merged API - Create Campaign
  x-api-slug: userprofilesprofileidcampaigns-post
  description: Inserts a new campaign.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcampaigns-post-openapi.md
- name: Google Doubleclick Merged API - Update Campaign
  x-api-slug: userprofilesprofileidcampaigns-put
  description: Updates an existing campaign.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcampaigns-put-openapi.md
- name: Google Doubleclick Merged API - Get Campaign Creatives
  x-api-slug: userprofilesprofileidcampaignscampaignidcampaigncreativeassociations-get
  description: Retrieves the list of creative IDs associated with the specified campaign.
    This method supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcampaignscampaignidcampaigncreativeassociations-get-openapi.md
- name: Google Doubleclick Merged API - Add Campaign Creative
  x-api-slug: userprofilesprofileidcampaignscampaignidcampaigncreativeassociations-post
  description: Associates a creative with the specified campaign. This method creates
    a default ad with dimensions matching the creative in the campaign if such a default
    ad does not exist already.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcampaignscampaignidcampaigncreativeassociations-post-openapi.md
- name: Google Doubleclick Merged API - Get Landing Pages
  x-api-slug: userprofilesprofileidcampaignscampaignidlandingpages-get
  description: Retrieves the list of landing pages for the specified campaign.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcampaignscampaignidlandingpages-get-openapi.md
- name: Google Doubleclick Merged API - Update Landing Page
  x-api-slug: userprofilesprofileidcampaignscampaignidlandingpages-patch
  description: Updates an existing campaign landing page. This method supports patch
    semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcampaignscampaignidlandingpages-patch-openapi.md
- name: Google Doubleclick Merged API - Add Landing Page
  x-api-slug: userprofilesprofileidcampaignscampaignidlandingpages-post
  description: Inserts a new landing page for the specified campaign.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcampaignscampaignidlandingpages-post-openapi.md
- name: Google Doubleclick Merged API - Update Landing Page
  x-api-slug: userprofilesprofileidcampaignscampaignidlandingpages-put
  description: Updates an existing campaign landing page.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcampaignscampaignidlandingpages-put-openapi.md
- name: Google Doubleclick Merged API - Delete Landing Page
  x-api-slug: userprofilesprofileidcampaignscampaignidlandingpagesid-delete
  description: Deletes an existing campaign landing page.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcampaignscampaignidlandingpagesid-delete-openapi.md
- name: Google Doubleclick Merged API - Get Landing Page
  x-api-slug: userprofilesprofileidcampaignscampaignidlandingpagesid-get
  description: Gets one campaign landing page by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcampaignscampaignidlandingpagesid-get-openapi.md
- name: Google Doubleclick Merged API - Get Campaign
  x-api-slug: userprofilesprofileidcampaignsid-get
  description: Gets one campaign by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcampaignsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Change Logs
  x-api-slug: userprofilesprofileidchangelogs-get
  description: Retrieves a list of change logs. This method supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidchangelogs-get-openapi.md
- name: Google Doubleclick Merged API - Get Change Log
  x-api-slug: userprofilesprofileidchangelogsid-get
  description: Gets one change log by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidchangelogsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Cities
  x-api-slug: userprofilesprofileidcities-get
  description: Retrieves a list of cities, possibly filtered.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcities-get-openapi.md
- name: Google Doubleclick Merged API - Get Connection Types
  x-api-slug: userprofilesprofileidconnectiontypes-get
  description: Retrieves a list of connection types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidconnectiontypes-get-openapi.md
- name: Google Doubleclick Merged API - Get Connection Type
  x-api-slug: userprofilesprofileidconnectiontypesid-get
  description: Gets one connection type by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidconnectiontypesid-get-openapi.md
- name: Google Doubleclick Merged API - Get Content Categories
  x-api-slug: userprofilesprofileidcontentcategories-get
  description: Retrieves a list of content categories, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcontentcategories-get-openapi.md
- name: Google Doubleclick Merged API - Get Content Category
  x-api-slug: userprofilesprofileidcontentcategories-patch
  description: Updates an existing content category. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcontentcategories-patch-openapi.md
- name: Google Doubleclick Merged API - Create Content Category
  x-api-slug: userprofilesprofileidcontentcategories-post
  description: Inserts a new content category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcontentcategories-post-openapi.md
- name: Google Doubleclick Merged API - Update Content Category
  x-api-slug: userprofilesprofileidcontentcategories-put
  description: Updates an existing content category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcontentcategories-put-openapi.md
- name: Google Doubleclick Merged API - Delete Content Category
  x-api-slug: userprofilesprofileidcontentcategoriesid-delete
  description: Deletes an existing content category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcontentcategoriesid-delete-openapi.md
- name: Google Doubleclick Merged API - Get Content Category
  x-api-slug: userprofilesprofileidcontentcategoriesid-get
  description: Gets one content category by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcontentcategoriesid-get-openapi.md
- name: Google Doubleclick Merged API - Insert Conversions
  x-api-slug: userprofilesprofileidconversionsbatchinsert-post
  description: Inserts conversions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidconversionsbatchinsert-post-openapi.md
- name: Google Doubleclick Merged API - Get Countries
  x-api-slug: userprofilesprofileidcountries-get
  description: Retrieves a list of countries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcountries-get-openapi.md
- name: Google Doubleclick Merged API - Get Country
  x-api-slug: userprofilesprofileidcountriesdartid-get
  description: Gets one country by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcountriesdartid-get-openapi.md
- name: Google Doubleclick Merged API - Insert Creative Asset
  x-api-slug: userprofilesprofileidcreativeassetsadvertiseridcreativeassets-post
  description: Inserts a new creative asset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativeassetsadvertiseridcreativeassets-post-openapi.md
- name: Google Doubleclick Merged API - Get Creative Fields
  x-api-slug: userprofilesprofileidcreativefields-get
  description: Retrieves a list of creative fields, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativefields-get-openapi.md
- name: Google Doubleclick Merged API - Update Creative Fields
  x-api-slug: userprofilesprofileidcreativefields-patch
  description: Updates an existing creative field. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativefields-patch-openapi.md
- name: Google Doubleclick Merged API - Create Creative Fields
  x-api-slug: userprofilesprofileidcreativefields-post
  description: Inserts a new creative field.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativefields-post-openapi.md
- name: Google Doubleclick Merged API - Update Creative Fields
  x-api-slug: userprofilesprofileidcreativefields-put
  description: Updates an existing creative field.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativefields-put-openapi.md
- name: Google Doubleclick Merged API - Get Creative Field Values
  x-api-slug: userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-get
  description: Retrieves a list of creative field values, possibly filtered. This
    method supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-get-openapi.md
- name: Google Doubleclick Merged API - Update Creative Field Value
  x-api-slug: userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-patch
  description: Updates an existing creative field value. This method supports patch
    semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-patch-openapi.md
- name: Google Doubleclick Merged API - Insert Creative Field Value
  x-api-slug: userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-post
  description: Inserts a new creative field value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-post-openapi.md
- name: Google Doubleclick Merged API - Update Creative Field Value
  x-api-slug: userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-put
  description: Updates an existing creative field value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-put-openapi.md
- name: Google Doubleclick Merged API - Delete Creative Field Value
  x-api-slug: userprofilesprofileidcreativefieldscreativefieldidcreativefieldvaluesid-delete
  description: Deletes an existing creative field value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldscreativefieldidcreativefieldvaluesid-delete-openapi.md
- name: Google Doubleclick Merged API - UpGetdate Creative Field Value
  x-api-slug: userprofilesprofileidcreativefieldscreativefieldidcreativefieldvaluesid-get
  description: Gets one creative field value by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldscreativefieldidcreativefieldvaluesid-get-openapi.md
- name: Google Doubleclick Merged API - Delete Creative Field
  x-api-slug: userprofilesprofileidcreativefieldsid-delete
  description: Deletes an existing creative field.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldsid-delete-openapi.md
- name: Google Doubleclick Merged API - Get Creative Field
  x-api-slug: userprofilesprofileidcreativefieldsid-get
  description: Gets one creative field by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Creative Groups
  x-api-slug: userprofilesprofileidcreativegroups-get
  description: Retrieves a list of creative groups, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativegroups-get-openapi.md
- name: Google Doubleclick Merged API - Update Creative Group
  x-api-slug: userprofilesprofileidcreativegroups-patch
  description: Updates an existing creative group. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativegroups-patch-openapi.md
- name: Google Doubleclick Merged API - Insert Creative Group
  x-api-slug: userprofilesprofileidcreativegroups-post
  description: Inserts a new creative group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativegroups-post-openapi.md
- name: Google Doubleclick Merged API - Update Creative Group
  x-api-slug: userprofilesprofileidcreativegroups-put
  description: Updates an existing creative group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativegroups-put-openapi.md
- name: Google Doubleclick Merged API - Get Creative Group
  x-api-slug: userprofilesprofileidcreativegroupsid-get
  description: Gets one creative group by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativegroupsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Creatives
  x-api-slug: userprofilesprofileidcreatives-get
  description: Retrieves a list of creatives, possibly filtered. This method supports
    paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreatives-get-openapi.md
- name: Google Doubleclick Merged API - Update Creative
  x-api-slug: userprofilesprofileidcreatives-patch
  description: Updates an existing creative. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreatives-patch-openapi.md
- name: Google Doubleclick Merged API - Insert Creative
  x-api-slug: userprofilesprofileidcreatives-post
  description: Inserts a new creative.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreatives-post-openapi.md
- name: Google Doubleclick Merged API - Update Creative
  x-api-slug: userprofilesprofileidcreatives-put
  description: Updates an existing creative.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreatives-put-openapi.md
- name: Google Doubleclick Merged API - Get Creative
  x-api-slug: userprofilesprofileidcreativesid-get
  description: Gets one creative by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidcreativesid-get-openapi.md
- name: Google Doubleclick Merged API - Get Report Dimension
  x-api-slug: userprofilesprofileiddimensionvaluesquery-post
  description: Retrieves list of report dimension values for a list of filters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiddimensionvaluesquery-post-openapi.md
- name: Google Doubleclick Merged API - Get Directory Site Contacts
  x-api-slug: userprofilesprofileiddirectorysitecontacts-get
  description: Retrieves a list of directory site contacts, possibly filtered. This
    method supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiddirectorysitecontacts-get-openapi.md
- name: Google Doubleclick Merged API - Get Directory Site Contact
  x-api-slug: userprofilesprofileiddirectorysitecontactsid-get
  description: Gets one directory site contact by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiddirectorysitecontactsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Directory Sites
  x-api-slug: userprofilesprofileiddirectorysites-get
  description: Retrieves a list of directory sites, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiddirectorysites-get-openapi.md
- name: Google Doubleclick Merged API - Insert Directory Site
  x-api-slug: userprofilesprofileiddirectorysites-post
  description: Inserts a new directory site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiddirectorysites-post-openapi.md
- name: Google Doubleclick Merged API - Get Directory Site
  x-api-slug: userprofilesprofileiddirectorysitesid-get
  description: Gets one directory site by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiddirectorysitesid-get-openapi.md
- name: Google Doubleclick Merged API - Get Dynamic Targeting Keys
  x-api-slug: userprofilesprofileiddynamictargetingkeys-get
  description: Retrieves a list of dynamic targeting keys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiddynamictargetingkeys-get-openapi.md
- name: Google Doubleclick Merged API - Insert Dynamic Targeting Key
  x-api-slug: userprofilesprofileiddynamictargetingkeys-post
  description: Inserts a new dynamic targeting key. Keys must be created at the advertiser
    level before being assigned to the advertiser's ads, creatives, or placements.
    There is a maximum of 1000 keys per advertiser, out of which a maximum of 20 keys
    can be assigned per ad, creative, or placement.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiddynamictargetingkeys-post-openapi.md
- name: Google Doubleclick Merged API - Delete Dynamic Targeting Key
  x-api-slug: userprofilesprofileiddynamictargetingkeysobjectid-delete
  description: Deletes an existing dynamic targeting key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiddynamictargetingkeysobjectid-delete-openapi.md
- name: Google Doubleclick Merged API - Get Event Tags
  x-api-slug: userprofilesprofileideventtags-get
  description: Retrieves a list of event tags, possibly filtered.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileideventtags-get-openapi.md
- name: Google Doubleclick Merged API - Update Event Tag
  x-api-slug: userprofilesprofileideventtags-patch
  description: Updates an existing event tag. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileideventtags-patch-openapi.md
- name: Google Doubleclick Merged API - Insert Event Tag
  x-api-slug: userprofilesprofileideventtags-post
  description: Inserts a new event tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileideventtags-post-openapi.md
- name: Google Doubleclick Merged API - Update Event Tag
  x-api-slug: userprofilesprofileideventtags-put
  description: Updates an existing event tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileideventtags-put-openapi.md
- name: Google Doubleclick Merged API - Delete Event Tag
  x-api-slug: userprofilesprofileideventtagsid-delete
  description: Deletes an existing event tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileideventtagsid-delete-openapi.md
- name: Google Doubleclick Merged API - Get Event Tag
  x-api-slug: userprofilesprofileideventtagsid-get
  description: Gets one event tag by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileideventtagsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Files
  x-api-slug: userprofilesprofileidfiles-get
  description: Lists files for a user profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfiles-get-openapi.md
- name: Google Doubleclick Merged API - Get Floodlight Activities
  x-api-slug: userprofilesprofileidfloodlightactivities-get
  description: Retrieves a list of floodlight activities, possibly filtered. This
    method supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightactivities-get-openapi.md
- name: Google Doubleclick Merged API - Update Floodlight Activity
  x-api-slug: userprofilesprofileidfloodlightactivities-patch
  description: Updates an existing floodlight activity. This method supports patch
    semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightactivities-patch-openapi.md
- name: Google Doubleclick Merged API - Insert Floodlight Activity
  x-api-slug: userprofilesprofileidfloodlightactivities-post
  description: Inserts a new floodlight activity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightactivities-post-openapi.md
- name: Google Doubleclick Merged API - Update Floodlight Activity
  x-api-slug: userprofilesprofileidfloodlightactivities-put
  description: Updates an existing floodlight activity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightactivities-put-openapi.md
- name: Google Doubleclick Merged API - Generate Tag for Floodlight Activity
  x-api-slug: userprofilesprofileidfloodlightactivitiesgeneratetag-post
  description: Generates a tag for a floodlight activity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightactivitiesgeneratetag-post-openapi.md
- name: Google Doubleclick Merged API - Delete Floodlight Activity
  x-api-slug: userprofilesprofileidfloodlightactivitiesid-delete
  description: Deletes an existing floodlight activity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightactivitiesid-delete-openapi.md
- name: Google Doubleclick Merged API - Get Floodlight Activity
  x-api-slug: userprofilesprofileidfloodlightactivitiesid-get
  description: Gets one floodlight activity by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightactivitiesid-get-openapi.md
- name: Google Doubleclick Merged API - Get Floodlight Activity Groups
  x-api-slug: userprofilesprofileidfloodlightactivitygroups-get
  description: Retrieves a list of floodlight activity groups, possibly filtered.
    This method supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightactivitygroups-get-openapi.md
- name: Google Doubleclick Merged API - Update Floodlight Activity Group
  x-api-slug: userprofilesprofileidfloodlightactivitygroups-patch
  description: Updates an existing floodlight activity group. This method supports
    patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightactivitygroups-patch-openapi.md
- name: Google Doubleclick Merged API - Create Floodlight Activity Group
  x-api-slug: userprofilesprofileidfloodlightactivitygroups-post
  description: Inserts a new floodlight activity group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightactivitygroups-post-openapi.md
- name: Google Doubleclick Merged API - Update Floodlight Activity Group
  x-api-slug: userprofilesprofileidfloodlightactivitygroups-put
  description: Updates an existing floodlight activity group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightactivitygroups-put-openapi.md
- name: Google Doubleclick Merged API - Get Floodlight Activity Group
  x-api-slug: userprofilesprofileidfloodlightactivitygroupsid-get
  description: Gets one floodlight activity group by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightactivitygroupsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Floodlight Configurations
  x-api-slug: userprofilesprofileidfloodlightconfigurations-get
  description: Retrieves a list of floodlight configurations, possibly filtered.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightconfigurations-get-openapi.md
- name: Google Doubleclick Merged API - Update Floodlight Configuration
  x-api-slug: userprofilesprofileidfloodlightconfigurations-patch
  description: Updates an existing floodlight configuration. This method supports
    patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightconfigurations-patch-openapi.md
- name: Google Doubleclick Merged API - Update Floodlight Configuration
  x-api-slug: userprofilesprofileidfloodlightconfigurations-put
  description: Updates an existing floodlight configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightconfigurations-put-openapi.md
- name: Google Doubleclick Merged API - Get Floodlight Configuration
  x-api-slug: userprofilesprofileidfloodlightconfigurationsid-get
  description: Gets one floodlight configuration by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidfloodlightconfigurationsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Languages
  x-api-slug: userprofilesprofileidlanguages-get
  description: Retrieves a list of languages.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidlanguages-get-openapi.md
- name: Google Doubleclick Merged API - Get Metros
  x-api-slug: userprofilesprofileidmetros-get
  description: Retrieves a list of metros.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidmetros-get-openapi.md
- name: Google Doubleclick Merged API - Get Mobile Carriers
  x-api-slug: userprofilesprofileidmobilecarriers-get
  description: Retrieves a list of mobile carriers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidmobilecarriers-get-openapi.md
- name: Google Doubleclick Merged API - Get Mobile Carrier
  x-api-slug: userprofilesprofileidmobilecarriersid-get
  description: Gets one mobile carrier by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidmobilecarriersid-get-openapi.md
- name: Google Doubleclick Merged API - Get Operating System Versions
  x-api-slug: userprofilesprofileidoperatingsystemversions-get
  description: Retrieves a list of operating system versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidoperatingsystemversions-get-openapi.md
- name: Google Doubleclick Merged API - Get Operating System Version
  x-api-slug: userprofilesprofileidoperatingsystemversionsid-get
  description: Gets one operating system version by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidoperatingsystemversionsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Operating Systems
  x-api-slug: userprofilesprofileidoperatingsystems-get
  description: Retrieves a list of operating systems.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidoperatingsystems-get-openapi.md
- name: Google Doubleclick Merged API - Get Operating System
  x-api-slug: userprofilesprofileidoperatingsystemsdartid-get
  description: Gets one operating system by DART ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidoperatingsystemsdartid-get-openapi.md
- name: Google Doubleclick Merged API - Get Placement Groups
  x-api-slug: userprofilesprofileidplacementgroups-get
  description: Retrieves a list of placement groups, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacementgroups-get-openapi.md
- name: Google Doubleclick Merged API - Update Placement Group
  x-api-slug: userprofilesprofileidplacementgroups-patch
  description: Updates an existing placement group. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacementgroups-patch-openapi.md
- name: Google Doubleclick Merged API - Insert Placement Group
  x-api-slug: userprofilesprofileidplacementgroups-post
  description: Inserts a new placement group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacementgroups-post-openapi.md
- name: Google Doubleclick Merged API - Update Placement Group
  x-api-slug: userprofilesprofileidplacementgroups-put
  description: Updates an existing placement group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacementgroups-put-openapi.md
- name: Google Doubleclick Merged API - Get Placement Group
  x-api-slug: userprofilesprofileidplacementgroupsid-get
  description: Gets one placement group by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacementgroupsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Placement Strategies
  x-api-slug: userprofilesprofileidplacementstrategies-get
  description: Retrieves a list of placement strategies, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacementstrategies-get-openapi.md
- name: Google Doubleclick Merged API - Update Placement Strategy
  x-api-slug: userprofilesprofileidplacementstrategies-patch
  description: Updates an existing placement strategy. This method supports patch
    semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacementstrategies-patch-openapi.md
- name: Google Doubleclick Merged API - Insert Placement Strategy
  x-api-slug: userprofilesprofileidplacementstrategies-post
  description: Inserts a new placement strategy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacementstrategies-post-openapi.md
- name: Google Doubleclick Merged API - Update Placement Strategy
  x-api-slug: userprofilesprofileidplacementstrategies-put
  description: Updates an existing placement strategy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacementstrategies-put-openapi.md
- name: Google Doubleclick Merged API - Delete Placement Strategy
  x-api-slug: userprofilesprofileidplacementstrategiesid-delete
  description: Deletes an existing placement strategy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacementstrategiesid-delete-openapi.md
- name: Google Doubleclick Merged API - Get Placement Strategy
  x-api-slug: userprofilesprofileidplacementstrategiesid-get
  description: Gets one placement strategy by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacementstrategiesid-get-openapi.md
- name: Google Doubleclick Merged API - Get Placements
  x-api-slug: userprofilesprofileidplacements-get
  description: Retrieves a list of placements, possibly filtered. This method supports
    paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacements-get-openapi.md
- name: Google Doubleclick Merged API - Update Placement
  x-api-slug: userprofilesprofileidplacements-patch
  description: Updates an existing placement. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacements-patch-openapi.md
- name: Google Doubleclick Merged API - Insert Placement
  x-api-slug: userprofilesprofileidplacements-post
  description: Inserts a new placement.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacements-post-openapi.md
- name: Google Doubleclick Merged API - Update Placement
  x-api-slug: userprofilesprofileidplacements-put
  description: Updates an existing placement.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacements-put-openapi.md
- name: Google Doubleclick Merged API - Generate Placement Tag
  x-api-slug: userprofilesprofileidplacementsgeneratetags-post
  description: Generates tags for a placement.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacementsgeneratetags-post-openapi.md
- name: Google Doubleclick Merged API - Get Placement
  x-api-slug: userprofilesprofileidplacementsid-get
  description: Gets one placement by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplacementsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Platform Types
  x-api-slug: userprofilesprofileidplatformtypes-get
  description: Retrieves a list of platform types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplatformtypes-get-openapi.md
- name: Google Doubleclick Merged API - Get Platform Type
  x-api-slug: userprofilesprofileidplatformtypesid-get
  description: Gets one platform type by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidplatformtypesid-get-openapi.md
- name: Google Doubleclick Merged API - Get Postal Codes
  x-api-slug: userprofilesprofileidpostalcodes-get
  description: Retrieves a list of postal codes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidpostalcodes-get-openapi.md
- name: Google Doubleclick Merged API - Get Postal Code
  x-api-slug: userprofilesprofileidpostalcodescode-get
  description: Gets one postal code by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidpostalcodescode-get-openapi.md
- name: Google Doubleclick Merged API - Get Projects
  x-api-slug: userprofilesprofileidprojects-get
  description: Retrieves a list of projects, possibly filtered. This method supports
    paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidprojects-get-openapi.md
- name: Google Doubleclick Merged API - Get Project
  x-api-slug: userprofilesprofileidprojectsid-get
  description: Gets one project by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidprojectsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Inventory Items
  x-api-slug: userprofilesprofileidprojectsprojectidinventoryitems-get
  description: Retrieves a list of inventory items, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidprojectsprojectidinventoryitems-get-openapi.md
- name: Google Doubleclick Merged API - Get Inventory Item
  x-api-slug: userprofilesprofileidprojectsprojectidinventoryitemsid-get
  description: Gets one inventory item by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidprojectsprojectidinventoryitemsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Order Documents
  x-api-slug: userprofilesprofileidprojectsprojectidorderdocuments-get
  description: Retrieves a list of order documents, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidprojectsprojectidorderdocuments-get-openapi.md
- name: Google Doubleclick Merged API - Get Order Document
  x-api-slug: userprofilesprofileidprojectsprojectidorderdocumentsid-get
  description: Gets one order document by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidprojectsprojectidorderdocumentsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Orders
  x-api-slug: userprofilesprofileidprojectsprojectidorders-get
  description: Retrieves a list of orders, possibly filtered. This method supports
    paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidprojectsprojectidorders-get-openapi.md
- name: Google Doubleclick Merged API - Get Order
  x-api-slug: userprofilesprofileidprojectsprojectidordersid-get
  description: Gets one order by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidprojectsprojectidordersid-get-openapi.md
- name: Google Doubleclick Merged API - Get Regions
  x-api-slug: userprofilesprofileidregions-get
  description: Retrieves a list of regions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidregions-get-openapi.md
- name: Google Doubleclick Merged API - Update Remarketing List Shares
  x-api-slug: userprofilesprofileidremarketinglistshares-patch
  description: Updates an existing remarketing list share. This method supports patch
    semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidremarketinglistshares-patch-openapi.md
- name: Google Doubleclick Merged API - Update Remarketing List Shares
  x-api-slug: userprofilesprofileidremarketinglistshares-put
  description: Updates an existing remarketing list share.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidremarketinglistshares-put-openapi.md
- name: Google Doubleclick Merged API - Get Remarketing List Shares
  x-api-slug: userprofilesprofileidremarketinglistsharesremarketinglistid-get
  description: Gets one remarketing list share by remarketing list ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidremarketinglistsharesremarketinglistid-get-openapi.md
- name: Google Doubleclick Merged API - Get Remarketing Lists
  x-api-slug: userprofilesprofileidremarketinglists-get
  description: Retrieves a list of remarketing lists, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidremarketinglists-get-openapi.md
- name: Google Doubleclick Merged API - Update Remarketing List
  x-api-slug: userprofilesprofileidremarketinglists-patch
  description: Updates an existing remarketing list. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidremarketinglists-patch-openapi.md
- name: Google Doubleclick Merged API - Insert Remarketing List
  x-api-slug: userprofilesprofileidremarketinglists-post
  description: Inserts a new remarketing list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidremarketinglists-post-openapi.md
- name: Google Doubleclick Merged API - Update Remarketing List
  x-api-slug: userprofilesprofileidremarketinglists-put
  description: Updates an existing remarketing list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidremarketinglists-put-openapi.md
- name: Google Doubleclick Merged API - Get Remarketing List
  x-api-slug: userprofilesprofileidremarketinglistsid-get
  description: Gets one remarketing list by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidremarketinglistsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Reports
  x-api-slug: userprofilesprofileidreports-get
  description: Retrieves list of reports.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidreports-get-openapi.md
- name: Google Doubleclick Merged API - Get Report
  x-api-slug: userprofilesprofileidreports-post
  description: Creates a report.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidreports-post-openapi.md
- name: Google Doubleclick Merged API - Return Compatible Fields
  x-api-slug: userprofilesprofileidreportscompatiblefieldsquery-post
  description: Returns the fields that are compatible to be selected in the respective
    sections of a report criteria, given the fields already selected in the input
    report and user permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidreportscompatiblefieldsquery-post-openapi.md
- name: Google Doubleclick Merged API - Delete Report
  x-api-slug: userprofilesprofileidreportsreportid-delete
  description: Deletes a report by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidreportsreportid-delete-openapi.md
- name: Google Doubleclick Merged API - Get Report
  x-api-slug: userprofilesprofileidreportsreportid-get
  description: Retrieves a report by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidreportsreportid-get-openapi.md
- name: Google Doubleclick Merged API - Update Report
  x-api-slug: userprofilesprofileidreportsreportid-patch
  description: Updates a report. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidreportsreportid-patch-openapi.md
- name: Google Doubleclick Merged API - Update Report
  x-api-slug: userprofilesprofileidreportsreportid-put
  description: Updates a report.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidreportsreportid-put-openapi.md
- name: Google Doubleclick Merged API - Get Report Files
  x-api-slug: userprofilesprofileidreportsreportidfiles-get
  description: Lists files for a report.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidreportsreportidfiles-get-openapi.md
- name: Google Doubleclick Merged API - Get Report File
  x-api-slug: userprofilesprofileidreportsreportidfilesfileid-get
  description: Retrieves a report file.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidreportsreportidfilesfileid-get-openapi.md
- name: Google Doubleclick Merged API - Run Report
  x-api-slug: userprofilesprofileidreportsreportidrun-post
  description: Runs a report.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidreportsreportidrun-post-openapi.md
- name: Google Doubleclick Merged API - Get Sites
  x-api-slug: userprofilesprofileidsites-get
  description: Retrieves a list of sites, possibly filtered. This method supports
    paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidsites-get-openapi.md
- name: Google Doubleclick Merged API - Update Site
  x-api-slug: userprofilesprofileidsites-patch
  description: Updates an existing site. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidsites-patch-openapi.md
- name: Google Doubleclick Merged API - Create Site
  x-api-slug: userprofilesprofileidsites-post
  description: Inserts a new site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidsites-post-openapi.md
- name: Google Doubleclick Merged API - Update Site
  x-api-slug: userprofilesprofileidsites-put
  description: Updates an existing site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidsites-put-openapi.md
- name: Google Doubleclick Merged API - Get Site
  x-api-slug: userprofilesprofileidsitesid-get
  description: Gets one site by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidsitesid-get-openapi.md
- name: Google Doubleclick Merged API - Get Sizes
  x-api-slug: userprofilesprofileidsizes-get
  description: Retrieves a list of sizes, possibly filtered.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidsizes-get-openapi.md
- name: Google Doubleclick Merged API - Insert Size
  x-api-slug: userprofilesprofileidsizes-post
  description: Inserts a new size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidsizes-post-openapi.md
- name: Google Doubleclick Merged API - Get Size
  x-api-slug: userprofilesprofileidsizesid-get
  description: Gets one size by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidsizesid-get-openapi.md
- name: Google Doubleclick Merged API - Get Subaccounts
  x-api-slug: userprofilesprofileidsubaccounts-get
  description: Gets a list of subaccounts, possibly filtered. This method supports
    paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidsubaccounts-get-openapi.md
- name: Google Doubleclick Merged API - Update Subaccount
  x-api-slug: userprofilesprofileidsubaccounts-patch
  description: Updates an existing subaccount. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidsubaccounts-patch-openapi.md
- name: Google Doubleclick Merged API - Insert Subaccount
  x-api-slug: userprofilesprofileidsubaccounts-post
  description: Inserts a new subaccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidsubaccounts-post-openapi.md
- name: Google Doubleclick Merged API - Update Subaccount
  x-api-slug: userprofilesprofileidsubaccounts-put
  description: Updates an existing subaccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidsubaccounts-put-openapi.md
- name: Google Doubleclick Merged API - Get Subaccount
  x-api-slug: userprofilesprofileidsubaccountsid-get
  description: Gets one subaccount by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidsubaccountsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Targetable Remarketing Lists
  x-api-slug: userprofilesprofileidtargetableremarketinglists-get
  description: Retrieves a list of targetable remarketing lists, possibly filtered.
    This method supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidtargetableremarketinglists-get-openapi.md
- name: Google Doubleclick Merged API - Get Targetable Remarketing List
  x-api-slug: userprofilesprofileidtargetableremarketinglistsid-get
  description: Gets one remarketing list by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidtargetableremarketinglistsid-get-openapi.md
- name: Google Doubleclick Merged API - Get Targeting Templates
  x-api-slug: userprofilesprofileidtargetingtemplates-get
  description: Retrieves a list of targeting templates, optionally filtered. This
    method supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidtargetingtemplates-get-openapi.md
- name: Google Doubleclick Merged API - Update Targeting Template
  x-api-slug: userprofilesprofileidtargetingtemplates-patch
  description: Updates an existing targeting template. This method supports patch
    semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidtargetingtemplates-patch-openapi.md
- name: Google Doubleclick Merged API - Create Targeting Template
  x-api-slug: userprofilesprofileidtargetingtemplates-post
  description: Inserts a new targeting template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidtargetingtemplates-post-openapi.md
- name: Google Doubleclick Merged API - Update Targeting Template
  x-api-slug: userprofilesprofileidtargetingtemplates-put
  description: Updates an existing targeting template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidtargetingtemplates-put-openapi.md
- name: Google Doubleclick Merged API - Get Targeting Template
  x-api-slug: userprofilesprofileidtargetingtemplatesid-get
  description: Gets one targeting template by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidtargetingtemplatesid-get-openapi.md
- name: Google Doubleclick Merged API - Get User Role Permission Groups
  x-api-slug: userprofilesprofileiduserrolepermissiongroups-get
  description: Gets a list of all supported user role permission groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiduserrolepermissiongroups-get-openapi.md
- name: Google Doubleclick Merged API - Get User Role Permission Group
  x-api-slug: userprofilesprofileiduserrolepermissiongroupsid-get
  description: Gets one user role permission group by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiduserrolepermissiongroupsid-get-openapi.md
- name: Google Doubleclick Merged API - Get User Role Permissions
  x-api-slug: userprofilesprofileiduserrolepermissions-get
  description: Gets a list of user role permissions, possibly filtered.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiduserrolepermissions-get-openapi.md
- name: Google Doubleclick Merged API - Get User Role Permission
  x-api-slug: userprofilesprofileiduserrolepermissionsid-get
  description: Gets one user role permission by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiduserrolepermissionsid-get-openapi.md
- name: Google Doubleclick Merged API - Get User Roles
  x-api-slug: userprofilesprofileiduserroles-get
  description: Retrieves a list of user roles, possibly filtered. This method supports
    paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiduserroles-get-openapi.md
- name: Google Doubleclick Merged API - Update User Role
  x-api-slug: userprofilesprofileiduserroles-patch
  description: Updates an existing user role. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiduserroles-patch-openapi.md
- name: Google Doubleclick Merged API - Insert User Role
  x-api-slug: userprofilesprofileiduserroles-post
  description: Inserts a new user role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiduserroles-post-openapi.md
- name: Google Doubleclick Merged API - Update User Role
  x-api-slug: userprofilesprofileiduserroles-put
  description: Updates an existing user role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiduserroles-put-openapi.md
- name: Google Doubleclick Merged API - Delete User Role
  x-api-slug: userprofilesprofileiduserrolesid-delete
  description: Deletes an existing user role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiduserrolesid-delete-openapi.md
- name: Google Doubleclick Merged API - Get User Role
  x-api-slug: userprofilesprofileiduserrolesid-get
  description: Gets one user role by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileiduserrolesid-get-openapi.md
- name: Google Doubleclick Merged API - Get Video Formats
  x-api-slug: userprofilesprofileidvideoformats-get
  description: Lists available video formats.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidvideoformats-get-openapi.md
- name: Google Doubleclick Merged API - Get Video
  x-api-slug: userprofilesprofileidvideoformatsid-get
  description: Gets one video format by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/userprofilesprofileidvideoformatsid-get-openapi.md
- name: Google Doubleclick Merged API - Download CSV
  x-api-slug: lineitemsdownloadlineitems-post
  description: Retrieves line items in CSV format.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/lineitemsdownloadlineitems-post-openapi.md
- name: Google Doubleclick Merged API - Upload CSV
  x-api-slug: lineitemsuploadlineitems-post
  description: Uploads line items in CSV format.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/lineitemsuploadlineitems-post-openapi.md
- name: Google Doubleclick Merged API - Get Stored Queries
  x-api-slug: queries-get
  description: Retrieves stored queries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/queries-get-openapi.md
- name: Google Doubleclick Merged API - Get Stored Reports
  x-api-slug: queriesqueryidreports-get
  description: Retrieves stored reports.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/queriesqueryidreports-get-openapi.md
- name: Google Doubleclick Merged API - Create Query
  x-api-slug: query-post
  description: Creates a query.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/query-post-openapi.md
- name: Google Doubleclick Merged API - Delete Stored Query
  x-api-slug: queryqueryid-delete
  description: Deletes a stored query as well as the associated stored reports.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/queryqueryid-delete-openapi.md
- name: Google Doubleclick Merged API - Get Stored Query
  x-api-slug: queryqueryid-get
  description: Retrieves a stored query.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/queryqueryid-get-openapi.md
- name: Google Doubleclick Merged API - Run Stored Query
  x-api-slug: queryqueryid-post
  description: Runs a stored query to generate a report.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/queryqueryid-post-openapi.md
- name: Google Doubleclick Merged API - Get Entities in SDF Format
  x-api-slug: sdfdownload-post
  description: Retrieves entities in SDF format.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/sdfdownload-post-openapi.md
- name: Google Doubleclick Merged API - Get Conversions
  x-api-slug: agencyagencyidadvertiseradvertiseridengineengineaccountidconversion-get
  description: Retrieves a list of conversions from a DoubleClick Search engine account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/agencyagencyidadvertiseradvertiseridengineengineaccountidconversion-get-openapi.md
- name: Google Doubleclick Merged API - Get Saved Columns
  x-api-slug: agencyagencyidadvertiseradvertiseridsavedcolumns-get
  description: Retrieve the list of saved columns for a specified advertiser.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/agencyagencyidadvertiseradvertiseridsavedcolumns-get-openapi.md
- name: Google Doubleclick Merged API - Update Conversions
  x-api-slug: conversion-patch
  description: Updates a batch of conversions in DoubleClick Search. This method supports
    patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/conversion-patch-openapi.md
- name: Google Doubleclick Merged API - Insert Conversion
  x-api-slug: conversion-post
  description: Inserts a batch of new conversions into DoubleClick Search.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/conversion-post-openapi.md
- name: Google Doubleclick Merged API - Update Conversions
  x-api-slug: conversion-put
  description: Updates a batch of conversions in DoubleClick Search.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/conversion-put-openapi.md
- name: Google Doubleclick Merged API - Update Availability
  x-api-slug: conversionupdateavailability-post
  description: Updates the availabilities of a batch of floodlight activities in DoubleClick
    Search.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/conversionupdateavailability-post-openapi.md
- name: Google Doubleclick Merged API - Insert Report
  x-api-slug: reports-post
  description: Inserts a report request into the reporting system.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/reports-post-openapi.md
- name: Google Doubleclick Merged API - Generate Report
  x-api-slug: reportsgenerate-post
  description: Generates and returns a report immediately.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/reportsgenerate-post-openapi.md
- name: Google Doubleclick Merged API - Get Report Status
  x-api-slug: reportsreportid-get
  description: Polls for the status of a report request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/reportsreportid-get-openapi.md
- name: Google Doubleclick Merged API - Download Report
  x-api-slug: reportsreportidfilesreportfragment-get
  description: Downloads a report file encoded in UTF-8.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Advertising, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/advertising/master/_listings/google-doubleclick/reportsreportidfilesreportfragment-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.dataflow.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.doubleclick.stack.network
- type: x-authentication
  url: https://developers.google.com/ad-exchange/buyer-rest/auth-guide
- type: x-blog
  url: http://googleadsdeveloper.blogspot.com/search/label/ad_exchange
- type: x-blog-rss
  url: http://googleadsdeveloper.blogspot.com/feeds/posts/default?alt=rss
- type: x-developer
  url: https://developers.google.com/ad-exchange/buyer-rest/
- type: x-forum
  url: https://groups.google.com/forum/#!forum/google-doubleclick-ad-exchange-buyer-api
- type: x-getting-started
  url: https://developers.google.com/ad-exchange/buyer-rest/start
- type: x-support
  url: https://developers.google.com/ad-exchange/buyer-rest/community/
- type: x-website
  url: https://www.doubleclickbygoogle.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---