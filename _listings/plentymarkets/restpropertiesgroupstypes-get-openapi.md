---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Get group types from module configuration
  description: Get group types from module configuration.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/properties/groups/surcharge/types:
    get:
      summary: Get surcharge types from module configuration
      description: Get surcharge types from module configuration.
      operationId: getRestPropertiesGroupsSurchargeTypes
      x-api-path-slug: restpropertiesgroupssurchargetypes-get
      responses:
        200:
          description: OK
      tags:
      - Surcharge
      - Types
      - From
      - Module
      - Configuration
  /rest/properties/groups/types:
    get:
      summary: Get group types from module configuration
      description: Get group types from module configuration.
      operationId: getRestPropertiesGroupsTypes
      x-api-path-slug: restpropertiesgroupstypes-get
      responses:
        200:
          description: OK
      tags:
      - Group
      - Types
      - From
      - Module
      - Configuration
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