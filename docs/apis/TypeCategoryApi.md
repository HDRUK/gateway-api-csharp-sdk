# GatewayApiSdk.Api.TypeCategoryApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call016393e03d3b197d2172abf0d7ce08f5**](TypeCategoryApi.md#call016393e03d3b197d2172abf0d7ce08f5) | **PUT** /api/v1/type_categories/{id} | TypeCategory@update |
| [**Call4864cc161acae07c9aaf81414fa6bebd**](TypeCategoryApi.md#call4864cc161acae07c9aaf81414fa6bebd) | **DELETE** /api/v1/type_categories/{id} | TypeCategory@destroy |
| [**Call83ae406abb0fb38fa792b4cfcbbbebbf**](TypeCategoryApi.md#call83ae406abb0fb38fa792b4cfcbbbebbf) | **POST** /api/v1/type_categories | TypeCategory@store |
| [**Cd1f252c1f5296d0e6007eb543ef9099**](TypeCategoryApi.md#cd1f252c1f5296d0e6007eb543ef9099) | **GET** /api/v1/type_categories/{id} | TypeCategory@show |
| [**F5f0b860854ee5a33ee3d4b5f8a6d2fc**](TypeCategoryApi.md#f5f0b860854ee5a33ee3d4b5f8a6d2fc) | **GET** /api/v1/type_categories | TypeCategory@index |
| [**Faae0a9813b380e92fba8a26820717ee**](TypeCategoryApi.md#faae0a9813b380e92fba8a26820717ee) | **PATCH** /api/v1/type_categories/{id} | TypeCategory@update |

<a id="call016393e03d3b197d2172abf0d7ce08f5"></a>
# **Call016393e03d3b197d2172abf0d7ce08f5**
> Model016393e03d3b197d2172abf0d7ce08f5200Response Call016393e03d3b197d2172abf0d7ce08f5 (int id, Model016393e03d3b197d2172abf0d7ce08f5Request model016393e03d3b197d2172abf0d7ce08f5Request)

TypeCategory@update

Update a system type category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | type category id |  |
| **model016393e03d3b197d2172abf0d7ce08f5Request** | [**Model016393e03d3b197d2172abf0d7ce08f5Request**](Model016393e03d3b197d2172abf0d7ce08f5Request.md) | TypeCategory definition |  |

### Return type

[**Model016393e03d3b197d2172abf0d7ce08f5200Response**](Model016393e03d3b197d2172abf0d7ce08f5200Response.md)

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

<a id="call4864cc161acae07c9aaf81414fa6bebd"></a>
# **Call4864cc161acae07c9aaf81414fa6bebd**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call4864cc161acae07c9aaf81414fa6bebd (int id)

TypeCategory@destroy

Delete a system type category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | type category id |  |

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

<a id="call83ae406abb0fb38fa792b4cfcbbbebbf"></a>
# **Call83ae406abb0fb38fa792b4cfcbbbebbf**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Call83ae406abb0fb38fa792b4cfcbbbebbf (Model83ae406abb0fb38fa792b4cfcbbbebbfRequest model83ae406abb0fb38fa792b4cfcbbbebbfRequest)

TypeCategory@store

Creates a new system type category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model83ae406abb0fb38fa792b4cfcbbbebbfRequest** | [**Model83ae406abb0fb38fa792b4cfcbbbebbfRequest**](Model83ae406abb0fb38fa792b4cfcbbbebbfRequest.md) | Programming language definition |  |

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

<a id="cd1f252c1f5296d0e6007eb543ef9099"></a>
# **Cd1f252c1f5296d0e6007eb543ef9099**
> Cd1f252c1f5296d0e6007eb543ef9099200Response Cd1f252c1f5296d0e6007eb543ef9099 (int id)

TypeCategory@show

Return a single system type category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | type category id |  |

### Return type

[**Cd1f252c1f5296d0e6007eb543ef9099200Response**](Cd1f252c1f5296d0e6007eb543ef9099200Response.md)

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

<a id="f5f0b860854ee5a33ee3d4b5f8a6d2fc"></a>
# **F5f0b860854ee5a33ee3d4b5f8a6d2fc**
> F5f0b860854ee5a33ee3d4b5f8a6d2fc200Response F5f0b860854ee5a33ee3d4b5f8a6d2fc ()

TypeCategory@index

Returns a list of type categories enabled on the system


### Parameters
This endpoint does not need any parameter.
### Return type

[**F5f0b860854ee5a33ee3d4b5f8a6d2fc200Response**](F5f0b860854ee5a33ee3d4b5f8a6d2fc200Response.md)

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

<a id="faae0a9813b380e92fba8a26820717ee"></a>
# **Faae0a9813b380e92fba8a26820717ee**
> Model016393e03d3b197d2172abf0d7ce08f5200Response Faae0a9813b380e92fba8a26820717ee (int id, A5f6e0a9550d3c58c50dda55412cd051Request a5f6e0a9550d3c58c50dda55412cd051Request)

TypeCategory@update

Edit a system type category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | type category id |  |
| **a5f6e0a9550d3c58c50dda55412cd051Request** | [**A5f6e0a9550d3c58c50dda55412cd051Request**](A5f6e0a9550d3c58c50dda55412cd051Request.md) | TypeCategory definition |  |

### Return type

[**Model016393e03d3b197d2172abf0d7ce08f5200Response**](Model016393e03d3b197d2172abf0d7ce08f5200Response.md)

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

