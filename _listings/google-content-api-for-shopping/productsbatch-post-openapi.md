---
swagger: "2.0"
x-collection-name: Google Content API for Shopping
x-complete: 0
info:
  title: Google Content API for Shopping API Product Batches
  description: Retrieves, inserts, and deletes multiple products in a single request.
    This method can only be called for non-multi-client accounts.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /content/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/authinfo:
    get:
      summary: Authenticated User
      description: Returns information about the authenticated user.
      operationId: content.accounts.authinfo
      x-api-path-slug: accountsauthinfo-get
      responses:
        200:
          description: OK
      tags:
      - Authenticated
      - User
  /accounts/batch:
    post:
      summary: Account Batch
      description: Retrieves, inserts, updates, and deletes multiple Merchant Center
        (sub-)accounts in a single request.
      operationId: content.accounts.custombatch
      x-api-path-slug: accountsbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      responses:
        200:
          description: OK
      tags:
      - Account
      - Batch
  /accountshipping/batch:
    post:
      summary: Account Batches
      description: Retrieves and updates the shipping settings of multiple accounts
        in a single request.
      operationId: content.accountshipping.custombatch
      x-api-path-slug: accountshippingbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      responses:
        200:
          description: OK
      tags:
      - Account
      - Batches
  /accountstatuses/batch:
    post:
      summary: Account Status Batch
      description: Retrieves account batch status.
      operationId: content.accountstatuses.custombatch
      x-api-path-slug: accountstatusesbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Account
      - Status
      - Batch
  /accounttax/batch:
    post:
      summary: Account Taxes
      description: Retrieves and updates tax settings of multiple accounts in a single
        request.
      operationId: content.accounttax.custombatch
      x-api-path-slug: accounttaxbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      responses:
        200:
          description: OK
      tags:
      - Account
      - Taxes
  /datafeeds/batch:
    post:
      summary: Data Feeds
      description: Retrieves data feed batches.
      operationId: content.datafeeds.custombatch
      x-api-path-slug: datafeedsbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      responses:
        200:
          description: OK
      tags:
      - Data
      - Feeds
  /datafeedstatuses/batch:
    post:
      summary: Data Feed Status
      description: Retrieves data feed batch status.
      operationId: content.datafeedstatuses.custombatch
      x-api-path-slug: datafeedstatusesbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Data
      - Feed
      - Status
  /inventory/batch:
    post:
      summary: Inventory
      description: Updates price and availability for multiple products or stores
        in a single request. This operation does not update the expiration date of
        the products. This method can only be called for non-multi-client accounts.
      operationId: content.inventory.custombatch
      x-api-path-slug: inventorybatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      responses:
        200:
          description: OK
      tags:
      - Inventory
  /orders/batch:
    post:
      summary: Orders
      description: Retrieves or modifies multiple orders in a single request. This
        method can only be called for non-multi-client accounts.
      operationId: content.orders.custombatch
      x-api-path-slug: ordersbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Orders
  /products/batch:
    post:
      summary: Product Batches
      description: Retrieves, inserts, and deletes multiple products in a single request.
        This method can only be called for non-multi-client accounts.
      operationId: content.products.custombatch
      x-api-path-slug: productsbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      responses:
        200:
          description: OK
      tags:
      - Product
      - Batches
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