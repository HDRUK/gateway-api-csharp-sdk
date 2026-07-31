# GatewayApiSdk.Api.SearchDataCustodiansApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Ada26698c9cdc86c01aaf53b0677a48d**](SearchDataCustodiansApi.md#ada26698c9cdc86c01aaf53b0677a48d) | **POST** /api/v1/search/data_custodians | Search@data_custodians |

<a id="ada26698c9cdc86c01aaf53b0677a48d"></a>
# **Ada26698c9cdc86c01aaf53b0677a48d**
> Ada26698c9cdc86c01aaf53b0677a48d200Response Ada26698c9cdc86c01aaf53b0677a48d (Ada26698c9cdc86c01aaf53b0677a48dRequest ada26698c9cdc86c01aaf53b0677a48dRequest, string sort = null, string direction = null, int perPage = null)

Search@data_custodians

Returns gateway data custodians related to the provided query term(s)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **ada26698c9cdc86c01aaf53b0677a48dRequest** | [**Ada26698c9cdc86c01aaf53b0677a48dRequest**](Ada26698c9cdc86c01aaf53b0677a48dRequest.md) | Submit search query |  |
| **sort** | **string** | Field to sort by (default: &#39;score&#39;) | [optional]  |
| **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | [optional]  |
| **perPage** | **int** | Number of results to return per page | [optional]  |

### Return type

[**Ada26698c9cdc86c01aaf53b0677a48d200Response**](Ada26698c9cdc86c01aaf53b0677a48d200Response.md)

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

