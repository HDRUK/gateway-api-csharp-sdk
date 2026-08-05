# GatewayApiSdk.Api.AuthenticationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Authentication**](AuthenticationApi.md#authentication) | **POST** /api/v1/auth | AuthController@checkAuthorization |
| [**Login**](AuthenticationApi.md#login) | **POST** /api/v1/auth/login | AuthController@login |
| [**Register**](AuthenticationApi.md#register) | **POST** /api/v1/auth/register | AuthController@register |

<a id="authentication"></a>
# **Authentication**
> Authentication200Response Authentication (AuthenticationRequest authenticationRequest)

AuthController@checkAuthorization

Generate Jwt based on email and password


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **authenticationRequest** | [**AuthenticationRequest**](AuthenticationRequest.md) | Pass user credentials |  |

### Return type

[**Authentication200Response**](Authentication200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Missing Property |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="login"></a>
# **Login**
> Register200Response Login (LoginRequest loginRequest)

AuthController@login

Login with email and password


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **loginRequest** | [**LoginRequest**](LoginRequest.md) | Pass user credentials |  |

### Return type

[**Register200Response**](Register200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **400** | Validation error |  -  |
| **401** | Invalid credentials |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="register"></a>
# **Register**
> Register200Response Register (RegisterRequest registerRequest)

AuthController@register

Register a new user with email and password


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registerRequest** | [**RegisterRequest**](RegisterRequest.md) | Pass user registration data |  |

### Return type

[**Register200Response**](Register200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **400** | Validation error |  -  |
| **409** | Email already exists |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

