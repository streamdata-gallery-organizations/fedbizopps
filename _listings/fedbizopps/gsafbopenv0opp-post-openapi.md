---
swagger: "2.0"
x-collection-name: FedBizOpps
x-complete: 0
info:
  title: FBOpen API Search Opportunities
  description: Individual opportunities can be modified if POST functionality is enabled
    in the API.
  version: 1.0.0
host: api.data.gov
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /gsa/fbopen/v0/opp:
    post:
      summary: Search Opportunities
      description: Individual opportunities can be modified if POST functionality
        is enabled in the API.
      operationId: postOpportunity
      x-api-path-slug: gsafbopenv0opp-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Business Opportunities
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