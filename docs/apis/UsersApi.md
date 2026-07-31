# GatewayApiSdk.Api.UsersApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateUsers**](UsersApi.md#createusers) | **POST** /api/v1/users | UserController@store |
| [**DeleteUsers**](UsersApi.md#deleteusers) | **DELETE** /api/v1/users/{id} | UserController@destroy |
| [**EditUsers**](UsersApi.md#editusers) | **PATCH** /api/v1/users/{id} | UserController@edit |
| [**FetchAllUsers**](UsersApi.md#fetchallusers) | **GET** /api/v1/users | UserController@index |
| [**FetchUsers**](UsersApi.md#fetchusers) | **GET** /api/v1/users/{id} | UserController@show |
| [**ResendSecondaryVerificationEmail**](UsersApi.md#resendsecondaryverificationemail) | **POST** /api/v1/users/{id}/resend-secondary-verification | Resend secondary email verification |
| [**UpdateUsers**](UsersApi.md#updateusers) | **PUT** /api/v1/users/{id} | UserController@update |
| [**VerifySecondaryEmail**](UsersApi.md#verifysecondaryemail) | **GET** /api/v1/users/verify-secondary-email/{uuid} | Verify user&#39;s secondary email using a UUID |

<a id="createusers"></a>
# **CreateUsers**
> CreateCategories200Response CreateUsers (CreateUsersRequest createUsersRequest)

UserController@store

Create a new user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createUsersRequest** | [**CreateUsersRequest**](CreateUsersRequest.md) | Pass user credentials |  |

### Return type

[**CreateCategories200Response**](CreateCategories200Response.md)

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

<a id="deleteusers"></a>
# **DeleteUsers**
> DeleteFederation200Response DeleteUsers (int id)

UserController@destroy

Delete User based in id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | user id |  |

### Return type

[**DeleteFederation200Response**](DeleteFederation200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Error response |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="editusers"></a>
# **EditUsers**
> FetchUsers200Response EditUsers (int id, UpdateUsersRequest updateUsersRequest)

UserController@edit

Edit user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | user id |  |
| **updateUsersRequest** | [**UpdateUsersRequest**](UpdateUsersRequest.md) | Pass user credentials |  |

### Return type

[**FetchUsers200Response**](FetchUsers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **400** | Error |  -  |
| **401** | Unauthorized |  -  |
| **404** | Error response |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchallusers"></a>
# **FetchAllUsers**
> FetchAllUsers200Response FetchAllUsers (string filterNames = null)

UserController@index

Get All Users


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **filterNames** | **string** | Three or more characters to filter users names by | [optional]  |

### Return type

[**FetchAllUsers200Response**](FetchAllUsers200Response.md)

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

<a id="fetchusers"></a>
# **FetchUsers**
> FetchUsers200Response FetchUsers (int id)

UserController@show

Get users by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | user id |  |

### Return type

[**FetchUsers200Response**](FetchUsers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="resendsecondaryverificationemail"></a>
# **ResendSecondaryVerificationEmail**
> ResendSecondaryVerificationEmail200Response ResendSecondaryVerificationEmail (int id)

Resend secondary email verification

Resends the verification email for the secondary email address. Old tokens are expired.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | User ID |  |

### Return type

[**ResendSecondaryVerificationEmail200Response**](ResendSecondaryVerificationEmail200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Verification email resent |  -  |
| **404** | User or secondary email not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updateusers"></a>
# **UpdateUsers**
> FetchUsers200Response UpdateUsers (int id, UpdateUsersRequest updateUsersRequest)

UserController@update

Update user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | user id |  |
| **updateUsersRequest** | [**UpdateUsersRequest**](UpdateUsersRequest.md) | Pass user credentials |  |

### Return type

[**FetchUsers200Response**](FetchUsers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **400** | Error |  -  |
| **401** | Unauthorized |  -  |
| **404** | Error response |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="verifysecondaryemail"></a>
# **VerifySecondaryEmail**
> VerifySecondaryEmail200Response VerifySecondaryEmail (string uuid)

Verify user's secondary email using a UUID

This endpoint verifies the secondary email for a user if the UUID is valid and not expired.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **uuid** | **string** | Verification UUID |  |

### Return type

[**VerifySecondaryEmail200Response**](VerifySecondaryEmail200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Email verified successfully |  -  |
| **400** | Invalid or expired token |  -  |
| **404** | UUID not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

