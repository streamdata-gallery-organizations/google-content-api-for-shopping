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
x-alexaRank: "0"
tags: Google Content API for Shopping
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/apis.md
specificationVersion: "0.14"
apis:
- name: Content API for Shopping - Authenticated User
  x-api-slug: accountsauthinfo-get
  description: Returns information about the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/accountsauthinfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/accountsauthinfo-get-openapi.md
- name: Content API for Shopping - Account Batch
  x-api-slug: accountsbatch-post
  description: Retrieves, inserts, updates, and deletes multiple Merchant Center (sub-)accounts
    in a single request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/accountsbatch-post-openapi.md
- name: Content API for Shopping - Account Batches
  x-api-slug: accountshippingbatch-post
  description: Retrieves and updates the shipping settings of multiple accounts in
    a single request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/accountshippingbatch-post-openapi.md
- name: Content API for Shopping - Account Status Batch
  x-api-slug: accountstatusesbatch-post
  description: Retrieves account batch status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/accountstatusesbatch-post-openapi.md
- name: Content API for Shopping - Account Taxes
  x-api-slug: accounttaxbatch-post
  description: Retrieves and updates tax settings of multiple accounts in a single
    request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/accounttaxbatch-post-openapi.md
- name: Content API for Shopping - Data Feeds
  x-api-slug: datafeedsbatch-post
  description: Retrieves data feed batches.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/datafeedsbatch-post-openapi.md
- name: Content API for Shopping - Data Feed Status
  x-api-slug: datafeedstatusesbatch-post
  description: Retrieves data feed batch status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/datafeedstatusesbatch-post-openapi.md
- name: Content API for Shopping - Inventory
  x-api-slug: inventorybatch-post
  description: Updates price and availability for multiple products or stores in a
    single request. This operation does not update the expiration date of the products.
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/inventorybatch-post-openapi.md
- name: Content API for Shopping - Orders
  x-api-slug: ordersbatch-post
  description: Retrieves or modifies multiple orders in a single request. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/ordersbatch-post-openapi.md
- name: Content API for Shopping - Product Batches
  x-api-slug: productsbatch-post
  description: Retrieves, inserts, and deletes multiple products in a single request.
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/productsbatch-post-openapi.md
- name: Content API for Shopping - Product Batch
  x-api-slug: productstatusesbatch-post
  description: Gets the statuses of multiple products in a single request. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/productstatusesbatch-post-openapi.md
- name: Content API for Shopping - Shipping Settings
  x-api-slug: shippingsettingsbatch-post
  description: Retrieves and updates the shipping settings of multiple accounts in
    a single request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/shippingsettingsbatch-post-openapi.md
- name: Content API for Shopping - Get Accounts
  x-api-slug: merchantidaccounts-get
  description: Lists the sub-accounts in your Merchant Center account. This method
    can only be called for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounts-get-openapi.md
- name: Content API for Shopping - Create Accounts
  x-api-slug: merchantidaccounts-post
  description: Creates a Merchant Center sub-account. This method can only be called
    for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounts-post-openapi.md
- name: Content API for Shopping - Delete Account
  x-api-slug: merchantidaccountsaccountid-delete
  description: Deletes a Merchant Center sub-account. This method can only be called
    for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountsaccountid-delete-openapi.md
- name: Content API for Shopping - Get Account
  x-api-slug: merchantidaccountsaccountid-get
  description: 'Retrieves a Merchant Center account. This method can only be called
    for accounts to which the managing account has access: either the managing account
    itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountsaccountid-get-openapi.md
- name: Content API for Shopping - Update Account
  x-api-slug: merchantidaccountsaccountid-patch
  description: 'Updates a Merchant Center account. This method can only be called
    for accounts to which the managing account has access: either the managing account
    itself or sub-accounts if the managing account is a multi-client account. This
    method supports patch semantics.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountsaccountid-patch-openapi.md
- name: Content API for Shopping - Update Account
  x-api-slug: merchantidaccountsaccountid-put
  description: 'Updates a Merchant Center account. This method can only be called
    for accounts to which the managing account has access: either the managing account
    itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountsaccountid-put-openapi.md
- name: Content API for Shopping - Get Account Shipping
  x-api-slug: merchantidaccountshipping-get
  description: Lists the shipping settings of the sub-accounts in your Merchant Center
    account. This method can only be called for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountshipping-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountshipping-get-openapi.md
- name: Content API for Shopping - Get Account Shipping
  x-api-slug: merchantidaccountshippingaccountid-get
  description: 'Retrieves the shipping settings of the account. This method can only
    be called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountshippingaccountid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountshippingaccountid-get-openapi.md
- name: Content API for Shopping - Updat Account Shipping
  x-api-slug: merchantidaccountshippingaccountid-patch
  description: 'Updates the shipping settings of the account. This method can only
    be called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.
    This method supports patch semantics.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountshippingaccountid-patch-openapi.md
