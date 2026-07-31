# GatewayApiSdk.Api.SearchCollectionsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Aa33edfdace17b70600d964e0db4d44b**](SearchCollectionsApi.md#aa33edfdace17b70600d964e0db4d44b) | **POST** /api/v1/search/collections | Search@collections |

<a id="aa33edfdace17b70600d964e0db4d44b"></a>
# **Aa33edfdace17b70600d964e0db4d44b**
> Aa33edfdace17b70600d964e0db4d44b200Response Aa33edfdace17b70600d964e0db4d44b (Aa33edfdace17b70600d964e0db4d44bRequest aa33edfdace17b70600d964e0db4d44bRequest, string sort = null, string direction = null)

Search@collections

Returns gateway collections related to the provided query term(s)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **aa33edfdace17b70600d964e0db4d44bRequest** | [**Aa33edfdace17b70600d964e0db4d44bRequest**](Aa33edfdace17b70600d964e0db4d44bRequest.md) | Submit search query |  |
| **sort** | **string** | Field to sort by (default: &#39;score&#39;) | [optional]  |
| **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | [optional]  |

### Return type

[**Aa33edfdace17b70600d964e0db4d44b200Response**](Aa33edfdace17b70600d964e0db4d44b200Response.md)

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

