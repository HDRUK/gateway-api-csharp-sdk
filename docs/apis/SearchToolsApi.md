# GatewayApiSdk.Api.SearchToolsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**A3e02b5a05b56708998c4bd96935d5f5**](SearchToolsApi.md#a3e02b5a05b56708998c4bd96935d5f5) | **POST** /api/v1/search/tools | Search@tools |

<a id="a3e02b5a05b56708998c4bd96935d5f5"></a>
# **A3e02b5a05b56708998c4bd96935d5f5**
> A3e02b5a05b56708998c4bd96935d5f5200Response A3e02b5a05b56708998c4bd96935d5f5 (A3e02b5a05b56708998c4bd96935d5f5Request a3e02b5a05b56708998c4bd96935d5f5Request, string sort = null, string direction = null)

Search@tools

Returns gateway tools related to the provided query term(s)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **a3e02b5a05b56708998c4bd96935d5f5Request** | [**A3e02b5a05b56708998c4bd96935d5f5Request**](A3e02b5a05b56708998c4bd96935d5f5Request.md) | Submit search query |  |
| **sort** | **string** | Field to sort by (default: &#39;score&#39;) | [optional]  |
| **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | [optional]  |

### Return type

[**A3e02b5a05b56708998c4bd96935d5f5200Response**](A3e02b5a05b56708998c4bd96935d5f5200Response.md)

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

