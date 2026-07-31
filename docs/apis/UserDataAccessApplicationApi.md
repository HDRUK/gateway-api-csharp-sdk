# GatewayApiSdk.Api.UserDataAccessApplicationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call02454c833604944c4ab43341c54819b5**](UserDataAccessApplicationApi.md#call02454c833604944c4ab43341c54819b5) | **GET** /api/v1/users/{userId}/dar/applications/count | UserDataAccessApplicationController@allCounts |
| [**Call34fca475ca3526cfda7bd59f33676ca9**](UserDataAccessApplicationApi.md#call34fca475ca3526cfda7bd59f33676ca9) | **GET** /api/v1/users/{userId}/dar/applications/{id} | UserDataAccessApplicationController@show |
| [**Call3ed5d58afc4b6c7bb2d955fa4c0f1671**](UserDataAccessApplicationApi.md#call3ed5d58afc4b6c7bb2d955fa4c0f1671) | **GET** /api/v1/users/{userId}/dar/applications | UserDataAccessApplicationController@index |
| [**Call7090c41ba0c1412e6f1e62c5d9db14ba**](UserDataAccessApplicationApi.md#call7090c41ba0c1412e6f1e62c5d9db14ba) | **GET** /api/v1/users/{userId}/dar/applications/{id}/answers | UserDataAccessApplicationController@showAnswers |
| [**Call7710dee56f16ff46e25d95111beb5ce0**](UserDataAccessApplicationApi.md#call7710dee56f16ff46e25d95111beb5ce0) | **GET** /api/v1/users/{userId}/dar/applications/{id}/showHeader | UserDataAccessApplicationController@showHeader |
| [**Call7753eafda891afa178f7cbff9e66ff10**](UserDataAccessApplicationApi.md#call7753eafda891afa178f7cbff9e66ff10) | **GET** /api/v1/users/{userId}/dar/applications/count/{field} | UserDataAccessApplicationController@count |
| [**D05df7a52fe05d677aa184236d61de56**](UserDataAccessApplicationApi.md#d05df7a52fe05d677aa184236d61de56) | **PUT** /api/v1/users/{userId}/dar/applications/{id}/answers | UserDataAccessApplication@storeAnswers |

<a id="call02454c833604944c4ab43341c54819b5"></a>
# **Call02454c833604944c4ab43341c54819b5**
> CountUniqueFieldsCollections200Response Call02454c833604944c4ab43341c54819b5 (int userId)

UserDataAccessApplicationController@allCounts

Get Counts for all status fields in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |

### Return type

[**CountUniqueFieldsCollections200Response**](CountUniqueFieldsCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call34fca475ca3526cfda7bd59f33676ca9"></a>
# **Call34fca475ca3526cfda7bd59f33676ca9**
> Model4e4d590ec8943163168e4fc34bd166a1200Response Call34fca475ca3526cfda7bd59f33676ca9 (int userId, int id)

UserDataAccessApplicationController@show

Return a DAR application belonging to the user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**Model4e4d590ec8943163168e4fc34bd166a1200Response**](Model4e4d590ec8943163168e4fc34bd166a1200Response.md)

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

<a id="call3ed5d58afc4b6c7bb2d955fa4c0f1671"></a>
# **Call3ed5d58afc4b6c7bb2d955fa4c0f1671**
> Model0ff8ad69b213abf8d671b3695d0b69b5200Response Call3ed5d58afc4b6c7bb2d955fa4c0f1671 (int userId)

UserDataAccessApplicationController@index

List of dar applications belonging to a user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |

### Return type

[**Model0ff8ad69b213abf8d671b3695d0b69b5200Response**](Model0ff8ad69b213abf8d671b3695d0b69b5200Response.md)

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

<a id="call7090c41ba0c1412e6f1e62c5d9db14ba"></a>
# **Call7090c41ba0c1412e6f1e62c5d9db14ba**
> Model473ee45c3962ae2a02abbac5015dce6a200Response Call7090c41ba0c1412e6f1e62c5d9db14ba (int userId, int id)

UserDataAccessApplicationController@showAnswers

Return answers from the user's DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**Model473ee45c3962ae2a02abbac5015dce6a200Response**](Model473ee45c3962ae2a02abbac5015dce6a200Response.md)

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

<a id="call7710dee56f16ff46e25d95111beb5ce0"></a>
# **Call7710dee56f16ff46e25d95111beb5ce0**
> Model4e4d590ec8943163168e4fc34bd166a1200Response Call7710dee56f16ff46e25d95111beb5ce0 (int userId, int id)

UserDataAccessApplicationController@showHeader

Get header information about a specific DAR


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**Model4e4d590ec8943163168e4fc34bd166a1200Response**](Model4e4d590ec8943163168e4fc34bd166a1200Response.md)

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

<a id="call7753eafda891afa178f7cbff9e66ff10"></a>
# **Call7753eafda891afa178f7cbff9e66ff10**
> CountUniqueFieldsCollections200Response Call7753eafda891afa178f7cbff9e66ff10 (int userId, string field)

UserDataAccessApplicationController@count

Get Counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **field** | **string** | name of the field to perform a count on |  |

### Return type

[**CountUniqueFieldsCollections200Response**](CountUniqueFieldsCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="d05df7a52fe05d677aa184236d61de56"></a>
# **D05df7a52fe05d677aa184236d61de56**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response D05df7a52fe05d677aa184236d61de56 (int userId, int id, D05df7a52fe05d677aa184236d61de56Request d05df7a52fe05d677aa184236d61de56Request)

UserDataAccessApplication@storeAnswers

Add answers to the user's DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |
| **d05df7a52fe05d677aa184236d61de56Request** | [**D05df7a52fe05d677aa184236d61de56Request**](D05df7a52fe05d677aa184236d61de56Request.md) | UserDataAccessApplication definition |  |

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

