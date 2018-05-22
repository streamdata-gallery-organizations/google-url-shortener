---
swagger: "2.0"
x-collection-name: Google URL Shortener
x-complete: 0
info:
  title: Google URL Shortener API Get Short URLs
  description: Expands a short URL or gets creation time and analytics.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /urlshortener/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /url:
    get:
      summary: Get Short URLs
      description: Expands a short URL or gets creation time and analytics.
      operationId: urlshortener.url.get
      x-api-path-slug: url-get
      parameters:
      - in: query
        name: projection
        description: Additional information to return
      - in: query
        name: shortUrl
        description: The short URL, including the protocol
      responses:
        200:
          description: OK
      tags:
      - Short URL
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