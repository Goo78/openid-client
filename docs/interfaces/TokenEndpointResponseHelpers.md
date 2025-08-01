# Interface: TokenEndpointResponseHelpers

[💗 Help the project](https://github.com/sponsors/panva)

Support from the community to continue maintaining and improving this module is welcome. If you find the module useful, please consider supporting the project by [becoming a sponsor](https://github.com/sponsors/panva).

***

Helpers attached to any resolved [TokenEndpointResponse](TokenEndpointResponse.md)

## Methods

### claims()

▸ **claims**(): `undefined` \| [`IDToken`](IDToken.md)

Returns the parsed JWT Claims Set of an
[id\_token](TokenEndpointResponse.md#id_token) returned by the
authorization server

> [!NOTE]\
> Returns `undefined` when [id\_token](TokenEndpointResponse.md#id_token) was
> not returned by the authorization server

#### Returns

`undefined` \| [`IDToken`](IDToken.md)

***

### expiresIn()

▸ **expiresIn**(): `undefined` \| `number`

Returns the number of seconds until the
[access\_token](TokenEndpointResponse.md#access_token) expires

> [!NOTE]\
> Returns `0` when already expired

> [!NOTE]\
> Returns `undefined` when [expires\_in](TokenEndpointResponse.md#expires_in)
> was not returned by the authorization server

#### Returns

`undefined` \| `number`
