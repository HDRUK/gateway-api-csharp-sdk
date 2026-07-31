# GatewayApiSdk.Api.SearchDataUsesApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**SearchDataUses**](SearchDataUsesApi.md#searchdatauses) | **POST** /api/v1/search/dur | Search@data_uses |

<a id="searchdatauses"></a>
# **SearchDataUses**
> SearchDataUses200Response SearchDataUses (SearchDataUsesRequest searchDataUsesRequest, string sort = null, string direction = null, bool download = null)

Search@data_uses

Returns gateway data uses related to the provided query term(s)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **searchDataUsesRequest** | [**SearchDataUsesRequest**](SearchDataUsesRequest.md) | Submit search query |  |
| **sort** | **string** | Field to sort by (default: &#39;score&#39;) | [optional]  |
| **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | [optional]  |
| **download** | **bool** | Download a csv of the results (default: false) | [optional]  |

### Return type

[**SearchDataUses200Response**](SearchDataUses200Response.md)

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

