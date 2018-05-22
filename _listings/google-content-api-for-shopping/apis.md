---
name: Google Content API for Shopping
x-slug: google-content-api-for-shopping
description: 'API allowing retailers to manage their product feed content programmatically.
  Providing item-level data quality information: See if an item was disapproved because
  a landing page URL isn&rsquo;t working on a mobile device or if unique product identifiers
  are inaccurate. Faster pricing and availability updates: Ensure customers have the
  latest price-points and know what&rsquo;s in-stock before they click through to
  your site. More integration options: The newer API supports a broader choice of
  programming languages and data formats.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
x-kinRank: "9"
x-alexaRank: ""
tags: Google Content API for Shopping
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/apis.md
specificationVersion: "0.14"
apis:
- name: Google Content API for Shopping API Authenticated User
  x-api-slug: google-content-api-for-shopping-api
  description: Returns information about the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//accounts/authinfo
  tags: Authenticated, User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/accountsauthinfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/accountsauthinfo-get-openapi.md
- name: Google Content API for Shopping API Account Batch
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves, inserts, updates, and deletes multiple Merchant Center (sub-)accounts
    in a single request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//accounts/batch
  tags: Account, Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/accountsbatch-post-openapi.md
- name: Google Content API for Shopping API Account Batches
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves and updates the shipping settings of multiple accounts in
    a single request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//accountshipping/batch
  tags: Account, Batches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/accountshippingbatch-post-openapi.md
- name: Google Content API for Shopping API Account Status Batch
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves account batch status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//accountstatuses/batch
  tags: Account, Status, Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/accountstatusesbatch-post-openapi.md
- name: Google Content API for Shopping API Account Taxes
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves and updates tax settings of multiple accounts in a single
    request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//accounttax/batch
  tags: Account, Taxes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/accounttaxbatch-post-openapi.md
- name: Google Content API for Shopping API Data Feeds
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves data feed batches.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//datafeeds/batch
  tags: Data, Feeds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/datafeedsbatch-post-openapi.md
- name: Google Content API for Shopping API Data Feed Status
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves data feed batch status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//datafeedstatuses/batch
  tags: Data, Feed, Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/datafeedstatusesbatch-post-openapi.md
- name: Google Content API for Shopping API Inventory
  x-api-slug: google-content-api-for-shopping-api
  description: Updates price and availability for multiple products or stores in a
    single request. This operation does not update the expiration date of the products.
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//inventory/batch
  tags: Inventory
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/inventorybatch-post-openapi.md
- name: Google Content API for Shopping API Orders
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves or modifies multiple orders in a single request. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//orders/batch
  tags: Orders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/ordersbatch-post-openapi.md
- name: Google Content API for Shopping API Product Batches
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves, inserts, and deletes multiple products in a single request.
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//products/batch
  tags: Product, Batches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/productsbatch-post-openapi.md
- name: Google Content API for Shopping API Product Batch
  x-api-slug: google-content-api-for-shopping-api
  description: Gets the statuses of multiple products in a single request. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//productstatuses/batch
  tags: Product, Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/productstatusesbatch-post-openapi.md
- name: Google Content API for Shopping API Shipping Settings
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves and updates the shipping settings of multiple accounts in
    a single request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//shippingsettings/batch
  tags: Shipping, Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/shippingsettingsbatch-post-openapi.md
- name: Google Content API for Shopping API Get Accounts
  x-api-slug: google-content-api-for-shopping-api
  description: Lists the sub-accounts in your Merchant Center account. This method
    can only be called for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accounts
  tags: Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounts-get-openapi.md
- name: Google Content API for Shopping API Create Accounts
  x-api-slug: google-content-api-for-shopping-api
  description: Creates a Merchant Center sub-account. This method can only be called
    for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accounts
  tags: Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounts-post-openapi.md
