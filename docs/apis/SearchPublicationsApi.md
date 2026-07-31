# GatewayApiSdk.Api.SearchPublicationsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call9946399cbddb0dcadcbd5801e5ee1dd4**](SearchPublicationsApi.md#call9946399cbddb0dcadcbd5801e5ee1dd4) | **POST** /api/v1/search/publications | Search@publications |
| [**Call9a0abfa6186327d43c51259d5b524fde**](SearchPublicationsApi.md#call9a0abfa6186327d43c51259d5b524fde) | **POST** /api/v1/search/doi | Search@publications |

<a id="call9946399cbddb0dcadcbd5801e5ee1dd4"></a>
# **Call9946399cbddb0dcadcbd5801e5ee1dd4**
> Model9946399cbddb0dcadcbd5801e5ee1dd4200Response Call9946399cbddb0dcadcbd5801e5ee1dd4 (Model9946399cbddb0dcadcbd5801e5ee1dd4Request model9946399cbddb0dcadcbd5801e5ee1dd4Request, string sort = null, string direction = null, string source = null)

Search@publications

Returns gateway publications related to the provided query term(s)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model9946399cbddb0dcadcbd5801e5ee1dd4Request** | [**Model9946399cbddb0dcadcbd5801e5ee1dd4Request**](Model9946399cbddb0dcadcbd5801e5ee1dd4Request.md) | Submit search query |  |
| **sort** | **string** | Field to sort by (default: &#39;score&#39;) | [optional]  |
| **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | [optional]  |
| **source** | **string** | Which source to search (&#39;GAT&#39; or &#39;FED&#39;, default: &#39;GAT&#39;) | [optional]  |

### Return type

[**Model9946399cbddb0dcadcbd5801e5ee1dd4200Response**](Model9946399cbddb0dcadcbd5801e5ee1dd4200Response.md)

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

<a id="call9a0abfa6186327d43c51259d5b524fde"></a>
# **Call9a0abfa6186327d43c51259d5b524fde**
> Model9a0abfa6186327d43c51259d5b524fde200Response Call9a0abfa6186327d43c51259d5b524fde (Model9a0abfa6186327d43c51259d5b524fdeRequest model9a0abfa6186327d43c51259d5b524fdeRequest)

Search@publications

Returns publications from EuropePMC matching a give DOI


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model9a0abfa6186327d43c51259d5b524fdeRequest** | [**Model9a0abfa6186327d43c51259d5b524fdeRequest**](Model9a0abfa6186327d43c51259d5b524fdeRequest.md) | Submit search query |  |

### Return type

[**Model9a0abfa6186327d43c51259d5b524fde200Response**](Model9a0abfa6186327d43c51259d5b524fde200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **204** | No match found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

