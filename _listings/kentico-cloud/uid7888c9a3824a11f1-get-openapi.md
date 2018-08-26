---
swagger: "2.0"
x-collection-name: Kentico Cloud
x-complete: 0
info:
  title: Kentico Cloud View data of visitor by ID
  description: ""
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
  /visitor/569030c7-52a5-44f5-a243-c5285b3eb24e/e3e9e191a12b9257/segment:
    get:
      summary: Retrieving visitor's segments
      description: "Use the Personalization API to retrieve the list of segments that
        the specified visitor belongs to.\n\n* Authenticate the request using your
        Personalization API Key.\n* Specify the User ID of the visitor you are asking
        about.\n \nSee <https://developer.kenticocloud.com/docs/personalizing-content#section-retrieving-visitor-s-segments>
        for more details."
      operationId: Visitor569030c752a544f5A243C5285b3eb24eE3e9e191a12b9257SegmentGet
      x-api-path-slug: visitor569030c752a544f5a243c5285b3eb24ee3e9e191a12b9257segment-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Retrieving
      - Visitors
      - Segments
  /visitor/569030c7-52a5-44f5-a243-c5285b3eb24e/7888c9a3824a11f1/segments:
    get:
      summary: List segments of a visitor
      description: Retrieve the names of segments that the specified visitor belongs
        to.
      operationId: Visitor569030c752a544f5A243C5285b3eb24e7888c9a3824a11f1SegmentsGet
      x-api-path-slug: visitor569030c752a544f5a243c5285b3eb24e7888c9a3824a11f1segments-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Segments
      - Of
      - Visitor
  /uid/7888c9a3824a11f1:
    get:
      summary: View data of visitor by ID
      description: ""
      operationId: Uid7888c9a3824a11f1Get
      x-api-path-slug: uid7888c9a3824a11f1-get
      responses:
        200:
          description: OK
      tags:
      - View
      - Data
      - Of
      - Visitor
      - By
      - ID
    delete:
      summary: Delete data of visitor by ID
      description: ""
      operationId: Uid7888c9a3824a11f1Delete
      x-api-path-slug: uid7888c9a3824a11f1-delete
      responses:
        200:
          description: OK
      tags:
      - Data
      - Of
      - Visitor
      - By
      - ID
  /email/lola.mira@blabla.com:
    get:
      summary: View data of visitor by email
      description: ""
      operationId: EmailLolaMiraBlablaComGet
      x-api-path-slug: emaillola-mirablabla-com-get
      responses:
        200:
          description: OK
      tags:
      - View
      - Data
      - Of
      - Visitor
      - By
      - Email
    delete:
      summary: Delete data of visitor by email
      description: ""
      operationId: EmailLolaMiraBlablaComDelete
      x-api-path-slug: emaillola-mirablabla-com-delete
      responses:
        200:
          description: OK
      tags:
      - Data
      - Of
      - Visitor
      - By
      - Email
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