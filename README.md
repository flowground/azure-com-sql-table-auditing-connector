# ![LOGO](logo.png) SqlManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SqlManagementClient API (version 2014-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-tableAuditing/2014-04-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:30+03:00

## API Description

The Azure SQL Database management API provides a RESTful set of web APIs that interact with Azure SQL Database services to manage your databases. The API enables users to create, retrieve, update, and delete databases, servers, and other entities.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists a server's table auditing policies. Table auditing is deprecated, use blob auditing instead.

*Tags:* `TableAuditing`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a server's table auditing policy. Table auditing is deprecated, use blob auditing instead.

*Tags:* `TableAuditing`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `tableAuditingPolicyName` - _required_ - The name of the table auditing policy.
    Possible values: default.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Creates or updates a server's table auditing policy. Table auditing is deprecated, use blob auditing instead.

*Tags:* `TableAuditing`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `tableAuditingPolicyName` - _required_ - The name of the table auditing policy.
    Possible values: default.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Lists a database's table auditing policies. Table auditing is deprecated, use blob auditing instead.

*Tags:* `TableAuditing`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database for which the table audit policy is defined.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a database's table auditing policy. Table auditing is deprecated, use blob auditing instead.

*Tags:* `TableAuditing`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database for which the table audit policy is defined.
* `tableAuditingPolicyName` - _required_ - The name of the table auditing policy.
    Possible values: default.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Creates or updates a database's table auditing policy. Table auditing is deprecated, use blob auditing instead.

*Tags:* `TableAuditing`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database for which the table auditing policy will be defined.
* `tableAuditingPolicyName` - _required_ - The name of the table auditing policy.
    Possible values: default.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a database's connection policy, which is used with table auditing. Table auditing is deprecated, use blob auditing instead.

*Tags:* `TableAuditing`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database for which the connection policy is defined.
* `connectionPolicyName` - _required_ - The name of the connection policy.
    Possible values: default.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Creates or updates a database's connection policy, which is used with table auditing. Table auditing is deprecated, use blob auditing instead.

*Tags:* `TableAuditing`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database for which the connection policy will be defined.
* `connectionPolicyName` - _required_ - The name of the connection policy.
    Possible values: default.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-table-auditing-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
