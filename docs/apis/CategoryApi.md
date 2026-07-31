# GatewayApiSdk.Api.CategoryApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**A5f6e0a9550d3c58c50dda55412cd051**](CategoryApi.md#a5f6e0a9550d3c58c50dda55412cd051) | **PATCH** /api/v1/categories/{id} | Category@update |
| [**Call37196d259228d2274dd9dbef8b00e547**](CategoryApi.md#call37196d259228d2274dd9dbef8b00e547) | **DELETE** /api/v1/categories/{id} | Category@destroy |
| [**Call988e8695bc991d7f8e40131db5ba7a76**](CategoryApi.md#call988e8695bc991d7f8e40131db5ba7a76) | **PUT** /api/v1/categories/{id} | Category@update |
| [**Call9c4934d1b68a6d4440ec72cfc8ae7074**](CategoryApi.md#call9c4934d1b68a6d4440ec72cfc8ae7074) | **GET** /api/v1/categories/{id} | Category@show |
| [**Dd76b8d73b7ea8b4951f03d7c0904c92**](CategoryApi.md#dd76b8d73b7ea8b4951f03d7c0904c92) | **POST** /api/v1/categories | Category@store |
| [**E225c2b7eb5daf7fb16e00f4f07ff030**](CategoryApi.md#e225c2b7eb5daf7fb16e00f4f07ff030) | **GET** /api/v1/categories | Category@index |

<a id="a5f6e0a9550d3c58c50dda55412cd051"></a>
# **A5f6e0a9550d3c58c50dda55412cd051**
> Model988e8695bc991d7f8e40131db5ba7a76200Response A5f6e0a9550d3c58c50dda55412cd051 (int id, A5f6e0a9550d3c58c50dda55412cd051Request a5f6e0a9550d3c58c50dda55412cd051Request)

Category@update

Edit a tool category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | category id |  |
| **a5f6e0a9550d3c58c50dda55412cd051Request** | [**A5f6e0a9550d3c58c50dda55412cd051Request**](A5f6e0a9550d3c58c50dda55412cd051Request.md) | Category definition |  |

### Return type

[**Model988e8695bc991d7f8e40131db5ba7a76200Response**](Model988e8695bc991d7f8e40131db5ba7a76200Response.md)

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

<a id="call37196d259228d2274dd9dbef8b00e547"></a>
# **Call37196d259228d2274dd9dbef8b00e547**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call37196d259228d2274dd9dbef8b00e547 (int id)

Category@destroy

Delete a tool category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | category id |  |

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

<a id="call988e8695bc991d7f8e40131db5ba7a76"></a>
# **Call988e8695bc991d7f8e40131db5ba7a76**
> Model988e8695bc991d7f8e40131db5ba7a76200Response Call988e8695bc991d7f8e40131db5ba7a76 (int id, Model988e8695bc991d7f8e40131db5ba7a76Request model988e8695bc991d7f8e40131db5ba7a76Request)

Category@update

Update a tool category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | category id |  |
| **model988e8695bc991d7f8e40131db5ba7a76Request** | [**Model988e8695bc991d7f8e40131db5ba7a76Request**](Model988e8695bc991d7f8e40131db5ba7a76Request.md) | Category definition |  |

### Return type

[**Model988e8695bc991d7f8e40131db5ba7a76200Response**](Model988e8695bc991d7f8e40131db5ba7a76200Response.md)

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

<a id="call9c4934d1b68a6d4440ec72cfc8ae7074"></a>
# **Call9c4934d1b68a6d4440ec72cfc8ae7074**
> E225c2b7eb5daf7fb16e00f4f07ff030200Response Call9c4934d1b68a6d4440ec72cfc8ae7074 (int id)

Category@show

Return a single tool category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | category id |  |

### Return type

[**E225c2b7eb5daf7fb16e00f4f07ff030200Response**](E225c2b7eb5daf7fb16e00f4f07ff030200Response.md)

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

<a id="dd76b8d73b7ea8b4951f03d7c0904c92"></a>
# **Dd76b8d73b7ea8b4951f03d7c0904c92**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Dd76b8d73b7ea8b4951f03d7c0904c92 (Dd76b8d73b7ea8b4951f03d7c0904c92Request dd76b8d73b7ea8b4951f03d7c0904c92Request)

Category@store

Creates a new tool category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **dd76b8d73b7ea8b4951f03d7c0904c92Request** | [**Dd76b8d73b7ea8b4951f03d7c0904c92Request**](Dd76b8d73b7ea8b4951f03d7c0904c92Request.md) | Category definition |  |

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

<a id="e225c2b7eb5daf7fb16e00f4f07ff030"></a>
# **E225c2b7eb5daf7fb16e00f4f07ff030**
> E225c2b7eb5daf7fb16e00f4f07ff030200Response E225c2b7eb5daf7fb16e00f4f07ff030 (int perPage = null)

Category@index

Returns a list of categories enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | per page | [optional]  |

### Return type

[**E225c2b7eb5daf7fb16e00f4f07ff030200Response**](E225c2b7eb5daf7fb16e00f4f07ff030200Response.md)

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

