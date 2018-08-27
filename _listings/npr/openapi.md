---
swagger: "2.0"
x-collection-name: NPR
x-complete: 1
info:
  title: NPR One API Reference
  description: npr-one-is-a-smart-application-that-brings-the-best-of-npr-and-member-station-programming-newscasts-podcasts-and-stories-together-to-create-a-new-experience-for-listening--it-provides-an-editorcurated-and-localized-mobile-listening-experience-based-on-the-content-the-listener-chooses-likes-shares-and-enjoys--the-api-provides-all-of-the-content-and-customization-in-a-simple-structured-way-that-is-easy-for-applicationdevelopers-to-implement-
  termsOfService: http://dev.npr.org/develop/terms-of-use
  contact:
    name: NPR One Enterprise Team
    url: http://dev.npr.org
    email: NPROneEnterprise@npr.org
  version: 1.0.0
host: api.npr.org
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /sponsorship/v2/ads:
    get:
      summary: Request DAAST sponsorship units
      description: |-
        **Not** for use by NPR One clients (for whom sponsorship is already integrated into the Listening Service), this endpoint is designed to be used by our other client applications to request sponsorship on behalf of a user. Sponsorship units are returned in the form of DAAST XML. It is worth noting that this endpoint attempts to always return XML, even in the case of exceptions.

        The default behavior of this endpoint is asynchronous; on an initial request, a call to our external sponsorship provider is placed on a queue, which is typically processed within 3 minutes. Once the sponsorship call is received and processed, the returned sponsorship units are placed in a cache on our server for the current user. Subsequent calls to this endpoint will return DAAST sponsorship units from this cache until tracking information is submitted, which removes the ad from the cache and will automatically request additional ads asynchronously if there are fewer than a certain number remaining in the cache.

        For development purposes, it's worth noting that there is currently no way to clear a user's cache without submitting some form of tracking.
      operationId: getAds
      x-api-path-slug: sponsorshipv2ads-get
      parameters:
      - in: query
        name: adCount
        description: How many sponsorship units to request in one call; if left unspecified,
          the default behavior is to return only 1
      - in: query
        name: forceResult
        description: Whether to force a synchronous call to our external sponsorship
          provider; the default behavior is asynchronous
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - News
      - Sponsorship
      - Advertising
    post:
      summary: Record tracking data for DAAST sponsorship units
      description: |-
        **Not** for use by NPR One clients (for whom sponsorship is already integrated into the Listening Service), this endpoint is designed to be used by our other client applications to submit tracking information for sponsorship units obtained from the `GET /sponsorship/v2/ads` endpoint.

        The tracking information should be submitted in the body of the request in the form of a JSON object following the Collection.Doc+JSON specification.
      operationId: receiveAdTracking
      x-api-path-slug: sponsorshipv2ads-post
      parameters:
      - in: body
        name: body
        description: A JSON object representing sponsorship tracking data to submit
          to our external provider
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - News
      - Sponsorship
      - Advertising
---