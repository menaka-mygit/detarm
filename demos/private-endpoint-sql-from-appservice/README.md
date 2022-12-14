---
description: This template shows how to create a Web app that consumes a private endpoint pointing to Azure SQL Server
page_type: sample
products:
- azure
- azure-resource-manager
urlFragment: private-endpoint-sql-from-appservice
languages:
- json
---
# WebApp consuming a Azure SQL Private Endpoint

![Azure Public Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/demos/private-endpoint-sql-from-appservice/PublicLastTestDate.svg)
![Azure Public Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/demos/private-endpoint-sql-from-appservice/PublicDeployment.svg)

![Azure US Gov Last Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/demos/private-endpoint-sql-from-appservice/FairfaxLastTestDate.svg)
![Azure US Gov Last Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/demos/private-endpoint-sql-from-appservice/FairfaxDeployment.svg)

![Best Practice Check](https://azurequickstartsservice.blob.core.windows.net/badges/demos/private-endpoint-sql-from-appservice/BestPracticeResult.svg)
![Cred Scan Check](https://azurequickstartsservice.blob.core.windows.net/badges/demos/private-endpoint-sql-from-appservice/CredScanResult.svg)

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fdemos%2Fprivate-endpoint-sql-from-appservice%2Fazuredeploy.json)

[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fdemos%2Fprivate-endpoint-sql-from-appservice%2Fazuredeploy.json)

This is a starter template that shows how to consume an Azure SQL private endpoint from a web app

## Architecture Diagram

![architecture diagram](images/webappsqlpvtlink.png)

## Notes

[Azure Private Link FAQ](https://docs.microsoft.com/azure/private-link/private-link-faq)

[Private link endpoints template format](https://docs.microsoft.com/azure/templates/microsoft.network/2020-04-01/privateendpoints)

`Tags: Microsoft.Sql/servers, Microsoft.Sql/servers/databases, Microsoft.Network/virtualNetworks, Microsoft.Network/privateEndpoints, Microsoft.Network/privateDnsZones, Microsoft.Network/privateDnsZones/virtualNetworkLinks, Microsoft.Network/privateEndpoints/privateDnsZoneGroups, Microsoft.Web/serverfarms, Microsoft.Web/sites, SQLAzure, config, extensions, networkConfig`
