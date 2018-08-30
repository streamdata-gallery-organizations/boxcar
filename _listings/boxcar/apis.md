---
name: Boxcar
x-slug: boxcar
description: 'For Developers: a push platform with SDKs, APIs and admin console.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/714-boxcar.jpg
x-kinRank: "8"
x-alexaRank: "1280273"
tags: Boxcar
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/boxcar/master/_listings/boxcar/apis.md
specificationVersion: "0.14"
apis:
- name: Box Car - Subscribe to Provider
  x-api-slug: notificationssubscribe-post
  description: This sends the user with the matching e-mail address a push notification
    which requests that they add your service. This will ease integration with your
    website, as you will have already registered them on your system and can identify
    whom they are based on their Boxcar e-mail address. Please note, this API call
    is an exception and will return an HTTP status code of 404 if we are unable to
    find the registered user by e-mail in our system. If the email address is not
    found in our system, we'll send an email to it letting the user know where they
    can download Boxcar. If the user has already added your service, we'll return
    an HTTP status code of 401.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/714-boxcar.jpg
  humanURL: http://boxcar.io
  baseURL: https://boxcar.io//devices/providers/%7Bprovider_key%7D/
  tags: Social, Notifications, Stack Network, SaaS, Mobile, Technology, internet,
    API Provider, Notifications, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/boxcar/master/_listings/boxcar/notificationssubscribe-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/boxcar/master/_listings/boxcar/notificationssubscribe-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://box.api.gallery.streamdata.io
- type: x-api-stack
  url: http://boxcar.stack.network
- type: x-blog
  url: http://blog.boxcar.io
- type: x-blog-rss
  url: http://blog.boxcar.io/rss
- type: x-crunchbase
  url: http://www.crunchbase.com/company/boxcar
- type: x-crunchbase
  url: https://crunchbase.com/organization/boxcar
- type: x-developer
  url: https://boxcar.io/developer
- type: x-email
  url: help@boxcar.io
- type: x-github
  url: https://github.com/boxcar
- type: x-twitter
  url: https://twitter.com/boxcar
- type: x-website
  url: http://boxcar.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---