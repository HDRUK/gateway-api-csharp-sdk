# GatewayApiSdk.Api.KeywordApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**C144e4dec467e0666f1a6eb1b905a080**](KeywordApi.md#c144e4dec467e0666f1a6eb1b905a080) | **DELETE** /api/v1/keywords/{id} | KeywordController@destroy |
| [**Call5e7d6f311632134045864947649b04d4**](KeywordApi.md#call5e7d6f311632134045864947649b04d4) | **PATCH** /api/v1/keywords/{id} | KeywordController@update |
| [**D59dbdaa4244200f6b9060e166e337d9**](KeywordApi.md#d59dbdaa4244200f6b9060e166e337d9) | **GET** /api/v1/keywords | KeywordController@index |
| [**Ec00b8619507d4ac62cec63eb9684501**](KeywordApi.md#ec00b8619507d4ac62cec63eb9684501) | **POST** /api/v1/keywords | KeywordController@store |
| [**F2450127ddd5aa4ad77c822ba256e01a**](KeywordApi.md#f2450127ddd5aa4ad77c822ba256e01a) | **PUT** /api/v1/keywords/{id} | KeywordController@update |
| [**Faadd5f355273c0ee61ef48436d03ded**](KeywordApi.md#faadd5f355273c0ee61ef48436d03ded) | **GET** /api/v1/keywords/{id} | KeywordController@show |

<a id="c144e4dec467e0666f1a6eb1b905a080"></a>
# **C144e4dec467e0666f1a6eb1b905a080**
> C29b5b3424f7317b69b4bda048ccfafb200Response C144e4dec467e0666f1a6eb1b905a080 (int id)

KeywordController@destroy

Delete a keyword by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | keyword id |  |

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

<a id="call5e7d6f311632134045864947649b04d4"></a>
# **Call5e7d6f311632134045864947649b04d4**
> F2450127ddd5aa4ad77c822ba256e01a200Response Call5e7d6f311632134045864947649b04d4 (int id, A5f6e0a9550d3c58c50dda55412cd051Request a5f6e0a9550d3c58c50dda55412cd051Request)

KeywordController@update

Edit a keyword by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | keyword id |  |
| **a5f6e0a9550d3c58c50dda55412cd051Request** | [**A5f6e0a9550d3c58c50dda55412cd051Request**](A5f6e0a9550d3c58c50dda55412cd051Request.md) | Category definition |  |

### Return type

[**F2450127ddd5aa4ad77c822ba256e01a200Response**](F2450127ddd5aa4ad77c822ba256e01a200Response.md)

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

<a id="d59dbdaa4244200f6b9060e166e337d9"></a>
# **D59dbdaa4244200f6b9060e166e337d9**
> D59dbdaa4244200f6b9060e166e337d9200Response D59dbdaa4244200f6b9060e166e337d9 (int perPage = null)

KeywordController@index

Returns a list of keywords


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | Alternative output schema version. | [optional]  |

### Return type

[**D59dbdaa4244200f6b9060e166e337d9200Response**](D59dbdaa4244200f6b9060e166e337d9200Response.md)

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

<a id="ec00b8619507d4ac62cec63eb9684501"></a>
# **Ec00b8619507d4ac62cec63eb9684501**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Ec00b8619507d4ac62cec63eb9684501 (Dd76b8d73b7ea8b4951f03d7c0904c92Request dd76b8d73b7ea8b4951f03d7c0904c92Request)

KeywordController@store

Creates a new keyword


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **dd76b8d73b7ea8b4951f03d7c0904c92Request** | [**Dd76b8d73b7ea8b4951f03d7c0904c92Request**](Dd76b8d73b7ea8b4951f03d7c0904c92Request.md) | Keyword definition |  |

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
| **409** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="f2450127ddd5aa4ad77c822ba256e01a"></a>
# **F2450127ddd5aa4ad77c822ba256e01a**
> F2450127ddd5aa4ad77c822ba256e01a200Response F2450127ddd5aa4ad77c822ba256e01a (int id, Model988e8695bc991d7f8e40131db5ba7a76Request model988e8695bc991d7f8e40131db5ba7a76Request)

KeywordController@update

Update a keyword by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | keyword id |  |
| **model988e8695bc991d7f8e40131db5ba7a76Request** | [**Model988e8695bc991d7f8e40131db5ba7a76Request**](Model988e8695bc991d7f8e40131db5ba7a76Request.md) | Keyword definition |  |

### Return type

[**F2450127ddd5aa4ad77c822ba256e01a200Response**](F2450127ddd5aa4ad77c822ba256e01a200Response.md)

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

<a id="faadd5f355273c0ee61ef48436d03ded"></a>
# **Faadd5f355273c0ee61ef48436d03ded**
> Faadd5f355273c0ee61ef48436d03ded200Response Faadd5f355273c0ee61ef48436d03ded (int id)

KeywordController@show

Return a single keyword


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | keyword id |  |

### Return type

[**Faadd5f355273c0ee61ef48436d03ded200Response**](Faadd5f355273c0ee61ef48436d03ded200Response.md)

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

