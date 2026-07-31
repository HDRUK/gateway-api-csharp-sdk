# GatewayApiSdk.Api.SearchDataCustodiansApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**SearchDataCustodians**](SearchDataCustodiansApi.md#searchdatacustodians) | **POST** /api/v1/search/data_custodians | Search@data_custodians |

<a id="searchdatacustodians"></a>
# **SearchDataCustodians**
> SearchDataCustodians200Response SearchDataCustodians (SearchDataCustodiansRequest searchDataCustodiansRequest, string sort = null, string direction = null, int perPage = null)

Search@data_custodians

Returns gateway data custodians related to the provided query term(s)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **searchDataCustodiansRequest** | [**SearchDataCustodiansRequest**](SearchDataCustodiansRequest.md) | Submit search query |  |
| **sort** | **string** | Field to sort by (default: &#39;score&#39;) | [optional]  |
| **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | [optional]  |
| **perPage** | **int** | Number of results to return per page | [optional]  |

### Return type

[**SearchDataCustodians200Response**](SearchDataCustodians200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

