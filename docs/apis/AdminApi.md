# GatewayApiSdk.Api.AdminApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**RevokeAllTokensV2**](AdminApi.md#revokealltokensv2) | **POST** /api/v2/admin/tokens/revoke_all | TokenRevocationController@revokeAll |

<a id="revokealltokensv2"></a>
# **RevokeAllTokensV2**
> RevokeAllTokensV2200Response RevokeAllTokensV2 ()

TokenRevocationController@revokeAll

Revoke every Gateway JWT issued up to now, including the caller's own. All users must sign in again.


### Parameters
This endpoint does not need any parameter.
### Return type

[**RevokeAllTokensV2200Response**](RevokeAllTokensV2200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

