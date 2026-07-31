# GatewayApiSdk.Api.LibraryApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call077bba41c87bc61e6c290b3fea2a5848**](LibraryApi.md#call077bba41c87bc61e6c290b3fea2a5848) | **PUT** /api/v1/libraries/{id} | Library@update |
| [**Call3b22aa4bb101550915e675702f8f3174**](LibraryApi.md#call3b22aa4bb101550915e675702f8f3174) | **POST** /api/v1/libraries | Library@store |
| [**Call416921483907d62b39163e3c4188d10c**](LibraryApi.md#call416921483907d62b39163e3c4188d10c) | **DELETE** /api/v1/libraries/{id} | Library@destroy |
| [**Call771bea7be0a7f7d2e0056f8c192100ad**](LibraryApi.md#call771bea7be0a7f7d2e0056f8c192100ad) | **PATCH** /api/v1/libraries/{id} | Library@update |
| [**D736d637e675097aaf709dfd755864c7**](LibraryApi.md#d736d637e675097aaf709dfd755864c7) | **GET** /api/v1/libraries/{id} | Return a single library |
| [**ListLibraries**](LibraryApi.md#listlibraries) | **GET** /api/v1/libraries | Retrieve a list of libraries |

<a id="call077bba41c87bc61e6c290b3fea2a5848"></a>
# **Call077bba41c87bc61e6c290b3fea2a5848**
> Model077bba41c87bc61e6c290b3fea2a5848200Response Call077bba41c87bc61e6c290b3fea2a5848 (int id, Model3b22aa4bb101550915e675702f8f3174Request model3b22aa4bb101550915e675702f8f3174Request)

Library@update

Update a library


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | library id |  |
| **model3b22aa4bb101550915e675702f8f3174Request** | [**Model3b22aa4bb101550915e675702f8f3174Request**](Model3b22aa4bb101550915e675702f8f3174Request.md) | library definition |  |

### Return type

[**Model077bba41c87bc61e6c290b3fea2a5848200Response**](Model077bba41c87bc61e6c290b3fea2a5848200Response.md)

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

<a id="call3b22aa4bb101550915e675702f8f3174"></a>
# **Call3b22aa4bb101550915e675702f8f3174**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Call3b22aa4bb101550915e675702f8f3174 (Model3b22aa4bb101550915e675702f8f3174Request model3b22aa4bb101550915e675702f8f3174Request)

Library@store

Creates a new library


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model3b22aa4bb101550915e675702f8f3174Request** | [**Model3b22aa4bb101550915e675702f8f3174Request**](Model3b22aa4bb101550915e675702f8f3174Request.md) | library definition |  |

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

<a id="call416921483907d62b39163e3c4188d10c"></a>
# **Call416921483907d62b39163e3c4188d10c**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call416921483907d62b39163e3c4188d10c (int id)

Library@destroy

Delete a library


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | library id |  |

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

<a id="call771bea7be0a7f7d2e0056f8c192100ad"></a>
# **Call771bea7be0a7f7d2e0056f8c192100ad**
> Model077bba41c87bc61e6c290b3fea2a5848200Response Call771bea7be0a7f7d2e0056f8c192100ad (int id, Model3b22aa4bb101550915e675702f8f3174Request model3b22aa4bb101550915e675702f8f3174Request)

Library@update

Edit a library


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | library id |  |
| **model3b22aa4bb101550915e675702f8f3174Request** | [**Model3b22aa4bb101550915e675702f8f3174Request**](Model3b22aa4bb101550915e675702f8f3174Request.md) | library definition |  |

### Return type

[**Model077bba41c87bc61e6c290b3fea2a5848200Response**](Model077bba41c87bc61e6c290b3fea2a5848200Response.md)

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

<a id="d736d637e675097aaf709dfd755864c7"></a>
# **D736d637e675097aaf709dfd755864c7**
> D736d637e675097aaf709dfd755864c7200Response D736d637e675097aaf709dfd755864c7 (int id)

Return a single library

Return a single library


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | library id |  |

### Return type

[**D736d637e675097aaf709dfd755864c7200Response**](D736d637e675097aaf709dfd755864c7200Response.md)

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

<a id="listlibraries"></a>
# **ListLibraries**
> ListLibraries200Response ListLibraries (int perPage = null)

Retrieve a list of libraries

Returns a paginated list of libraries along with associated datasets and teams.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | Specify the number of libraries per page | [optional] [default to 10] |

### Return type

[**ListLibraries200Response**](ListLibraries200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

