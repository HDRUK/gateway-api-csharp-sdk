# GatewayApiSdk.Api.DataProviderCollApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**C5bb5300d6a46cc5b1b6a3bb1c3fa869**](DataProviderCollApi.md#c5bb5300d6a46cc5b1b6a3bb1c3fa869) | **PUT** /api/v1/data_provider_colls/{id} | DataProviderColl@update |
| [**Call02ada355a680c816624e98ae028dc8b6**](DataProviderCollApi.md#call02ada355a680c816624e98ae028dc8b6) | **POST** /api/v1/data_provider_colls | DataProviderColl@store |
| [**Call08f75648c437bdf2ba9f66d0c1371d0c**](DataProviderCollApi.md#call08f75648c437bdf2ba9f66d0c1371d0c) | **GET** /api/v1/data_provider_colls/{id} | DataProviderColl@show |
| [**Call3351120ae1ae550ab36ee958b1feaf48**](DataProviderCollApi.md#call3351120ae1ae550ab36ee958b1feaf48) | **DELETE** /api/v1/data_provider_colls/{id} | DataProviderColl@destroy |
| [**Call81b552b8803870790579d840279ce8a3**](DataProviderCollApi.md#call81b552b8803870790579d840279ce8a3) | **PATCH** /api/v1/data_provider_colls/{id} | DataProviderColl@edit |
| [**D0fe0e1c60dd979135440e3e0b440b75**](DataProviderCollApi.md#d0fe0e1c60dd979135440e3e0b440b75) | **GET** /api/v1/data_provider_colls | DataProviderColl@index |
| [**Ed769d8210100bbcd0e3a11660d25dc0**](DataProviderCollApi.md#ed769d8210100bbcd0e3a11660d25dc0) | **GET** /api/v1/data_provider_colls/{id}/summary | DataProviderColl@showSummary |

<a id="c5bb5300d6a46cc5b1b6a3bb1c3fa869"></a>
# **C5bb5300d6a46cc5b1b6a3bb1c3fa869**
> C5bb5300d6a46cc5b1b6a3bb1c3fa869200Response C5bb5300d6a46cc5b1b6a3bb1c3fa869 (int id, C5bb5300d6a46cc5b1b6a3bb1c3fa869Request c5bb5300d6a46cc5b1b6a3bb1c3fa869Request)

DataProviderColl@update

Update a DataProviderColl


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataProviderColl ID |  |
| **c5bb5300d6a46cc5b1b6a3bb1c3fa869Request** | [**C5bb5300d6a46cc5b1b6a3bb1c3fa869Request**](C5bb5300d6a46cc5b1b6a3bb1c3fa869Request.md) | DataProviderColl definition |  |

### Return type

[**C5bb5300d6a46cc5b1b6a3bb1c3fa869200Response**](C5bb5300d6a46cc5b1b6a3bb1c3fa869200Response.md)

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

<a id="call02ada355a680c816624e98ae028dc8b6"></a>
# **Call02ada355a680c816624e98ae028dc8b6**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Call02ada355a680c816624e98ae028dc8b6 (Model02ada355a680c816624e98ae028dc8b6Request model02ada355a680c816624e98ae028dc8b6Request)

DataProviderColl@store

Creates a new DataProviderColl


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model02ada355a680c816624e98ae028dc8b6Request** | [**Model02ada355a680c816624e98ae028dc8b6Request**](Model02ada355a680c816624e98ae028dc8b6Request.md) | DataProviderColl definition |  |

### Return type

[**Dd76b8d73b7ea8b4951f03d7c0904c92200Response**](Dd76b8d73b7ea8b4951f03d7c0904c92200Response.md)

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

<a id="call08f75648c437bdf2ba9f66d0c1371d0c"></a>
# **Call08f75648c437bdf2ba9f66d0c1371d0c**
> Model08f75648c437bdf2ba9f66d0c1371d0c200Response Call08f75648c437bdf2ba9f66d0c1371d0c (int id)

DataProviderColl@show

Return a single DataProviderColl


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataProviderColl ID |  |

### Return type

[**Model08f75648c437bdf2ba9f66d0c1371d0c200Response**](Model08f75648c437bdf2ba9f66d0c1371d0c200Response.md)

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

<a id="call3351120ae1ae550ab36ee958b1feaf48"></a>
# **Call3351120ae1ae550ab36ee958b1feaf48**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call3351120ae1ae550ab36ee958b1feaf48 (int id)

DataProviderColl@destroy

Delete a DataProviderColl


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataProviderColl ID |  |

### Return type

[**C29b5b3424f7317b69b4bda048ccfafb200Response**](C29b5b3424f7317b69b4bda048ccfafb200Response.md)

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

<a id="call81b552b8803870790579d840279ce8a3"></a>
# **Call81b552b8803870790579d840279ce8a3**
> C5bb5300d6a46cc5b1b6a3bb1c3fa869200Response Call81b552b8803870790579d840279ce8a3 (int id, Model81b552b8803870790579d840279ce8a3Request model81b552b8803870790579d840279ce8a3Request)

DataProviderColl@edit

Edit a DataProviderColl


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataProviderColl ID |  |
| **model81b552b8803870790579d840279ce8a3Request** | [**Model81b552b8803870790579d840279ce8a3Request**](Model81b552b8803870790579d840279ce8a3Request.md) | DataProviderColl definition |  |

### Return type

[**C5bb5300d6a46cc5b1b6a3bb1c3fa869200Response**](C5bb5300d6a46cc5b1b6a3bb1c3fa869200Response.md)

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

<a id="d0fe0e1c60dd979135440e3e0b440b75"></a>
# **D0fe0e1c60dd979135440e3e0b440b75**
> D0fe0e1c60dd979135440e3e0b440b75200Response D0fe0e1c60dd979135440e3e0b440b75 (int perPage = null)

DataProviderColl@index

Returns a list of DataProviderColls enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | per page | [optional]  |

### Return type

[**D0fe0e1c60dd979135440e3e0b440b75200Response**](D0fe0e1c60dd979135440e3e0b440b75200Response.md)

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

<a id="ed769d8210100bbcd0e3a11660d25dc0"></a>
# **Ed769d8210100bbcd0e3a11660d25dc0**
> Ed769d8210100bbcd0e3a11660d25dc0200Response Ed769d8210100bbcd0e3a11660d25dc0 (int id)

DataProviderColl@showSummary

Return a single DataProviderColl - summary


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataProviderColl ID - summary |  |

### Return type

[**Ed769d8210100bbcd0e3a11660d25dc0200Response**](Ed769d8210100bbcd0e3a11660d25dc0200Response.md)

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

