# ![LOGO](logo.png) RecoveryServicesClient **flow**ground Connector

## Description

A generated **flow**ground connector for the RecoveryServicesClient API (version 2016-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/recoveryservices-vaults/2016-06-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:38+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns the list of available operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Fetches all the resources of the specified type in the subscription.

*Tags:* `Vaults`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.

### Retrieve a list of Vaults.

*Tags:* `Vaults`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.

### Deletes a vault.

*Tags:* `Vaults`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.

### Get the Vault details.

*Tags:* `Vaults`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.

### Updates the vault.

*Tags:* `Vaults`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.

### Creates or updates a Recovery Services vault.

*Tags:* `Vaults`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.

### Get the vault extended info.

*Tags:* `VaultExtendedInfo`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.

### Update vault extended info.

*Tags:* `VaultExtendedInfo`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.
* `api-version` - _required_ - Client Api Version.

### Create vault extended info.

*Tags:* `VaultExtendedInfo`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-recoveryservices-vaults-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
