# GatewayApiSdk.Api.UserRolesApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateUserHasRoles**](UserRolesApi.md#createuserhasroles) | **POST** /api/v1/users/{userId}/roles | UserRoleController@store |
| [**DeleteUserHasRoles**](UserRolesApi.md#deleteuserhasroles) | **DELETE** /api/v1/users/{userId}/roles | UserRoleController@destroy |
| [**UpdateUserHasRoles**](UserRolesApi.md#updateuserhasroles) | **PATCH** /api/v1/users/{userId}/roles | UserRoleController@edit |

<a id="createuserhasroles"></a>
# **CreateUserHasRoles**
> DeleteApplications200Response CreateUserHasRoles (int userId, CreateUserHasRolesRequest createUserHasRolesRequest)

UserRoleController@store

Create user has roles


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
| **createUserHasRolesRequest** | [**CreateUserHasRolesRequest**](CreateUserHasRolesRequest.md) | Pass user credentials |  |

### Return type

[**DeleteApplications200Response**](DeleteApplications200Response.md)

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

<a id="deleteuserhasroles"></a>
# **DeleteUserHasRoles**
> DeleteFederation200Response DeleteUserHasRoles (int userId)

UserRoleController@destroy

Delete user - roles


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |

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
| **404** | Error response |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updateuserhasroles"></a>
# **UpdateUserHasRoles**
> DeleteApplications200Response UpdateUserHasRoles (int userId, UpdateUserHasRolesRequest updateUserHasRolesRequest)

UserRoleController@edit

Update user has roles


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
| **updateUserHasRolesRequest** | [**UpdateUserHasRolesRequest**](UpdateUserHasRolesRequest.md) | Pass user credentials |  |

### Return type

[**DeleteApplications200Response**](DeleteApplications200Response.md)

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

