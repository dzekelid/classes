---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
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
  /rest/accounts/contacts/classes:
    get:
      summary: List contact classes
      description: List contact classes.
      operationId: getRestAccountsContactsClasses
      x-api-path-slug: restaccountscontactsclasses-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Classes
  /rest/items/sales_prices/{id}/customer_classes:
    get:
      summary: List activated customer classes
      description: Lists the activated customer classes for a sales price. The ID
        of the sales price must be specified.
      operationId: getRestItemsSalesPricesCustomerClasses
      x-api-path-slug: restitemssales-pricesidcustomer-classes-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Activated
      - Customer
      - Classes
---