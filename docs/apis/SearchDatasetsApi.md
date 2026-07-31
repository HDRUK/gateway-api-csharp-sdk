# GatewayApiSdk.Api.SearchDatasetsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**SearchDatasets**](SearchDatasetsApi.md#searchdatasets) | **POST** /api/v1/search/datasets | Search@datasets |

<a id="searchdatasets"></a>
# **SearchDatasets**
> SearchDatasets200Response SearchDatasets (SearchDatasetsRequest searchDatasetsRequest)

Search@datasets

Returns gateway datasets related to the provided query term(s)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **searchDatasetsRequest** | [**SearchDatasetsRequest**](SearchDatasetsRequest.md) | Submit search query |  |

### Return type

[**SearchDatasets200Response**](SearchDatasets200Response.md)

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

