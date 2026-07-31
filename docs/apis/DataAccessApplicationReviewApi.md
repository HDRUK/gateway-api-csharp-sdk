# GatewayApiSdk.Api.DataAccessApplicationReviewApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Bdc71807f7e3ab85967e343d06f95228**](DataAccessApplicationReviewApi.md#bdc71807f7e3ab85967e343d06f95228) | **POST** /api/v1/teams/{team_id}/dar/applications/{id}/questions/{questionId}/reviews | DataAccessApplicationReview@store |
| [**Call05c982367b9c911ca1ec6d6352fa23fe**](DataAccessApplicationReviewApi.md#call05c982367b9c911ca1ec6d6352fa23fe) | **DELETE** /api/v1/teams/{teamId}/dar/applications/{id}/reviews/{reviewId}/files/{fileId} | DataAccessApplicationReview@destroyFile |
| [**Call154214db8250a7ff2fbbc9b6050ce1ab**](DataAccessApplicationReviewApi.md#call154214db8250a7ff2fbbc9b6050ce1ab) | **GET** /ap1/v1/teams/{teamId}/dar/applications/{id}/reviews/{reviewId}/download/{fileId} | DataAccessApplicationReview@downloadFile |
| [**Call1fe1b50e52ecaba3d4a895720df962c7**](DataAccessApplicationReviewApi.md#call1fe1b50e52ecaba3d4a895720df962c7) | **DELETE** /api/v1/teams/{team_id}/dar/applications/{id}/reviews/{reviewId} | DataAccessApplicationReview@destroyGlobal |
| [**Call3f912cdc3d1bff9db206309ee384c782**](DataAccessApplicationReviewApi.md#call3f912cdc3d1bff9db206309ee384c782) | **GET** /ap1/v1/users/{userId}/dar/applications/{id}/reviews/{reviewId}/download/{fileId} | DataAccessApplicationReview@downloadUserFile |
| [**Call53ba4c05c761d4787bfd1f1841d4b345**](DataAccessApplicationReviewApi.md#call53ba4c05c761d4787bfd1f1841d4b345) | **DELETE** /api/v1/teams/{team_id}/dar/applications/{id}/questions/{questionId}/reviews/{reviewId} | DataAccessApplicationReview@destroy |
| [**Call5766dcceb641169f89fecb537e8f79e4**](DataAccessApplicationReviewApi.md#call5766dcceb641169f89fecb537e8f79e4) | **GET** /api/v1/teams/{team_id}/dar/applications/{id}/reviews | DataAccessApplicationReview@index |
| [**Call63f5c8e9d4d96d169c64e6e0bd4d8ae1**](DataAccessApplicationReviewApi.md#call63f5c8e9d4d96d169c64e6e0bd4d8ae1) | **GET** /api/v1/users/{userId}/dar/applications/{id}/reviews | DataAccessApplicationReview@index |
| [**Call64625be7555cbc341f14b96ee6677188**](DataAccessApplicationReviewApi.md#call64625be7555cbc341f14b96ee6677188) | **PUT** /api/v1/users/{userId}/dar/applications/{id}/questions/{questionId}/reviews/{reviewId} | DataAccessApplicationReview@userUpdate |
| [**Call657e412d92e286b217a1892e7f84395c**](DataAccessApplicationReviewApi.md#call657e412d92e286b217a1892e7f84395c) | **PUT** /api/v1/teams/{team_id}/dar/applications/{id}/questions/{questionId}/reviews/{reviewId} | DataAccessApplicationReview@update |
| [**Call98785fe27d508b80baad6eb609d00f49**](DataAccessApplicationReviewApi.md#call98785fe27d508b80baad6eb609d00f49) | **PUT** /api/v1/users/{userId}/dar/applications/{id}/reviews/{reviewId} | DataAccessApplicationReview@userUpdateGlobal |
| [**Dd0ec98127c9183bf7f9d4a24085d8a8**](DataAccessApplicationReviewApi.md#dd0ec98127c9183bf7f9d4a24085d8a8) | **PUT** /api/v1/teams/{team_id}/dar/applications/{id}/reviews/{reviewId} | DataAccessApplicationReview@updateGlobal |
| [**De86e9675c626354e1d2c5d385712d90**](DataAccessApplicationReviewApi.md#de86e9675c626354e1d2c5d385712d90) | **POST** /api/v1/teams/{team_id}/dar/applications/{id}/reviews | DataAccessApplicationReview@storeGlobal |

<a id="bdc71807f7e3ab85967e343d06f95228"></a>
# **Bdc71807f7e3ab85967e343d06f95228**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Bdc71807f7e3ab85967e343d06f95228 (int teamId, int id, int questionId, De86e9675c626354e1d2c5d385712d90Request de86e9675c626354e1d2c5d385712d90Request)

DataAccessApplicationReview@store

Create a new review comment on a question in a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **questionId** | **int** | DAR application question id |  |
| **de86e9675c626354e1d2c5d385712d90Request** | [**De86e9675c626354e1d2c5d385712d90Request**](De86e9675c626354e1d2c5d385712d90Request.md) | DataAccessApplicationReview definition |  |

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

<a id="call05c982367b9c911ca1ec6d6352fa23fe"></a>
# **Call05c982367b9c911ca1ec6d6352fa23fe**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call05c982367b9c911ca1ec6d6352fa23fe (int teamId, int id, int reviewId, string fileId)

DataAccessApplicationReview@destroyFile

Delete a file associated with a DAR review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | Dar application id |  |
| **reviewId** | **int** | Review id |  |
| **fileId** | **string** | File uuid |  |

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

<a id="call154214db8250a7ff2fbbc9b6050ce1ab"></a>
# **Call154214db8250a7ff2fbbc9b6050ce1ab**
> void Call154214db8250a7ff2fbbc9b6050ce1ab (int teamId, int id, int reviewId, string fileId)

DataAccessApplicationReview@downloadFile

Download a file associated with a DAR application review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **reviewId** | **int** | DAR application review id |  |
| **fileId** | **string** | File uuid |  |

### Return type

void (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: file, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call1fe1b50e52ecaba3d4a895720df962c7"></a>
# **Call1fe1b50e52ecaba3d4a895720df962c7**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call1fe1b50e52ecaba3d4a895720df962c7 (int teamId, int id, int reviewId)

DataAccessApplicationReview@destroyGlobal

Delete a review from a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **reviewId** | **int** | DAR application review id |  |

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

<a id="call3f912cdc3d1bff9db206309ee384c782"></a>
# **Call3f912cdc3d1bff9db206309ee384c782**
> void Call3f912cdc3d1bff9db206309ee384c782 (int userId, int id, int reviewId, string fileId)

DataAccessApplicationReview@downloadUserFile

Download a file associated with a DAR application review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |
| **reviewId** | **int** | DAR application review id |  |
| **fileId** | **string** | File uuid |  |

### Return type

void (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: file, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call53ba4c05c761d4787bfd1f1841d4b345"></a>
# **Call53ba4c05c761d4787bfd1f1841d4b345**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call53ba4c05c761d4787bfd1f1841d4b345 (int teamId, int id, int questionId, int reviewId)

DataAccessApplicationReview@destroy

Delete a review from a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **questionId** | **int** | DAR application question id |  |
| **reviewId** | **int** | DAR application review id |  |

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

<a id="call5766dcceb641169f89fecb537e8f79e4"></a>
# **Call5766dcceb641169f89fecb537e8f79e4**
> Model5766dcceb641169f89fecb537e8f79e4200Response Call5766dcceb641169f89fecb537e8f79e4 (int teamId, int id)

DataAccessApplicationReview@index

Return all reviews on a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**Model5766dcceb641169f89fecb537e8f79e4200Response**](Model5766dcceb641169f89fecb537e8f79e4200Response.md)

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

<a id="call63f5c8e9d4d96d169c64e6e0bd4d8ae1"></a>
# **Call63f5c8e9d4d96d169c64e6e0bd4d8ae1**
> Model5766dcceb641169f89fecb537e8f79e4200Response Call63f5c8e9d4d96d169c64e6e0bd4d8ae1 (int userId, int id)

DataAccessApplicationReview@index

Return all reviews on a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**Model5766dcceb641169f89fecb537e8f79e4200Response**](Model5766dcceb641169f89fecb537e8f79e4200Response.md)

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

<a id="call64625be7555cbc341f14b96ee6677188"></a>
# **Call64625be7555cbc341f14b96ee6677188**
> Model657e412d92e286b217a1892e7f84395c200Response Call64625be7555cbc341f14b96ee6677188 (int userId, int id, int questionId, int reviewId, De86e9675c626354e1d2c5d385712d90Request de86e9675c626354e1d2c5d385712d90Request)

DataAccessApplicationReview@userUpdate

User endpoint to update a review comment on a question in a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |
| **questionId** | **int** | DAR application question id |  |
| **reviewId** | **int** | DAR application review id |  |
| **de86e9675c626354e1d2c5d385712d90Request** | [**De86e9675c626354e1d2c5d385712d90Request**](De86e9675c626354e1d2c5d385712d90Request.md) | DataAccessApplicationReview definition |  |

### Return type

[**Model657e412d92e286b217a1892e7f84395c200Response**](Model657e412d92e286b217a1892e7f84395c200Response.md)

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

<a id="call657e412d92e286b217a1892e7f84395c"></a>
# **Call657e412d92e286b217a1892e7f84395c**
> Model657e412d92e286b217a1892e7f84395c200Response Call657e412d92e286b217a1892e7f84395c (int teamId, int id, int questionId, int reviewId, De86e9675c626354e1d2c5d385712d90Request de86e9675c626354e1d2c5d385712d90Request)

DataAccessApplicationReview@update

Update a review comment on a question in a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **questionId** | **int** | DAR application question id |  |
| **reviewId** | **int** | DAR application review id |  |
| **de86e9675c626354e1d2c5d385712d90Request** | [**De86e9675c626354e1d2c5d385712d90Request**](De86e9675c626354e1d2c5d385712d90Request.md) | DataAccessApplicationReview definition |  |

### Return type

[**Model657e412d92e286b217a1892e7f84395c200Response**](Model657e412d92e286b217a1892e7f84395c200Response.md)

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

<a id="call98785fe27d508b80baad6eb609d00f49"></a>
# **Call98785fe27d508b80baad6eb609d00f49**
> Model657e412d92e286b217a1892e7f84395c200Response Call98785fe27d508b80baad6eb609d00f49 (int userId, int id, int reviewId, De86e9675c626354e1d2c5d385712d90Request de86e9675c626354e1d2c5d385712d90Request)

DataAccessApplicationReview@userUpdateGlobal

User endpoint to update a review comment on a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |
| **reviewId** | **int** | DAR application review id |  |
| **de86e9675c626354e1d2c5d385712d90Request** | [**De86e9675c626354e1d2c5d385712d90Request**](De86e9675c626354e1d2c5d385712d90Request.md) | DataAccessApplicationReview definition |  |

### Return type

[**Model657e412d92e286b217a1892e7f84395c200Response**](Model657e412d92e286b217a1892e7f84395c200Response.md)

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

<a id="dd0ec98127c9183bf7f9d4a24085d8a8"></a>
# **Dd0ec98127c9183bf7f9d4a24085d8a8**
> Model657e412d92e286b217a1892e7f84395c200Response Dd0ec98127c9183bf7f9d4a24085d8a8 (int teamId, int id, int reviewId, De86e9675c626354e1d2c5d385712d90Request de86e9675c626354e1d2c5d385712d90Request)

DataAccessApplicationReview@updateGlobal

Update a review comment on a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **reviewId** | **int** | DAR application review id |  |
| **de86e9675c626354e1d2c5d385712d90Request** | [**De86e9675c626354e1d2c5d385712d90Request**](De86e9675c626354e1d2c5d385712d90Request.md) | DataAccessApplicationReview definition |  |

### Return type

[**Model657e412d92e286b217a1892e7f84395c200Response**](Model657e412d92e286b217a1892e7f84395c200Response.md)

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

<a id="de86e9675c626354e1d2c5d385712d90"></a>
# **De86e9675c626354e1d2c5d385712d90**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response De86e9675c626354e1d2c5d385712d90 (int teamId, int id, De86e9675c626354e1d2c5d385712d90Request de86e9675c626354e1d2c5d385712d90Request)

DataAccessApplicationReview@storeGlobal

Create a new review comment on a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **de86e9675c626354e1d2c5d385712d90Request** | [**De86e9675c626354e1d2c5d385712d90Request**](De86e9675c626354e1d2c5d385712d90Request.md) | DataAccessApplicationReview definition |  |

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

