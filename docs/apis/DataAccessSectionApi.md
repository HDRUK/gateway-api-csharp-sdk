# GatewayApiSdk.Api.DataAccessSectionApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call0df3660c2b63970f84f9beec8a6c334e**](DataAccessSectionApi.md#call0df3660c2b63970f84f9beec8a6c334e) | **DELETE** /api/v1/dar/sections/{id} | DataAccessSection@destroy |
| [**Call22b4daa2ab6ab3638657b9f6eee22316**](DataAccessSectionApi.md#call22b4daa2ab6ab3638657b9f6eee22316) | **PUT** /api/v1/dar/sections/{id} | DataAccessSection@update |
| [**Call24bb1d73f780293f012cbc187f5448f3**](DataAccessSectionApi.md#call24bb1d73f780293f012cbc187f5448f3) | **POST** /api/v1/dar/sections | DataAccessSection@store |
| [**Call2935b32e38ac989b35eab8e0b7552cd3**](DataAccessSectionApi.md#call2935b32e38ac989b35eab8e0b7552cd3) | **PATCH** /api/v1/dar/sections/{id} | DataAccessSection@update |
| [**Call94f1c18e47daa32c1346be4a0d0449e4**](DataAccessSectionApi.md#call94f1c18e47daa32c1346be4a0d0449e4) | **GET** /api/v1/dar/sections | DataAccessSection@index |
| [**Fc0e1e343f76b10d80b2332ca24fbfe0**](DataAccessSectionApi.md#fc0e1e343f76b10d80b2332ca24fbfe0) | **GET** /api/v1/dar/sections/{id} | DataAccessSection@show |

<a id="call0df3660c2b63970f84f9beec8a6c334e"></a>
# **Call0df3660c2b63970f84f9beec8a6c334e**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call0df3660c2b63970f84f9beec8a6c334e (int id)

DataAccessSection@destroy

Delete a system DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR section id |  |

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

<a id="call22b4daa2ab6ab3638657b9f6eee22316"></a>
# **Call22b4daa2ab6ab3638657b9f6eee22316**
> Fc0e1e343f76b10d80b2332ca24fbfe0200Response Call22b4daa2ab6ab3638657b9f6eee22316 (int id, Model24bb1d73f780293f012cbc187f5448f3Request model24bb1d73f780293f012cbc187f5448f3Request)

DataAccessSection@update

Update a system DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR section id |  |
| **model24bb1d73f780293f012cbc187f5448f3Request** | [**Model24bb1d73f780293f012cbc187f5448f3Request**](Model24bb1d73f780293f012cbc187f5448f3Request.md) | DataAccessSection definition |  |

### Return type

[**Fc0e1e343f76b10d80b2332ca24fbfe0200Response**](Fc0e1e343f76b10d80b2332ca24fbfe0200Response.md)

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

<a id="call24bb1d73f780293f012cbc187f5448f3"></a>
# **Call24bb1d73f780293f012cbc187f5448f3**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Call24bb1d73f780293f012cbc187f5448f3 (Model24bb1d73f780293f012cbc187f5448f3Request model24bb1d73f780293f012cbc187f5448f3Request)

DataAccessSection@store

Creates a new DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model24bb1d73f780293f012cbc187f5448f3Request** | [**Model24bb1d73f780293f012cbc187f5448f3Request**](Model24bb1d73f780293f012cbc187f5448f3Request.md) | DataAccessSection definition |  |

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

<a id="call2935b32e38ac989b35eab8e0b7552cd3"></a>
# **Call2935b32e38ac989b35eab8e0b7552cd3**
> Fc0e1e343f76b10d80b2332ca24fbfe0200Response Call2935b32e38ac989b35eab8e0b7552cd3 (int id, Model2935b32e38ac989b35eab8e0b7552cd3Request model2935b32e38ac989b35eab8e0b7552cd3Request)

DataAccessSection@update

Edit a system DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR section id |  |
| **model2935b32e38ac989b35eab8e0b7552cd3Request** | [**Model2935b32e38ac989b35eab8e0b7552cd3Request**](Model2935b32e38ac989b35eab8e0b7552cd3Request.md) | DataAccessSection definition |  |

### Return type

[**Fc0e1e343f76b10d80b2332ca24fbfe0200Response**](Fc0e1e343f76b10d80b2332ca24fbfe0200Response.md)

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

<a id="call94f1c18e47daa32c1346be4a0d0449e4"></a>
# **Call94f1c18e47daa32c1346be4a0d0449e4**
> Model94f1c18e47daa32c1346be4a0d0449e4200Response Call94f1c18e47daa32c1346be4a0d0449e4 (int perPage = null)

DataAccessSection@index

List of DAR sections


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | per page | [optional]  |

### Return type

[**Model94f1c18e47daa32c1346be4a0d0449e4200Response**](Model94f1c18e47daa32c1346be4a0d0449e4200Response.md)

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

<a id="fc0e1e343f76b10d80b2332ca24fbfe0"></a>
# **Fc0e1e343f76b10d80b2332ca24fbfe0**
> Fc0e1e343f76b10d80b2332ca24fbfe0200Response Fc0e1e343f76b10d80b2332ca24fbfe0 (int id)

DataAccessSection@show

Return a single DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR section id |  |

### Return type

[**Fc0e1e343f76b10d80b2332ca24fbfe0200Response**](Fc0e1e343f76b10d80b2332ca24fbfe0200Response.md)

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

