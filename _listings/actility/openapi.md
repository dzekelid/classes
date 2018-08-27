swagger: "2.0"
x-collection-name: Actility
x-complete: 1
info:
  title: ThingPark DX Maker API
  description: api-providing-features-for-device-makers-such-as-preprovisioning-on-standalone-join-servers-
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /maker/v011/api
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