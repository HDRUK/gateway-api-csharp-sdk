# GatewayApiSdk.Api.ProgrammingLanguageApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Ac545f07640e752592440f34e55b1ed3**](ProgrammingLanguageApi.md#ac545f07640e752592440f34e55b1ed3) | **POST** /api/v1/programming_languages | ProgrammingLanguage@store |
| [**Ac75502b12db43904eeea0400eb245d8**](ProgrammingLanguageApi.md#ac75502b12db43904eeea0400eb245d8) | **GET** /api/v1/programming_languages | ProgrammingLanguage@index |
| [**B50ca1696491e4e1ff3cc267fa7e71ee**](ProgrammingLanguageApi.md#b50ca1696491e4e1ff3cc267fa7e71ee) | **GET** /api/v1/programming_languages/{id} | ProgrammingLanguage@show |
| [**Call00f9ccd45119f11eb3044b4d61f9e79d**](ProgrammingLanguageApi.md#call00f9ccd45119f11eb3044b4d61f9e79d) | **DELETE** /api/v1/programming_languages/{id} | ProgrammingLanguage@destroy |
| [**Call9a975e45459cd2614334b378875d3108**](ProgrammingLanguageApi.md#call9a975e45459cd2614334b378875d3108) | **PATCH** /api/v1/programming_languages/{id} | ProgrammingLanguage@update |
| [**F65686cb0c089366a7c7f67bf528c957**](ProgrammingLanguageApi.md#f65686cb0c089366a7c7f67bf528c957) | **PUT** /api/v1/programming_languages/{id} | ProgrammingLanguage@update |

<a id="ac545f07640e752592440f34e55b1ed3"></a>
# **Ac545f07640e752592440f34e55b1ed3**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Ac545f07640e752592440f34e55b1ed3 (Dd76b8d73b7ea8b4951f03d7c0904c92Request dd76b8d73b7ea8b4951f03d7c0904c92Request)

ProgrammingLanguage@store

Creates a new system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **dd76b8d73b7ea8b4951f03d7c0904c92Request** | [**Dd76b8d73b7ea8b4951f03d7c0904c92Request**](Dd76b8d73b7ea8b4951f03d7c0904c92Request.md) | Programming language definition |  |

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

<a id="ac75502b12db43904eeea0400eb245d8"></a>
# **Ac75502b12db43904eeea0400eb245d8**
> Ac75502b12db43904eeea0400eb245d8200Response Ac75502b12db43904eeea0400eb245d8 ()

ProgrammingLanguage@index

Returns a list of programming languages enabled on the system


### Parameters
This endpoint does not need any parameter.
### Return type

[**Ac75502b12db43904eeea0400eb245d8200Response**](Ac75502b12db43904eeea0400eb245d8200Response.md)

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

<a id="b50ca1696491e4e1ff3cc267fa7e71ee"></a>
# **B50ca1696491e4e1ff3cc267fa7e71ee**
> B50ca1696491e4e1ff3cc267fa7e71ee200Response B50ca1696491e4e1ff3cc267fa7e71ee (int id)

ProgrammingLanguage@show

Return a single system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming language id |  |

### Return type

[**B50ca1696491e4e1ff3cc267fa7e71ee200Response**](B50ca1696491e4e1ff3cc267fa7e71ee200Response.md)

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

<a id="call00f9ccd45119f11eb3044b4d61f9e79d"></a>
# **Call00f9ccd45119f11eb3044b4d61f9e79d**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call00f9ccd45119f11eb3044b4d61f9e79d (int id)

ProgrammingLanguage@destroy

Delete a system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming language id |  |

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

<a id="call9a975e45459cd2614334b378875d3108"></a>
# **Call9a975e45459cd2614334b378875d3108**
> F65686cb0c089366a7c7f67bf528c957200Response Call9a975e45459cd2614334b378875d3108 (int id, A5f6e0a9550d3c58c50dda55412cd051Request a5f6e0a9550d3c58c50dda55412cd051Request)

ProgrammingLanguage@update

Edit a system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming language id |  |
| **a5f6e0a9550d3c58c50dda55412cd051Request** | [**A5f6e0a9550d3c58c50dda55412cd051Request**](A5f6e0a9550d3c58c50dda55412cd051Request.md) | ProgrammingLanguage definition |  |

### Return type

[**F65686cb0c089366a7c7f67bf528c957200Response**](F65686cb0c089366a7c7f67bf528c957200Response.md)

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

<a id="f65686cb0c089366a7c7f67bf528c957"></a>
# **F65686cb0c089366a7c7f67bf528c957**
> F65686cb0c089366a7c7f67bf528c957200Response F65686cb0c089366a7c7f67bf528c957 (int id, Model988e8695bc991d7f8e40131db5ba7a76Request model988e8695bc991d7f8e40131db5ba7a76Request)

ProgrammingLanguage@update

Update a system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming language id |  |
| **model988e8695bc991d7f8e40131db5ba7a76Request** | [**Model988e8695bc991d7f8e40131db5ba7a76Request**](Model988e8695bc991d7f8e40131db5ba7a76Request.md) | ProgrammingLanguage definition |  |

### Return type

[**F65686cb0c089366a7c7f67bf528c957200Response**](F65686cb0c089366a7c7f67bf528c957200Response.md)

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

