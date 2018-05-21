---
name: FedBizOpps
x-slug: fedbizopps
description: This is the API documentation for the FBOpen API, a search API of opportunities
  to work with the U.S. government.You can learn more about FBOpen and its data by
  returning to the main documentation page.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/FedBizOppsLogo.jpg
x-kinRank: "9"
x-alexaRank: ""
tags: FedBizOpps
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fedbizopps/master/_listings/fedbizopps/apis.md
specificationVersion: "0.14"
apis:
- name: FBOpen API Search Opportunities
  x-api-slug: fbopen-api
  description: Individual opportunities can be modified if POST functionality is enabled
    in the API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/FedBizOppsLogo.jpg
  humanURL: https://18f.github.io/fbopen-docs/apidocs#-all-opportunities
  baseURL: https://api.data.gov////gsa/fbopen/v0/opp
  tags: Business Opportunities
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fedbizopps/master/_listings/fedbizopps/gsafbopenv0opp-post-openapi.md
- name: FBOpen API Post Oopportunity
  x-api-slug: fbopen-api
  description: Search for opportunities matching the query string (q). Supports Lucene
    query syntax.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/FedBizOppsLogo.jpg
  humanURL: https://18f.github.io/fbopen-docs/apidocs#-all-opportunities
  baseURL: https://api.data.gov////gsa/fbopen/v0/opps
  tags: Business Opportunities
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fedbizopps/master/_listings/fedbizopps/gsafbopenv0opps-getting-started-openapi.md
- name: FBOpen API
  x-api-slug: fbopen-api
  description: This is the API documentation for the FBOpen API, a search API of opportunities
    to work with the U.S. government.You can learn more about FBOpen and its data
    by returning to the main documentation page.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/FedBizOppsLogo.jpg
  humanURL: https://18f.github.io/fbopen-docs/apidocs#-all-opportunities
  baseURL: https://api.data.gov//
  tags: FedBizOpps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fedbizopps/master/_listings/fedbizopps/openapi.md
x-common:
- type: x-issues
  url: https://github.com/18f/fbopen/issues/new
- type: x-signup
  url: https://api.data.gov/signup/
- type: x-twitter
  url: https://twitter.com/fbopen
- type: x-website
  url: https://18f.github.io/fbopen-docs/apidocs#-all-opportunities
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---