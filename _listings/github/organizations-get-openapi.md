---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Organizations
  description: Get all organizations
  termsOfService: https://help.github.com/articles/github-terms-of-service/#b-api-terms
  version: 1.0.0
host: api.github.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations:
    get:
      summary: Get Organizations
      description: Get all organizations
      operationId: getOrganizations
      x-api-path-slug: organizations-get
      responses:
        200:
          description: OK
      tags:
      - Organizations
x-streamrank:
  polling_total_time_average: "0.16"
  polling_size_download_average: "16805.74"
  streaming_total_time_average: "0.09"
  streaming_size_download_average: "8406.46"
  change_yes: "3"
  change_no: "2338"
  time_percentage: "41"
  size_percentage: "50"
  change_percentage: "0"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---