- name: Google Content API for Shopping API Delete Account
  x-api-slug: google-content-api-for-shopping-api
  description: Deletes a Merchant Center sub-account. This method can only be called
    for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accounts/{accountId}
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountsaccountid-delete-openapi.md
- name: Google Content API for Shopping API Get Account
  x-api-slug: google-content-api-for-shopping-api
  description: 'Retrieves a Merchant Center account. This method can only be called
    for accounts to which the managing account has access: either the managing account
    itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accounts/{accountId}
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountsaccountid-get-openapi.md
- name: Google Content API for Shopping API Update Account
  x-api-slug: google-content-api-for-shopping-api
  description: 'Updates a Merchant Center account. This method can only be called
    for accounts to which the managing account has access: either the managing account
    itself or sub-accounts if the managing account is a multi-client account. This
    method supports patch semantics.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accounts/{accountId}
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountsaccountid-patch-openapi.md
- name: Google Content API for Shopping API Update Account
  x-api-slug: google-content-api-for-shopping-api
  description: 'Updates a Merchant Center account. This method can only be called
    for accounts to which the managing account has access: either the managing account
    itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accounts/{accountId}
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountsaccountid-put-openapi.md
- name: Google Content API for Shopping API Get Account Shipping
  x-api-slug: google-content-api-for-shopping-api
  description: Lists the shipping settings of the sub-accounts in your Merchant Center
    account. This method can only be called for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accountshipping
  tags: Account, Shipping
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountshipping-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountshipping-get-openapi.md
- name: Google Content API for Shopping API Get Account Shipping
  x-api-slug: google-content-api-for-shopping-api
  description: 'Retrieves the shipping settings of the account. This method can only
    be called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accountshipping/{accountId}
  tags: Account, Shipping
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountshippingaccountid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountshippingaccountid-get-openapi.md
- name: Google Content API for Shopping API Updat Account Shipping
  x-api-slug: google-content-api-for-shopping-api
  description: 'Updates the shipping settings of the account. This method can only
    be called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.
    This method supports patch semantics.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accountshipping/{accountId}
  tags: Updat, Account, Shipping
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountshippingaccountid-patch-openapi.md
- name: Google Content API for Shopping API Updat Account Shipping
  x-api-slug: google-content-api-for-shopping-api
  description: 'Updates the shipping settings of the account. This method can only
    be called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accountshipping/{accountId}
  tags: Updat, Account, Shipping
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountshippingaccountid-put-openapi.md
- name: Google Content API for Shopping API Get Account Status
  x-api-slug: google-content-api-for-shopping-api
  description: Lists the statuses of the sub-accounts in your Merchant Center account.
    This method can only be called for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accountstatuses
  tags: Account, Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountstatuses-get-openapi.md
- name: Google Content API for Shopping API Get Account Status
  x-api-slug: google-content-api-for-shopping-api
  description: 'Retrieves the status of a Merchant Center account. This method can
    only be called for accounts to which the managing account has access: either the
    managing account itself or sub-accounts if the managing account is a multi-client
    account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accountstatuses/{accountId}
  tags: Account, Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountstatusesaccountid-get-openapi.md
- name: Google Content API for Shopping API Get Account Taxes
  x-api-slug: google-content-api-for-shopping-api
  description: Lists the tax settings of the sub-accounts in your Merchant Center
    account. This method can only be called for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accounttax
  tags: Account, Taxes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounttax-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounttax-get-openapi.md
- name: Google Content API for Shopping API Get Account Tax
  x-api-slug: google-content-api-for-shopping-api
  description: 'Retrieves the tax settings of the account. This method can only be
    called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accounttax/{accountId}
  tags: Account, Tax
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounttaxaccountid-get-openapi.md
- name: Google Content API for Shopping API Update Account Tax
  x-api-slug: google-content-api-for-shopping-api
  description: 'Updates the tax settings of the account. This method can only be called
    for accounts to which the managing account has access: either the managing account
    itself or sub-accounts if the managing account is a multi-client account. This
    method supports patch semantics.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accounttax/{accountId}
  tags: Account, Tax
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounttaxaccountid-patch-openapi.md
- name: Google Content API for Shopping API Update Account Tax
  x-api-slug: google-content-api-for-shopping-api
  description: 'Updates the tax settings of the account. This method can only be called
    for accounts to which the managing account has access: either the managing account
    itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/accounttax/{accountId}
  tags: Account, Tax
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounttaxaccountid-put-openapi.md
- name: Google Content API for Shopping API Get Data Feeds
  x-api-slug: google-content-api-for-shopping-api
  description: Lists the datafeeds in your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeeds
  tags: Data, Feeds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeeds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeeds-get-openapi.md
- name: Google Content API for Shopping API Create Data Feed
  x-api-slug: google-content-api-for-shopping-api
  description: Registers a datafeed with your Merchant Center account. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeeds
  tags: Data, Feed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeeds-post-openapi.md
- name: Google Content API for Shopping API Delete Data Feed
  x-api-slug: google-content-api-for-shopping-api
  description: Deletes a datafeed from your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeeds/{datafeedId}
  tags: Data, Feed
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-delete-openapi.md
- name: Google Content API for Shopping API Get Data Feed
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves a datafeed from your Merchant Center account. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeeds/{datafeedId}
  tags: Data, Feed
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-get-openapi.md
- name: Google Content API for Shopping API Update Data Feed
  x-api-slug: google-content-api-for-shopping-api
  description: Updates a datafeed of your Merchant Center account. This method can
    only be called for non-multi-client accounts. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeeds/{datafeedId}
  tags: Data, Feed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-patch-openapi.md