- name: Content API for Shopping - Updat Account Shipping
  x-api-slug: merchantidaccountshippingaccountid-put
  description: 'Updates the shipping settings of the account. This method can only
    be called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountshippingaccountid-put-openapi.md
- name: Content API for Shopping - Get Account Status
  x-api-slug: merchantidaccountstatuses-get
  description: Lists the statuses of the sub-accounts in your Merchant Center account.
    This method can only be called for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountstatuses-get-openapi.md
- name: Content API for Shopping - Get Account Status
  x-api-slug: merchantidaccountstatusesaccountid-get
  description: 'Retrieves the status of a Merchant Center account. This method can
    only be called for accounts to which the managing account has access: either the
    managing account itself or sub-accounts if the managing account is a multi-client
    account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccountstatusesaccountid-get-openapi.md
- name: Content API for Shopping - Get Account Taxes
  x-api-slug: merchantidaccounttax-get
  description: Lists the tax settings of the sub-accounts in your Merchant Center
    account. This method can only be called for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounttax-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounttax-get-openapi.md
- name: Content API for Shopping - Get Account Tax
  x-api-slug: merchantidaccounttaxaccountid-get
  description: 'Retrieves the tax settings of the account. This method can only be
    called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounttaxaccountid-get-openapi.md
- name: Content API for Shopping - Update Account Tax
  x-api-slug: merchantidaccounttaxaccountid-patch
  description: 'Updates the tax settings of the account. This method can only be called
    for accounts to which the managing account has access: either the managing account
    itself or sub-accounts if the managing account is a multi-client account. This
    method supports patch semantics.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounttaxaccountid-patch-openapi.md
- name: Content API for Shopping - Update Account Tax
  x-api-slug: merchantidaccounttaxaccountid-put
  description: 'Updates the tax settings of the account. This method can only be called
    for accounts to which the managing account has access: either the managing account
    itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidaccounttaxaccountid-put-openapi.md
- name: Content API for Shopping - Get Data Feeds
  x-api-slug: merchantiddatafeeds-get
  description: Lists the datafeeds in your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeeds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeeds-get-openapi.md
- name: Content API for Shopping - Create Data Feed
  x-api-slug: merchantiddatafeeds-post
  description: Registers a datafeed with your Merchant Center account. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeeds-post-openapi.md
- name: Content API for Shopping - Delete Data Feed
  x-api-slug: merchantiddatafeedsdatafeedid-delete
  description: Deletes a datafeed from your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-delete-openapi.md
- name: Content API for Shopping - Get Data Feed
  x-api-slug: merchantiddatafeedsdatafeedid-get
  description: Retrieves a datafeed from your Merchant Center account. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-get-openapi.md
- name: Content API for Shopping - Update Data Feed
  x-api-slug: merchantiddatafeedsdatafeedid-patch
  description: Updates a datafeed of your Merchant Center account. This method can
    only be called for non-multi-client accounts. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-patch-openapi.md
- name: Content API for Shopping - Update Data Feed
  x-api-slug: merchantiddatafeedsdatafeedid-put
  description: Updates a datafeed of your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-put-openapi.md
- name: Content API for Shopping - Get Data Feed Status
  x-api-slug: merchantiddatafeedstatuses-get
  description: Lists the statuses of the datafeeds in your Merchant Center account.
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedstatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedstatuses-get-openapi.md
- name: Content API for Shopping - Get Data Feed Status
  x-api-slug: merchantiddatafeedstatusesdatafeedid-get
  description: Retrieves the status of a datafeed from your Merchant Center account.
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedstatusesdatafeedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantiddatafeedstatusesdatafeedid-get-openapi.md
- name: Content API for Shopping - Update Price
  x-api-slug: merchantidinventorystorecodeproductsproductid-post
  description: Updates price and availability of a product in your Merchant Center
    account. This operation does not update the expiration date of the product. This
    method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidinventorystorecodeproductsproductid-post-openapi.md
- name: Content API for Shopping - Get Orders
  x-api-slug: merchantidorders-get
  description: Lists the orders in your Merchant Center account. This method can only
    be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidorders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidorders-get-openapi.md
- name: Content API for Shopping - Get Order
  x-api-slug: merchantidordersorderid-get
  description: Retrieves an order from your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderid-get-openapi.md
- name: Content API for Shopping - Acknowledge Order
  x-api-slug: merchantidordersorderidacknowledge-post
  description: Marks an order as acknowledged. This method can only be called for
    non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidacknowledge-post-openapi.md
- name: Content API for Shopping - Cancel Order
  x-api-slug: merchantidordersorderidcancel-post
  description: Cancels all line items in an order. This method can only be called
    for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidcancel-post-openapi.md
- name: Content API for Shopping - Cancel Order Line Item
  x-api-slug: merchantidordersorderidcancellineitem-post
  description: Cancels a line item. This method can only be called for non-multi-client
    accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidcancellineitem-post-openapi.md
