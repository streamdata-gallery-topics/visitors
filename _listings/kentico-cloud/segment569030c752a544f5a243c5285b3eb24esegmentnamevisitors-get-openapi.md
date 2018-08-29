---
swagger: "2.0"
x-collection-name: Kentico Cloud
x-complete: 0
info:
  title: Kentico Cloud List visitors of a segment
  description: Retrieve visitors that match the specified segment.
  version: 1.0.0
host: deliver.kenticocloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /segment/569030c7-52a5-44f5-a243-c5285b3eb24e/{SegmentName}/visitors:
    get:
      summary: List visitors of a segment
      description: Retrieve visitors that match the specified segment.
      operationId: Segment569030c752a544f5A243C5285b3eb24eVisitorsBySegmentNameGet
      x-api-path-slug: segment569030c752a544f5a243c5285b3eb24esegmentnamevisitors-get
      parameters:
      - in: path
        name: SegmentName
      responses:
        200:
          description: OK
      tags:
      - List
      - Visitors
      - Of
      - Segment
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