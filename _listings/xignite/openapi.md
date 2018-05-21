---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Global Master
  description: this-web-service-provides-multiple-securityrelated-operations-including-mapping-of-symbol-cusip-cik-and-name-the-collection-of-statistical-information-to-be-used-in-stock-growth-simulations-split-information-and-lookup-services
  version: 1.0.0
host: globalmaster.xignite.com
basePath: xglobalmaster.json/XigniteGlobalMaster
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ListInstrumentClasses:
    post:
      summary: List Instrument Classes
      description: Get the possible instrument classes.
      operationId: ListInstrumentClasses
      x-api-path-slug: listinstrumentclasses-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - List
      - Instrument
      - Classes
---