- name: Content API for Shopping - Refund Order
  x-api-slug: merchantidordersorderidrefund-post
  description: Refund a portion of the order, up to the full amount paid. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidrefund-post-openapi.md
- name: Content API for Shopping - Return Line Item
  x-api-slug: merchantidordersorderidreturnlineitem-post
  description: Returns a line item. This method can only be called for non-multi-client
    accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidreturnlineitem-post-openapi.md
- name: Content API for Shopping - Ship Line Item
  x-api-slug: merchantidordersorderidshiplineitems-post
  description: Marks line item(s) as shipped. This method can only be called for non-multi-client
    accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidshiplineitems-post-openapi.md
- name: Content API for Shopping - Update Merchant Order ID
  x-api-slug: merchantidordersorderidupdatemerchantorderid-post
  description: Updates the merchant order ID for a given order. This method can only
    be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidupdatemerchantorderid-post-openapi.md
- name: Content API for Shopping - Update order Shippment
  x-api-slug: merchantidordersorderidupdateshipment-post
  description: Updates a shipment's status, carrier, and/or tracking ID. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersorderidupdateshipment-post-openapi.md
- name: Content API for Shopping - Get Order
  x-api-slug: merchantidordersbymerchantidmerchantorderid-get
  description: Retrieves an order using merchant order id. This method can only be
    called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidordersbymerchantidmerchantorderid-get-openapi.md
- name: Content API for Shopping - Get Prudcts
  x-api-slug: merchantidproducts-get
  description: Lists the products in your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidproducts-get-openapi.md
- name: Content API for Shopping - Upload Product
  x-api-slug: merchantidproducts-post
  description: Uploads a product to your Merchant Center account. If an item with
    the same channel, contentLanguage, offerId, and targetCountry already exists,
    this method updates that entry. This method can only be called for non-multi-client
    accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidproducts-post-openapi.md
- name: Content API for Shopping - Delete Product
  x-api-slug: merchantidproductsproductid-delete
  description: Deletes a product from your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidproductsproductid-delete-openapi.md
- name: Content API for Shopping - Get Product
  x-api-slug: merchantidproductsproductid-get
  description: Retrieves a product from your Merchant Center account. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidproductsproductid-get-openapi.md
- name: Content API for Shopping - Get Product Status
  x-api-slug: merchantidproductstatuses-get
  description: Lists the statuses of the products in your Merchant Center account.
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidproductstatuses-get-openapi.md
- name: Content API for Shopping - Get Product Status
  x-api-slug: merchantidproductstatusesproductid-get
  description: Gets the status of a product from your Merchant Center account. This
    method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidproductstatusesproductid-get-openapi.md
- name: Content API for Shopping - Get Shipping Settings
  x-api-slug: merchantidshippingsettings-get
  description: Lists the shipping settings of the sub-accounts in your Merchant Center
    account. This method can only be called for multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidshippingsettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidshippingsettings-get-openapi.md
- name: Content API for Shopping - Get Shipping Settings
  x-api-slug: merchantidshippingsettingsaccountid-get
  description: 'Retrieves the shipping settings of the account. This method can only
    be called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidshippingsettingsaccountid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidshippingsettingsaccountid-get-openapi.md
- name: Content API for Shopping - Update Shipping Settings
  x-api-slug: merchantidshippingsettingsaccountid-patch
  description: 'Updates the shipping settings of the account. This method can only
    be called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.
    This method supports patch semantics.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidshippingsettingsaccountid-patch-openapi.md
- name: Content API for Shopping - Update Shipping Settings
  x-api-slug: merchantidshippingsettingsaccountid-put
  description: 'Updates the shipping settings of the account. This method can only
    be called for accounts to which the managing account has access: either the managing
    account itself or sub-accounts if the managing account is a multi-client account.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidshippingsettingsaccountid-put-openapi.md
- name: Content API for Shopping - Get Supported Carriers
  x-api-slug: merchantidsupportedcarriers-get
  description: Retrieves supported carriers and carrier services for an account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidsupportedcarriers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidsupportedcarriers-get-openapi.md
- name: Content API for Shopping - Create Test Order
  x-api-slug: merchantidtestorders-post
  description: Sandbox only. Creates a test order. This method can only be called
    for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidtestorders-post-openapi.md
- name: Content API for Shopping - Update Test Order
  x-api-slug: merchantidtestordersorderidadvance-post
  description: Sandbox only. Moves a test order from state "inProgress" to state "pendingShipment".
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidtestordersorderidadvance-post-openapi.md
- name: Content API for Shopping - Get Test Order
  x-api-slug: merchantidtestordertemplatestemplatename-get
  description: Sandbox only. Retrieves an order template that can be used to quickly
    create a new order in sandbox. This method can only be called for non-multi-client
    accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-content-api-for-shopping/master/_listings/google-content-api-for-shopping/merchantidtestordertemplatestemplatename-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.container.engine.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.content.api.for.shopping.stack.network
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