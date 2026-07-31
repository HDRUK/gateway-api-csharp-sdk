# GatewayApiSdk.Api.SearchDataUsesApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call8db417727e7fe7c2e99206b060a3b882**](SearchDataUsesApi.md#call8db417727e7fe7c2e99206b060a3b882) | **POST** /api/v1/search/dur | Search@data_uses |

<a id="call8db417727e7fe7c2e99206b060a3b882"></a>
# **Call8db417727e7fe7c2e99206b060a3b882**
> Model8db417727e7fe7c2e99206b060a3b882200Response Call8db417727e7fe7c2e99206b060a3b882 (Model8db417727e7fe7c2e99206b060a3b882Request model8db417727e7fe7c2e99206b060a3b882Request, string sort = null, string direction = null, bool download = null)

Search@data_uses

Returns gateway data uses related to the provided query term(s)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model8db417727e7fe7c2e99206b060a3b882Request** | [**Model8db417727e7fe7c2e99206b060a3b882Request**](Model8db417727e7fe7c2e99206b060a3b882Request.md) | Submit search query |  |
| **sort** | **string** | Field to sort by (default: &#39;score&#39;) | [optional]  |
| **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | [optional]  |
| **download** | **bool** | Download a csv of the results (default: false) | [optional]  |

### Return type

[**Model8db417727e7fe7c2e99206b060a3b882200Response**](Model8db417727e7fe7c2e99206b060a3b882200Response.md)

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

