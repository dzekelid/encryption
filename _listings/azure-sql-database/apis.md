---
name: Azure SQL Database
description: Make building and maintaining applications easier and more productive.
  With built-in intelligence that learns app patterns and adapts to maximize performance,
  reliability, and data protection, SQL Database is a cloud database built for developers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Microsoft
- Database
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/encryption/master/_listings/azure-sql-database/apis.yaml
specificationVersion: "0.14"
apis:
- name: Azure SQL Database API
  description: Make building and maintaining applications easier and more productive
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: ""
  baseURL: ://management.azure.com//
  tags: Encryption
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/encryption/master/_listings/azure-sql-database/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-sql-servers-servername-databases-databasename-transparentdataencryption-current-operationresults-get.md
- name: Azure SQL Database API Databases List Transparent Data Encryption Activity
  description: Returns a database's transparent data encryption operation result.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: http:://management.azure.com//
  tags: Encryption
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/encryption/master/_listings/azure-sql-database/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-sql-servers-servername-databases-databasename-transparentdataencryption-current-operationresults-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/encryption/master/_listings/azure-sql-database/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-sql-servers-servername-databases-databasename-transparentdataencryption-current-operationresults-get-postman.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/sql-database/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/sql-database/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/sql-database/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/sql-database/
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/sql-database/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/sql-database/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/sql-database/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/sql-database/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---