- name: Google Content API for Shopping API Update Data Feed
  x-api-slug: google-content-api-for-shopping-api
  description: Updates a datafeed of your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeeds/{datafeedId}
  tags: Data, Feed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-put-openapi.md
- name: Google Content API for Shopping API Get Data Feed Status
  x-api-slug: google-content-api-for-shopping-api
  description: Lists the statuses of the datafeeds in your Merchant Center account.
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeedstatuses
  tags: Data, Feed, Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedstatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedstatuses-get-openapi.md
- name: Google Content API for Shopping API Get Data Feed Status
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves the status of a datafeed from your Merchant Center account.
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeedstatuses/{datafeedId}
  tags: Data, Feed, Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedstatusesdatafeedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedstatusesdatafeedid-get-openapi.md
- name: Google Content API for Shopping API Update Price
  x-api-slug: google-content-api-for-shopping-api
  description: Updates price and availability of a product in your Merchant Center
    account. This operation does not update the expiration date of the product. This
    method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/inventory/{storeCode}/products/{productId}
  tags: Price
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidinventorystorecodeproductsproductid-post-openapi.md
- name: Google Content API for Shopping API Get Orders
  x-api-slug: google-content-api-for-shopping-api
  description: Lists the orders in your Merchant Center account. This method can only
    be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/orders
  tags: Orders
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidorders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidorders-get-openapi.md
- name: Google Content API for Shopping API Get Order
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves an order from your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/orders/{orderId}
  tags: Order
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderid-get-openapi.md
- name: Google Content API for Shopping API Acknowledge Order
  x-api-slug: google-content-api-for-shopping-api
  description: Marks an order as acknowledged. This method can only be called for
    non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/orders/{orderId}/acknowledge
  tags: Acknowledge, Order
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidacknowledge-post-openapi.md
- name: Google Content API for Shopping API Cancel Order
  x-api-slug: google-content-api-for-shopping-api
  description: Cancels all line items in an order. This method can only be called
    for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/orders/{orderId}/cancel
  tags: Cancel, Order
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidcancel-post-openapi.md
- name: Google Content API for Shopping API Cancel Order Line Item
  x-api-slug: google-content-api-for-shopping-api
  description: Cancels a line item. This method can only be called for non-multi-client
    accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/orders/{orderId}/cancelLineItem
  tags: Cancel, Order, Line, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidcancellineitem-post-openapi.md
- name: Google Content API for Shopping API Refund Order
  x-api-slug: google-content-api-for-shopping-api
  description: Refund a portion of the order, up to the full amount paid. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/orders/{orderId}/refund
  tags: Refund, Order
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidrefund-post-openapi.md
- name: Google Content API for Shopping API Return Line Item
  x-api-slug: google-content-api-for-shopping-api
  description: Returns a line item. This method can only be called for non-multi-client
    accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/orders/{orderId}/returnLineItem
  tags: Return, Line, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidreturnlineitem-post-openapi.md
- name: Google Content API for Shopping API Ship Line Item
  x-api-slug: google-content-api-for-shopping-api
  description: Marks line item(s) as shipped. This method can only be called for non-multi-client
    accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/orders/{orderId}/shipLineItems
  tags: Ship, Line, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidshiplineitems-post-openapi.md
- name: Google Content API for Shopping API Update Merchant Order ID
  x-api-slug: google-content-api-for-shopping-api
  description: Updates the merchant order ID for a given order. This method can only
    be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/orders/{orderId}/updateMerchantOrderId
  tags: Merchant, Order, ID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidupdatemerchantorderid-post-openapi.md
- name: Google Content API for Shopping API Update order Shippment
  x-api-slug: google-content-api-for-shopping-api
  description: Updates a shipment's status, carrier, and/or tracking ID. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/orders/{orderId}/updateShipment
  tags: order, Shippment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidupdateshipment-post-openapi.md
- name: Google Content API for Shopping API Get Order
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves an order using merchant order id. This method can only be
    called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/ordersbymerchantid/{merchantOrderId}
  tags: Order
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersbymerchantidmerchantorderid-get-openapi.md
- name: Google Content API for Shopping API Get Prudcts
  x-api-slug: google-content-api-for-shopping-api
  description: Lists the products in your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/products
  tags: Prudcts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidproducts-get-openapi.md
