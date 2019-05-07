# ![LOGO](logo.png) Machine Learning Workspaces Management Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Machine Learning Workspaces Management Client API (version 2016-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/machinelearning-workspaces/2016-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:19+03:00

## API Description

These APIs allow end users to operate on Azure Machine Learning Workspace resources. They support CRUD operations for Azure Machine Learning Workspaces.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Azure Machine Learning Studio REST API operations.

*Tags:* `Operation`

#### Input Parameters
* `api-version` - _required_ - The client API version.

### Lists all the available machine learning workspaces under the specified subscription.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.

### Lists all the available machine learning workspaces under the specified resource group.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning workspace belongs.

### Deletes a machine learning workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning workspace belongs.
* `workspaceName` - _required_ - The name of the machine learning workspace.

### Gets the properties of the specified machine learning workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning workspace belongs.
* `workspaceName` - _required_ - The name of the machine learning workspace.

### Updates a machine learning workspace with the specified parameters.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning workspace belongs.
* `workspaceName` - _required_ - The name of the machine learning workspace.

### Creates or updates a workspace with the specified parameters.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning workspace belongs.
* `workspaceName` - _required_ - The name of the machine learning workspace.

### List the authorization keys associated with this workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `workspaceName` - _required_ - The name of the machine learning workspace.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning workspace belongs.

### Resync storage keys associated with this workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `workspaceName` - _required_ - The name of the machine learning workspace.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning workspace belongs.

## License

**flow**ground :- Telekom iPaaS / azure-com-machinelearning-workspaces-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
