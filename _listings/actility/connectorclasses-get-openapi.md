---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Dataflow API Connector processor classes retrieval
  description: Retrieves the list of system-wide processor classes providing connector
    behaviour.
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /dataflow/v021/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /binderClasses:
    get:
      summary: Binder processor classes retrieval
      description: Retrieves the list of system-wide processor classes providing binder
        (e.g. with a device) behaviour.
      operationId: retrieves-the-list-of-systemwide-processor-classes-providing-binder-eg-with-a-device-behaviour
      x-api-path-slug: binderclasses-get
      responses:
        200:
          description: OK
      tags:
      - Binder
      - Processor
      - Classes
      - Retrieval
  /driverClasses:
    get:
      summary: Driver processor classes retrieval
      description: Retrieves the list of system-wide processor classes providing driver
        behaviour.
      operationId: retrieves-the-list-of-systemwide-processor-classes-providing-driver-behaviour
      x-api-path-slug: driverclasses-get
      responses:
        200:
          description: OK
      tags:
      - Driver
      - Processor
      - Classes
      - Retrieval
  /connectorClasses:
    get:
      summary: Connector processor classes retrieval
      description: Retrieves the list of system-wide processor classes providing connector
        behaviour.
      operationId: retrieves-the-list-of-systemwide-processor-classes-providing-connector-behaviour
      x-api-path-slug: connectorclasses-get
      responses:
        200:
          description: OK
      tags:
      - Connector
      - Processor
      - Classes
      - Retrieval
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