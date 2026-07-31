# GatewayApiSdk.Api.AdminDataCustodianNetworksApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**FetchAdminDataCustodianNetworks**](AdminDataCustodianNetworksApi.md#fetchadmindatacustodiannetworks) | **GET** /api/v2/admin/data_custodian_networks | DataCustodianNetworks@adminIndex |

<a id="fetchadmindatacustodiannetworks"></a>
# **FetchAdminDataCustodianNetworks**
> void FetchAdminDataCustodianNetworks (int perPage = null)

DataCustodianNetworks@adminIndex

Superadmin-only listing used by the network management admin screen — unlike index(), this is not filtered to enabled=1, so disabled networks remain visible/manageable.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | per page | [optional]  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

