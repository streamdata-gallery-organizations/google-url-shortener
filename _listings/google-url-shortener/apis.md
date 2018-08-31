---
name: Google URL Shortener
x-slug: google-url-shortener
description: The Google URL Shortener at goo.gl is a service that takes long URLs
  and squeezes them into fewer characters to make a link that is easier to share,
  tweet, or email to friends. Users can create these short links through the web interface
  at goo.gl, or they can programatically create them through the URL Shortener API.
  With the URL Shortener API you can write applications that use simple HTTP methods
  to create, inspect, and manage goo.gl short links from desktop, mobile, or web.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-shortener.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google URL Shortener
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-url-shortener/master/_listings/google-url-shortener/apis.md
specificationVersion: "0.14"
apis:
- name: URL Shortener - Get Short URLs
  x-api-slug: url-get
  description: Expands a short URL or gets creation time and analytics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-shortener.png
  humanURL: https://goo.gl/
  baseURL: ://www.googleapis.com//urlshortener/v1
  tags: Links, DNS, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API, URL Shorteners
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-url-shortener/master/_listings/google-url-shortener/url-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-url-shortener/master/_listings/google-url-shortener/url-get-openapi.md
- name: URL Shortener - Create Short URL
  x-api-slug: url-post
  description: Creates a new short URL.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-shortener.png
  humanURL: https://goo.gl/
  baseURL: ://www.googleapis.com//urlshortener/v1
  tags: Links, DNS, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API, URL Shorteners
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-url-shortener/master/_listings/google-url-shortener/url-post-openapi.md
- name: URL Shortener - Get URL History
  x-api-slug: urlhistory-get
  description: Retrieves a list of URLs shortened by a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-shortener.png
  humanURL: https://goo.gl/
  baseURL: ://www.googleapis.com//urlshortener/v1
  tags: Links, DNS, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API, URL Shorteners
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-url-shortener/master/_listings/google-url-shortener/urlhistory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-url-shortener/master/_listings/google-url-shortener/urlhistory-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.translate.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.url.shortener.stack.network
- type: x-developer
  url: https://developers.google.com/url-shortener/
- type: x-documentation
  url: https://developers.google.com/url-shortener/v1/
- type: x-getting-started
  url: https://developers.google.com/url-shortener/v1/getting_started
- type: x-performance
  url: https://developers.google.com/url-shortener/v1/performance
- type: x-website
  url: https://goo.gl/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---