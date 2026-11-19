# GatewayApiSdk.Api.SearchSimilarDatasetsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**SearchSimilarDatasets**](SearchSimilarDatasetsApi.md#searchsimilardatasets) | **POST** /api/v1/search/similar/datasets | Search for similar datasets (deprecated) |
| [**SearchSimilarDatasetsV2**](SearchSimilarDatasetsApi.md#searchsimilardatasetsv2) | **POST** /api/v2/search/similar/datasets | Search for similar datasets |

<a id="searchsimilardatasets"></a>
# **SearchSimilarDatasets**
> void SearchSimilarDatasets (SearchSimilarDatasetsV2Request searchSimilarDatasetsV2Request)

Search for similar datasets (deprecated)

Deprecated: use /api/v2/search/similar/datasets, which this endpoint now serves. Responses carry Deprecation, Sunset and Link headers; it stops working after the Sunset date (17 May 2027).


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **searchSimilarDatasetsV2Request** | [**SearchSimilarDatasetsV2Request**](SearchSimilarDatasetsV2Request.md) |  |  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Same as /api/v2/search/similar/datasets |  -  |
| **400** | Missing or invalid dataset id |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="searchsimilardatasetsv2"></a>
# **SearchSimilarDatasetsV2**
> SearchSimilarDatasetsV2200Response SearchSimilarDatasetsV2 (SearchSimilarDatasetsV2Request searchSimilarDatasetsV2Request)

Search for similar datasets

Returns up to three gateway datasets sharing the most terms with the provided dataset's keywords and title. The provided dataset is never included.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **searchSimilarDatasetsV2Request** | [**SearchSimilarDatasetsV2Request**](SearchSimilarDatasetsV2Request.md) |  |  |

### Return type

[**SearchSimilarDatasetsV2200Response**](SearchSimilarDatasetsV2200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success; empty data when the dataset is not indexed |  -  |
| **400** | Missing or invalid dataset id |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

