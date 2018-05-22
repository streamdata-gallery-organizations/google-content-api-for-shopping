---
swagger: "2.0"
x-collection-name: Google Content API for Shopping
x-complete: 0
info:
  title: Google Content API for Shopping API Create Data Feed
  description: Registers a datafeed with your Merchant Center account. This method
    can only be called for non-multi-client accounts.
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
  /productstatuses/batch:
    post:
      summary: Product Batch
      description: Gets the statuses of multiple products in a single request. This
        method can only be called for non-multi-client accounts.
      operationId: content.productstatuses.custombatch
      x-api-path-slug: productstatusesbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Product
      - Batch
  /shippingsettings/batch:
    post:
      summary: Shipping Settings
      description: Retrieves and updates the shipping settings of multiple accounts
        in a single request.
      operationId: content.shippingsettings.custombatch
      x-api-path-slug: shippingsettingsbatch-post
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
      - Shipping
      - Settings
  /{merchantId}/accounts:
    get:
      summary: Get Accounts
      description: Lists the sub-accounts in your Merchant Center account. This method
        can only be called for multi-client accounts.
      operationId: content.accounts.list
      x-api-path-slug: merchantidaccounts-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of accounts to return in the response, used
          for paging
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: query
        name: pageToken
        description: The token returned by the previous request
      responses:
        200:
          description: OK
      tags:
      - Accounts
    post:
      summary: Create Accounts
      description: Creates a Merchant Center sub-account. This method can only be
        called for multi-client accounts.
      operationId: content.accounts.insert
      x-api-path-slug: merchantidaccounts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Accounts
  /{merchantId}/accounts/{accountId}:
    delete:
      summary: Delete Account
      description: Deletes a Merchant Center sub-account. This method can only be
        called for multi-client accounts.
      operationId: content.accounts.delete
      x-api-path-slug: merchantidaccountsaccountid-delete
      parameters:
      - in: path
        name: accountId
        description: The ID of the account
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Account
    get:
      summary: Get Account
      description: 'Retrieves a Merchant Center account. This method can only be called
        for accounts to which the managing account has access: either the managing
        account itself or sub-accounts if the managing account is a multi-client account.'
      operationId: content.accounts.get
      x-api-path-slug: merchantidaccountsaccountid-get
      parameters:
      - in: path
        name: accountId
        description: The ID of the account
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Account
    patch:
      summary: Update Account
      description: 'Updates a Merchant Center account. This method can only be called
        for accounts to which the managing account has access: either the managing
        account itself or sub-accounts if the managing account is a multi-client account.
        This method supports patch semantics.'
      operationId: content.accounts.patch
      x-api-path-slug: merchantidaccountsaccountid-patch
      parameters:
      - in: path
        name: accountId
        description: The ID of the account
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Account
    put:
      summary: Update Account
      description: 'Updates a Merchant Center account. This method can only be called
        for accounts to which the managing account has access: either the managing
        account itself or sub-accounts if the managing account is a multi-client account.'
      operationId: content.accounts.update
      x-api-path-slug: merchantidaccountsaccountid-put
      parameters:
      - in: path
        name: accountId
        description: The ID of the account
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Account
  /{merchantId}/accountshipping:
    get:
      summary: Get Account Shipping
      description: Lists the shipping settings of the sub-accounts in your Merchant
        Center account. This method can only be called for multi-client accounts.
      operationId: content.accountshipping.list
      x-api-path-slug: merchantidaccountshipping-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of shipping settings to return in the response,
          used for paging
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: query
        name: pageToken
        description: The token returned by the previous request
      responses:
        200:
          description: OK
      tags:
      - Account
      - Shipping
  /{merchantId}/accountshipping/{accountId}:
    get:
      summary: Get Account Shipping
      description: 'Retrieves the shipping settings of the account. This method can
        only be called for accounts to which the managing account has access: either
        the managing account itself or sub-accounts if the managing account is a multi-client
        account.'
      operationId: content.accountshipping.get
      x-api-path-slug: merchantidaccountshippingaccountid-get
      parameters:
      - in: path
        name: accountId
        description: The ID of the account for which to get/update account shipping
          settings
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Account
      - Shipping
    patch:
      summary: Updat Account Shipping
      description: 'Updates the shipping settings of the account. This method can
        only be called for accounts to which the managing account has access: either
        the managing account itself or sub-accounts if the managing account is a multi-client
        account. This method supports patch semantics.'
      operationId: content.accountshipping.patch
      x-api-path-slug: merchantidaccountshippingaccountid-patch
      parameters:
      - in: path
        name: accountId
        description: The ID of the account for which to get/update account shipping
          settings
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Updat
      - Account
      - Shipping
    put:
      summary: Updat Account Shipping
      description: 'Updates the shipping settings of the account. This method can
        only be called for accounts to which the managing account has access: either
        the managing account itself or sub-accounts if the managing account is a multi-client
        account.'
      operationId: content.accountshipping.update
      x-api-path-slug: merchantidaccountshippingaccountid-put
      parameters:
      - in: path
        name: accountId
        description: The ID of the account for which to get/update account shipping
          settings
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Updat
      - Account
      - Shipping
  /{merchantId}/accountstatuses:
    get:
      summary: Get Account Status
      description: Lists the statuses of the sub-accounts in your Merchant Center
        account. This method can only be called for multi-client accounts.
      operationId: content.accountstatuses.list
      x-api-path-slug: merchantidaccountstatuses-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of account statuses to return in the response,
          used for paging
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: query
        name: pageToken
        description: The token returned by the previous request
      responses:
        200:
          description: OK
      tags:
      - Account
      - Status
  /{merchantId}/accountstatuses/{accountId}:
    get:
      summary: Get Account Status
      description: 'Retrieves the status of a Merchant Center account. This method
        can only be called for accounts to which the managing account has access:
        either the managing account itself or sub-accounts if the managing account
        is a multi-client account.'
      operationId: content.accountstatuses.get
      x-api-path-slug: merchantidaccountstatusesaccountid-get
      parameters:
      - in: path
        name: accountId
        description: The ID of the account
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Account
      - Status
  /{merchantId}/accounttax:
    get:
      summary: Get Account Taxes
      description: Lists the tax settings of the sub-accounts in your Merchant Center
        account. This method can only be called for multi-client accounts.
      operationId: content.accounttax.list
      x-api-path-slug: merchantidaccounttax-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of tax settings to return in the response,
          used for paging
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: query
        name: pageToken
        description: The token returned by the previous request
      responses:
        200:
          description: OK
      tags:
      - Account
      - Taxes
  /{merchantId}/accounttax/{accountId}:
    get:
      summary: Get Account Tax
      description: 'Retrieves the tax settings of the account. This method can only
        be called for accounts to which the managing account has access: either the
        managing account itself or sub-accounts if the managing account is a multi-client
        account.'
      operationId: content.accounttax.get
      x-api-path-slug: merchantidaccounttaxaccountid-get
      parameters:
      - in: path
        name: accountId
        description: The ID of the account for which to get/update account tax settings
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Account
      - Tax
    patch:
      summary: Update Account Tax
      description: 'Updates the tax settings of the account. This method can only
        be called for accounts to which the managing account has access: either the
        managing account itself or sub-accounts if the managing account is a multi-client
        account. This method supports patch semantics.'
      operationId: content.accounttax.patch
      x-api-path-slug: merchantidaccounttaxaccountid-patch
      parameters:
      - in: path
        name: accountId
        description: The ID of the account for which to get/update account tax settings
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Account
      - Tax
    put:
      summary: Update Account Tax
      description: 'Updates the tax settings of the account. This method can only
        be called for accounts to which the managing account has access: either the
        managing account itself or sub-accounts if the managing account is a multi-client
        account.'
      operationId: content.accounttax.update
      x-api-path-slug: merchantidaccounttaxaccountid-put
      parameters:
      - in: path
        name: accountId
        description: The ID of the account for which to get/update account tax settings
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Account
      - Tax
  /{merchantId}/datafeeds:
    get:
      summary: Get Data Feeds
      description: Lists the datafeeds in your Merchant Center account. This method
        can only be called for non-multi-client accounts.
      operationId: content.datafeeds.list
      x-api-path-slug: merchantiddatafeeds-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of products to return in the response, used
          for paging
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: query
        name: pageToken
        description: The token returned by the previous request
      responses:
        200:
          description: OK
      tags:
      - Data
      - Feeds
    post:
      summary: Create Data Feed
      description: Registers a datafeed with your Merchant Center account. This method
        can only be called for non-multi-client accounts.
      operationId: content.datafeeds.insert
      x-api-path-slug: merchantiddatafeeds-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
      responses:
        200:
          description: OK
      tags:
      - Data
      - Feed
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