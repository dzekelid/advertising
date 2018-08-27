swagger: "2.0"
x-collection-name: AT&T Dev Program
x-complete: 1
info:
  title: AT&T Dev Program Merged API
  version: 1.0.0
host: api.att.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/1/ads:
    get:
      summary: Get Ads
      description: /rest/1/ads
      operationId: rest1ads
      x-api-path-slug: rest1ads-get
      responses:
        200:
          description: OK
      tags:
      - Rest
      - Ads