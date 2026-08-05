# GatewayApiSdk.Api.DataProviderCollApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateDataProviderColl**](DataProviderCollApi.md#createdataprovidercoll) | **POST** /api/v1/data_provider_colls | DataProviderColl@store |
| [**DeleteDataProviderColl**](DataProviderCollApi.md#deletedataprovidercoll) | **DELETE** /api/v1/data_provider_colls/{id} | DataProviderColl@destroy |
| [**EditDataProviderColl**](DataProviderCollApi.md#editdataprovidercoll) | **PATCH** /api/v1/data_provider_colls/{id} | DataProviderColl@edit |
| [**FetchDataProviderColl**](DataProviderCollApi.md#fetchdataprovidercoll) | **GET** /api/v1/data_provider_colls/{id} | DataProviderColl@show |
| [**FetchDataProviderCollSummary**](DataProviderCollApi.md#fetchdataprovidercollsummary) | **GET** /api/v1/data_provider_colls/{id}/summary | DataProviderColl@showSummary |
| [**FetchDataProviderColls**](DataProviderCollApi.md#fetchdataprovidercolls) | **GET** /api/v1/data_provider_colls | DataProviderColl@index |
| [**UpdateDataProviderColl**](DataProviderCollApi.md#updatedataprovidercoll) | **PUT** /api/v1/data_provider_colls/{id} | DataProviderColl@update |

<a id="createdataprovidercoll"></a>
# **CreateDataProviderColl**
> CreateDarIntegration201Response CreateDataProviderColl (CreateDataProviderCollRequest createDataProviderCollRequest)

DataProviderColl@store

Creates a new DataProviderColl


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createDataProviderCollRequest** | [**CreateDataProviderCollRequest**](CreateDataProviderCollRequest.md) | DataProviderColl definition |  |

### Return type

[**CreateDarIntegration201Response**](CreateDarIntegration201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletedataprovidercoll"></a>
# **DeleteDataProviderColl**
> DeleteApplications200Response DeleteDataProviderColl (int id)

DataProviderColl@destroy

Delete a DataProviderColl


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataProviderColl ID |  |

### Return type

[**DeleteApplications200Response**](DeleteApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **404** | Not found response |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="editdataprovidercoll"></a>
# **EditDataProviderColl**
> UpdateDataProviderColl200Response EditDataProviderColl (int id, EditDataProviderCollRequest editDataProviderCollRequest)

DataProviderColl@edit

Edit a DataProviderColl


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataProviderColl ID |  |
| **editDataProviderCollRequest** | [**EditDataProviderCollRequest**](EditDataProviderCollRequest.md) | DataProviderColl definition |  |

### Return type

[**UpdateDataProviderColl200Response**](UpdateDataProviderColl200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **404** | Not found response |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

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

<a id="updatedataprovidercoll"></a>
# **UpdateDataProviderColl**
> UpdateDataProviderColl200Response UpdateDataProviderColl (int id, UpdateDataProviderCollRequest updateDataProviderCollRequest)

DataProviderColl@update

Update a DataProviderColl


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataProviderColl ID |  |
| **updateDataProviderCollRequest** | [**UpdateDataProviderCollRequest**](UpdateDataProviderCollRequest.md) | DataProviderColl definition |  |

### Return type

[**UpdateDataProviderColl200Response**](UpdateDataProviderColl200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **404** | Not found response |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

