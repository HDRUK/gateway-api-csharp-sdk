# GatewayApiSdk.Api.DataProviderCollApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**FetchDataProviderColl**](DataProviderCollApi.md#fetchdataprovidercoll) | **GET** /api/v1/data_provider_colls/{id} | DataProviderColl@show |
| [**FetchDataProviderCollSummary**](DataProviderCollApi.md#fetchdataprovidercollsummary) | **GET** /api/v1/data_provider_colls/{id}/summary | DataProviderColl@showSummary |
| [**FetchDataProviderColls**](DataProviderCollApi.md#fetchdataprovidercolls) | **GET** /api/v1/data_provider_colls | DataProviderColl@index |

<a id="fetchdataprovidercoll"></a>
# **FetchDataProviderColl**
> FetchDataProviderColl200Response FetchDataProviderColl (int id)

DataProviderColl@show

Return a single DataProviderColl


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataProviderColl ID |  |

### Return type

[**FetchDataProviderColl200Response**](FetchDataProviderColl200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdataprovidercollsummary"></a>
# **FetchDataProviderCollSummary**
> FetchDataProviderCollSummary200Response FetchDataProviderCollSummary (int id)

DataProviderColl@showSummary

Return a single DataProviderColl - summary


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataProviderColl ID - summary |  |

### Return type

[**FetchDataProviderCollSummary200Response**](FetchDataProviderCollSummary200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdataprovidercolls"></a>
# **FetchDataProviderColls**
> FetchDataProviderColls200Response FetchDataProviderColls (int perPage = null)

DataProviderColl@index

Returns a list of DataProviderColls enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | per page | [optional]  |

### Return type

[**FetchDataProviderColls200Response**](FetchDataProviderColls200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

