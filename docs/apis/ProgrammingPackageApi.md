# GatewayApiSdk.Api.ProgrammingPackageApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Ad25f9129aefd55435b425747d5a706c**](ProgrammingPackageApi.md#ad25f9129aefd55435b425747d5a706c) | **POST** /api/v1/programming_packages | ProgrammingPackage@store |
| [**Call1aeebba947bfb42f364a2d5dd2ad8ef9**](ProgrammingPackageApi.md#call1aeebba947bfb42f364a2d5dd2ad8ef9) | **PUT** /api/v1/programming_packages/{id} | ProgrammingPackage@update |
| [**Call47ebee1d2e096dcb033d29f4ff244ad4**](ProgrammingPackageApi.md#call47ebee1d2e096dcb033d29f4ff244ad4) | **GET** /api/v1/programming_packages/{id} | ProgrammingPackage@show |
| [**Call6ac98caeb87a37c9286f592834b9c803**](ProgrammingPackageApi.md#call6ac98caeb87a37c9286f592834b9c803) | **GET** /api/v1/programming_packages | ProgrammingPackage@index |
| [**Call879046026ce3997dea0d9bf768f2f8e6**](ProgrammingPackageApi.md#call879046026ce3997dea0d9bf768f2f8e6) | **PATCH** /api/v1/programming_packages/{id} | ProgrammingPackage@update |
| [**Fdbe7e1aad9b02084b06c6d647766efd**](ProgrammingPackageApi.md#fdbe7e1aad9b02084b06c6d647766efd) | **DELETE** /api/v1/programming_packages/{id} | ProgrammingPackage@destroy |

<a id="ad25f9129aefd55435b425747d5a706c"></a>
# **Ad25f9129aefd55435b425747d5a706c**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Ad25f9129aefd55435b425747d5a706c (Dd76b8d73b7ea8b4951f03d7c0904c92Request dd76b8d73b7ea8b4951f03d7c0904c92Request)

ProgrammingPackage@store

Creates a new system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **dd76b8d73b7ea8b4951f03d7c0904c92Request** | [**Dd76b8d73b7ea8b4951f03d7c0904c92Request**](Dd76b8d73b7ea8b4951f03d7c0904c92Request.md) | Programming package definition |  |

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

<a id="call1aeebba947bfb42f364a2d5dd2ad8ef9"></a>
# **Call1aeebba947bfb42f364a2d5dd2ad8ef9**
> Model1aeebba947bfb42f364a2d5dd2ad8ef9200Response Call1aeebba947bfb42f364a2d5dd2ad8ef9 (int id, Model988e8695bc991d7f8e40131db5ba7a76Request model988e8695bc991d7f8e40131db5ba7a76Request)

ProgrammingPackage@update

Update a system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming package id |  |
| **model988e8695bc991d7f8e40131db5ba7a76Request** | [**Model988e8695bc991d7f8e40131db5ba7a76Request**](Model988e8695bc991d7f8e40131db5ba7a76Request.md) | ProgrammingPackage definition |  |

### Return type

[**Model1aeebba947bfb42f364a2d5dd2ad8ef9200Response**](Model1aeebba947bfb42f364a2d5dd2ad8ef9200Response.md)

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

<a id="call47ebee1d2e096dcb033d29f4ff244ad4"></a>
# **Call47ebee1d2e096dcb033d29f4ff244ad4**
> Model47ebee1d2e096dcb033d29f4ff244ad4200Response Call47ebee1d2e096dcb033d29f4ff244ad4 (int id)

ProgrammingPackage@show

Return a single system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming package id |  |

### Return type

[**Model47ebee1d2e096dcb033d29f4ff244ad4200Response**](Model47ebee1d2e096dcb033d29f4ff244ad4200Response.md)

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

<a id="call6ac98caeb87a37c9286f592834b9c803"></a>
# **Call6ac98caeb87a37c9286f592834b9c803**
> Model6ac98caeb87a37c9286f592834b9c803200Response Call6ac98caeb87a37c9286f592834b9c803 ()

ProgrammingPackage@index

Returns a list of programming packages enabled on the system


### Parameters
This endpoint does not need any parameter.
### Return type

[**Model6ac98caeb87a37c9286f592834b9c803200Response**](Model6ac98caeb87a37c9286f592834b9c803200Response.md)

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

<a id="call879046026ce3997dea0d9bf768f2f8e6"></a>
# **Call879046026ce3997dea0d9bf768f2f8e6**
> Model1aeebba947bfb42f364a2d5dd2ad8ef9200Response Call879046026ce3997dea0d9bf768f2f8e6 (int id, A5f6e0a9550d3c58c50dda55412cd051Request a5f6e0a9550d3c58c50dda55412cd051Request)

ProgrammingPackage@update

Edit a system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming package id |  |
| **a5f6e0a9550d3c58c50dda55412cd051Request** | [**A5f6e0a9550d3c58c50dda55412cd051Request**](A5f6e0a9550d3c58c50dda55412cd051Request.md) | ProgrammingPackage definition |  |

### Return type

[**Model1aeebba947bfb42f364a2d5dd2ad8ef9200Response**](Model1aeebba947bfb42f364a2d5dd2ad8ef9200Response.md)

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

<a id="fdbe7e1aad9b02084b06c6d647766efd"></a>
# **Fdbe7e1aad9b02084b06c6d647766efd**
> C29b5b3424f7317b69b4bda048ccfafb200Response Fdbe7e1aad9b02084b06c6d647766efd (int id)

ProgrammingPackage@destroy

Delete a system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming package id |  |

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

