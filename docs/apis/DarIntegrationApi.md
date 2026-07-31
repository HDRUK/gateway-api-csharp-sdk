# GatewayApiSdk.Api.DarIntegrationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**C663ccf8b1926d7678370d095b9b358f**](DarIntegrationApi.md#c663ccf8b1926d7678370d095b9b358f) | **PATCH** /api/v1/dar-integration/{id} | DarIntegration@edit |
| [**Call09c033f0336380c3d8bb6801e96378bc**](DarIntegrationApi.md#call09c033f0336380c3d8bb6801e96378bc) | **PUT** /api/v1/dar-integration/{id} | DarIntegration@update |
| [**Call17fa1074b71d9cefd3e65f2757117b57**](DarIntegrationApi.md#call17fa1074b71d9cefd3e65f2757117b57) | **DELETE** /api/v1/dar-integrations/{id} | DarIntegration@destroy |
| [**Call406144045c21a19659ee66f6d4a78235**](DarIntegrationApi.md#call406144045c21a19659ee66f6d4a78235) | **GET** /api/v1/dar-integration/{id} | DarIntegration@show |
| [**Call757fd0f4616caa763b0789d7ad7b3053**](DarIntegrationApi.md#call757fd0f4616caa763b0789d7ad7b3053) | **POST** /api/v1/dar-integration/{id} | DarIntegration@store |
| [**Call7ab50add4fe0a4b7cff7eab0f4b8df18**](DarIntegrationApi.md#call7ab50add4fe0a4b7cff7eab0f4b8df18) | **GET** /api/v1/dar-integration | DarIntegration@index |

<a id="c663ccf8b1926d7678370d095b9b358f"></a>
# **C663ccf8b1926d7678370d095b9b358f**
> Model09c033f0336380c3d8bb6801e96378bc200Response C663ccf8b1926d7678370d095b9b358f (int id, C663ccf8b1926d7678370d095b9b358fRequest c663ccf8b1926d7678370d095b9b358fRequest)

DarIntegration@edit

Edit a DAR integration enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dar integration id |  |
| **c663ccf8b1926d7678370d095b9b358fRequest** | [**C663ccf8b1926d7678370d095b9b358fRequest**](C663ccf8b1926d7678370d095b9b358fRequest.md) | DarIntegration definition |  |

### Return type

[**Model09c033f0336380c3d8bb6801e96378bc200Response**](Model09c033f0336380c3d8bb6801e96378bc200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Updated |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call09c033f0336380c3d8bb6801e96378bc"></a>
# **Call09c033f0336380c3d8bb6801e96378bc**
> Model09c033f0336380c3d8bb6801e96378bc200Response Call09c033f0336380c3d8bb6801e96378bc (int id, Model09c033f0336380c3d8bb6801e96378bcRequest model09c033f0336380c3d8bb6801e96378bcRequest)

DarIntegration@update

Updates a DAR integration enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dar integration id |  |
| **model09c033f0336380c3d8bb6801e96378bcRequest** | [**Model09c033f0336380c3d8bb6801e96378bcRequest**](Model09c033f0336380c3d8bb6801e96378bcRequest.md) | DarIntegration definition |  |

### Return type

[**Model09c033f0336380c3d8bb6801e96378bc200Response**](Model09c033f0336380c3d8bb6801e96378bc200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Updated |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call17fa1074b71d9cefd3e65f2757117b57"></a>
# **Call17fa1074b71d9cefd3e65f2757117b57**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call17fa1074b71d9cefd3e65f2757117b57 (int id)

DarIntegration@destroy

Delete a system Dar Integration


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dar integration id |  |

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

<a id="call406144045c21a19659ee66f6d4a78235"></a>
# **Call406144045c21a19659ee66f6d4a78235**
> Model7ab50add4fe0a4b7cff7eab0f4b8df18200ResponseDataInner Call406144045c21a19659ee66f6d4a78235 (int id)

DarIntegration@show

Returns a single DAR integration enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dar integration id |  |

### Return type

[**Model7ab50add4fe0a4b7cff7eab0f4b8df18200ResponseDataInner**](Model7ab50add4fe0a4b7cff7eab0f4b8df18200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call757fd0f4616caa763b0789d7ad7b3053"></a>
# **Call757fd0f4616caa763b0789d7ad7b3053**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Call757fd0f4616caa763b0789d7ad7b3053 (int id, Model09c033f0336380c3d8bb6801e96378bcRequest model09c033f0336380c3d8bb6801e96378bcRequest)

DarIntegration@store

Creates a new DAR integration enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dar integration id |  |
| **model09c033f0336380c3d8bb6801e96378bcRequest** | [**Model09c033f0336380c3d8bb6801e96378bcRequest**](Model09c033f0336380c3d8bb6801e96378bcRequest.md) | DarIntegration definition |  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call7ab50add4fe0a4b7cff7eab0f4b8df18"></a>
# **Call7ab50add4fe0a4b7cff7eab0f4b8df18**
> Model7ab50add4fe0a4b7cff7eab0f4b8df18200Response Call7ab50add4fe0a4b7cff7eab0f4b8df18 ()

DarIntegration@index

Returns a list of DAR integrations enabled on the system


### Parameters
This endpoint does not need any parameter.
### Return type

[**Model7ab50add4fe0a4b7cff7eab0f4b8df18200Response**](Model7ab50add4fe0a4b7cff7eab0f4b8df18200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

