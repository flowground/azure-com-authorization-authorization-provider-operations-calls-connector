# ![LOGO](logo.png) AuthorizationManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the AuthorizationManagementClient API (version 2018-01-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/authorization-authorization-ProviderOperationsCalls/2018-01-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:16+03:00

## API Description

Role based access control provides you a way to apply granular level policy administration down to individual resources or resource groups. These calls handle provider operations.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets provider operations metadata for all resource providers.

*Tags:* `ProviderOperationsMetadata`

#### Input Parameters
* `api-version` - _required_ - The API version to use for this operation.
* `$expand` - _optional_ - Specifies whether to expand the values.

### Gets provider operations metadata for the specified resource provider.

*Tags:* `ProviderOperationsMetadata`

#### Input Parameters
* `resourceProviderNamespace` - _required_ - The namespace of the resource provider.
* `api-version` - _required_ - The API version to use for this operation.
* `$expand` - _optional_ - Specifies whether to expand the values.

## License

**flow**ground :- Telekom iPaaS / azure-com-authorization-authorization-provider-operations-calls-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