- name: Google Content API for Shopping API Upload Product
  x-api-slug: google-content-api-for-shopping-api
  description: Uploads a product to your Merchant Center account. If an item with
    the same channel, contentLanguage, offerId, and targetCountry already exists,
    this method updates that entry. This method can only be called for non-multi-client
    accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/products
  tags: Upload, Product
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidproducts-post-openapi.md
- name: Google Content API for Shopping API Delete Product
  x-api-slug: google-content-api-for-shopping-api
  description: Deletes a product from your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/products/{productId}
  tags: Product
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidproductsproductid-delete-openapi.md
- name: Google Content API for Shopping API Get Product
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves a product from your Merchant Center account. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/products/{productId}
  tags: Product
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidproductsproductid-get-openapi.md
- name: Google Content API for Shopping API Get Product Status
  x-api-slug: google-content-api-for-shopping-api
  description: Lists the statuses of the products in your Merchant Center account.
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/productstatuses
  tags: Product, Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidproductstatuses-get-openapi.md
- name: Google Content API for Shopping API Get Product Status
  x-api-slug: google-content-api-for-shopping-api
  description: Gets the status of a product from your Merchant Center account. This
    method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/productstatuses/{productId}
  tags: Product, Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidproductstatusesproductid-get-openapi.md
- name: Google Content API for Shopping API Get Shipping Settings
  x-api-slug: google-content-api-for-shopping-api
  description: Lists the shipping settings of the sub-accounts in your Merchant Center
    account. This method can only be called for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/shippingsettings
  tags: Shipping, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidshippingsettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidshippingsettings-get-openapi.md
- name: Google Content API for Shopping API Get Shipping Settings
  x-api-slug: google-content-api-for-shopping-api
  description: 'Retrieves the shipping settings of the account. This method can only
    be called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/shippingsettings/{accountId}
  tags: Shipping, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidshippingsettingsaccountid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidshippingsettingsaccountid-get-openapi.md
- name: Google Content API for Shopping API Update Shipping Settings
  x-api-slug: google-content-api-for-shopping-api
  description: 'Updates the shipping settings of the account. This method can only
    be called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.
    This method supports patch semantics.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/shippingsettings/{accountId}
  tags: Shipping, Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidshippingsettingsaccountid-patch-openapi.md
- name: Google Content API for Shopping API Update Shipping Settings
  x-api-slug: google-content-api-for-shopping-api
  description: 'Updates the shipping settings of the account. This method can only
    be called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/shippingsettings/{accountId}
  tags: Shipping, Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidshippingsettingsaccountid-put-openapi.md
- name: Google Content API for Shopping API Get Supported Carriers
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves supported carriers and carrier services for an account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/supportedCarriers
  tags: Supported, Carriers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidsupportedcarriers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidsupportedcarriers-get-openapi.md
- name: Google Content API for Shopping API Create Test Order
  x-api-slug: google-content-api-for-shopping-api
  description: Sandbox only. Creates a test order. This method can only be called
    for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/testorders
  tags: Test, Order
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidtestorders-post-openapi.md
- name: Google Content API for Shopping API Update Test Order
  x-api-slug: google-content-api-for-shopping-api
  description: Sandbox only. Moves a test order from state "inProgress" to state "pendingShipment".
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/testorders/{orderId}/advance
  tags: Test, Order
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidtestordersorderidadvance-post-openapi.md
- name: Google Content API for Shopping API Get Test Order
  x-api-slug: google-content-api-for-shopping-api
  description: Sandbox only. Retrieves an order template that can be used to quickly
    create a new order in sandbox. This method can only be called for non-multi-client
    accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/testordertemplates/{templateName}
  tags: Test, Order
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidtestordertemplatestemplatename-get-openapi.md
- name: Google Content API for Shopping API
  x-api-slug: google-content-api-for-shopping-api
  description: 'API allowing retailers to manage their product feed content programmatically.
    Providing item-level data quality information: See if an item was disapproved
    because a landing page URL isn&rsquo;t working on a mobile device or if unique
    product identifiers are inaccurate. Faster pricing and availability updates: Ensure
    customers have the latest price-points and know what&rsquo;s in-stock before they
    click through to your site. More integration options: The newer API supports a
    broader choice of programming languages and data formats.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Google Content API for Shopping
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/openapi.md
x-common:
- type: x-best-practices
  url: https://developers.google.com/shopping-content/v2/best-practices
- type: x-code
  url: https://developers.google.com/shopping-content/v2/libraries
- type: x-testing
  url: https://developers.google.com/shopping-content/v2/how-tos/testing
- type: x-website
  url: https://developers.google.com/shopping-content/v2/quickstart
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---