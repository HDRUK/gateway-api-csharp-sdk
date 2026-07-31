# GatewayApiSdk.Api.SearchPublicationsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**SearchPublications**](SearchPublicationsApi.md#searchpublications) | **POST** /api/v1/search/publications | Search@publications |
| [**SearchPublicationsByDoi**](SearchPublicationsApi.md#searchpublicationsbydoi) | **POST** /api/v1/search/doi | Search@publications |

<a id="searchpublications"></a>
# **SearchPublications**
> SearchPublications200Response SearchPublications (SearchPublicationsRequest searchPublicationsRequest, string sort = null, string direction = null, string source = null)

Search@publications

Returns gateway publications related to the provided query term(s)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **searchPublicationsRequest** | [**SearchPublicationsRequest**](SearchPublicationsRequest.md) | Submit search query |  |
| **sort** | **string** | Field to sort by (default: &#39;score&#39;) | [optional]  |
| **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | [optional]  |
| **source** | **string** | Which source to search (&#39;GAT&#39; or &#39;FED&#39;, default: &#39;GAT&#39;) | [optional]  |

### Return type

[**SearchPublications200Response**](SearchPublications200Response.md)

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

<a id="searchpublicationsbydoi"></a>
# **SearchPublicationsByDoi**
> SearchPublicationsByDoi200Response SearchPublicationsByDoi (SearchPublicationsByDoiRequest searchPublicationsByDoiRequest)

Search@publications

Returns publications from EuropePMC matching a give DOI


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **searchPublicationsByDoiRequest** | [**SearchPublicationsByDoiRequest**](SearchPublicationsByDoiRequest.md) | Submit search query |  |

### Return type

[**SearchPublicationsByDoi200Response**](SearchPublicationsByDoi200Response.md)

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

