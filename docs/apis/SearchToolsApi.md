# GatewayApiSdk.Api.SearchToolsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**SearchTools**](SearchToolsApi.md#searchtools) | **POST** /api/v1/search/tools | Search@tools |

<a id="searchtools"></a>
# **SearchTools**
> SearchTools200Response SearchTools (SearchToolsRequest searchToolsRequest, string sort = null, string direction = null)

Search@tools

Returns gateway tools related to the provided query term(s)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **searchToolsRequest** | [**SearchToolsRequest**](SearchToolsRequest.md) | Submit search query |  |
| **sort** | **string** | Field to sort by (default: &#39;score&#39;) | [optional]  |
| **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | [optional]  |

### Return type

[**SearchTools200Response**](SearchTools200Response.md)

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

