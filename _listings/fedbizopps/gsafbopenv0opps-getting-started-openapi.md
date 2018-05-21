---
swagger: "2.0"
x-collection-name: FedBizOpps
x-complete: 0
info:
  title: FBOpen API Post Oopportunity
  description: Search for opportunities matching the query string (q). Supports Lucene
    query syntax.
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
  /gsa/fbopen/v0/opps:
    getting started:
      summary: Post Oopportunity
      description: Search for opportunities matching the query string (q). Supports
        Lucene query syntax.
      operationId: postOpportunity
      x-api-path-slug: gsafbopenv0opps-getting-started
      parameters:
      - in: query
        name: api_key
        description: your api
        type: string
        format: string
      - in: query
        name: data_source
        description: get results only from a particular data source
        type: string
        format: string
      - in: query
        name: limit
        description: number of results to return per request
        type: string
        format: string
      - in: query
        name: p
        description: page (one-indexed) of results to return
        type: string
        format: string
      - in: query
        name: q
        description: the keyword(s) or phrase you want to search for
        type: string
        format: string
      - in: query
        name: show_closed
        description: include opportunities with deadlines that have already passed
          in the results
        type: boolean
        format: boolean
      - in: query
        name: show_noncompeted
        description: include sole-sourced or otherwise non-competed opportunities
          in the results
        type: string
        format: string
      - in: query
        name: start
        description: get the next [limit] results starting with this number (zero-indexed)
        type: string
        format: string
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