---
swagger: "2.0"
x-collection-name: Disqus
x-complete: 1
info:
  title: Disqus
  description: welcome-to-the-disqus-web-api--the-api-enables-developers-to-communicate-with-disqus-data-from-within-their-own-applications-
  termsOfService: https://docs.disqus.com/kb/terms-and-policies/
  version: 1.0.0
host: disqus.com
basePath: api/3.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /forums/disableAds.json:
    post:
      summary: Forums DisableAds
      description: Forums DisableAds
      operationId: forums-disableads
      x-api-path-slug: forumsdisableads-json-post
      parameters:
      - in: query
        name: forum
        description: Looks up a forum by ID (aka short name) You must be a moderator
          on the selected forum
        type: string
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Forums
      - Advertising
---