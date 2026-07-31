# GatewayApiSdk.Api.SearchSimilarDatasetsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**SearchSimilarDatasets**](SearchSimilarDatasetsApi.md#searchsimilardatasets) | **POST** /api/v1/search/similar/datasets | Search@similarDatasets |

<a id="searchsimilardatasets"></a>
# **SearchSimilarDatasets**
> SearchSimilarDatasets200Response SearchSimilarDatasets (SearchSimilarDatasetsRequest searchSimilarDatasetsRequest)

Search@similarDatasets

Returns top three gateway datasets most similar to the provided dataset


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **searchSimilarDatasetsRequest** | [**SearchSimilarDatasetsRequest**](SearchSimilarDatasetsRequest.md) | Submit dataset id |  |

### Return type

[**SearchSimilarDatasets200Response**](SearchSimilarDatasets200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

