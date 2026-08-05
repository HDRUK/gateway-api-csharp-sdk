# GatewayApiSdk.Api.UsersApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateUsers**](UsersApi.md#createusers) | **POST** /api/v1/users | UserController@store |
| [**DeleteUsers**](UsersApi.md#deleteusers) | **DELETE** /api/v1/users/{id} | UserController@destroy |
| [**EditUsers**](UsersApi.md#editusers) | **PATCH** /api/v1/users/{id} | UserController@edit |
| [**VerifySecondaryEmail**](UsersApi.md#verifysecondaryemail) | **GET** /api/v1/users/verify-secondary-email/{uuid} | Verify user&#39;s secondary email using a UUID |

<a id="createusers"></a>
# **CreateUsers**
> CreateDarIntegration201Response CreateUsers (CreateUsersRequest createUsersRequest)

UserController@store

Create a new user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createUsersRequest** | [**CreateUsersRequest**](CreateUsersRequest.md) | Pass user credentials |  |

### Return type

[**CreateDarIntegration201Response**](CreateDarIntegration201Response.md)

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
> EditUsers200Response EditUsers (int id, EditUsersRequest editUsersRequest)

UserController@edit

Edit user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | user id |  |
| **editUsersRequest** | [**EditUsersRequest**](EditUsersRequest.md) | Pass user credentials |  |

### Return type

[**EditUsers200Response**](EditUsers200Response.md)

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

