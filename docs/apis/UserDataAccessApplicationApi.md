# GatewayApiSdk.Api.UserDataAccessApplicationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CountAllUserDarApplications**](UserDataAccessApplicationApi.md#countalluserdarapplications) | **GET** /api/v1/users/{userId}/dar/applications/count | UserDataAccessApplicationController@allCounts |
| [**CountUserDarApplicationsByField**](UserDataAccessApplicationApi.md#countuserdarapplicationsbyfield) | **GET** /api/v1/users/{userId}/dar/applications/count/{field} | UserDataAccessApplicationController@count |
| [**CreateUserDarApplicationAnswers**](UserDataAccessApplicationApi.md#createuserdarapplicationanswers) | **PUT** /api/v1/users/{userId}/dar/applications/{id}/answers | UserDataAccessApplication@storeAnswers |
| [**FetchUserDarApplicationAnswers**](UserDataAccessApplicationApi.md#fetchuserdarapplicationanswers) | **GET** /api/v1/users/{userId}/dar/applications/{id}/answers | UserDataAccessApplicationController@showAnswers |
| [**FetchUserDarApplicationDetails**](UserDataAccessApplicationApi.md#fetchuserdarapplicationdetails) | **GET** /api/v1/users/{userId}/dar/applications/{id} | UserDataAccessApplicationController@show |
| [**FetchUserDarApplicationHeader**](UserDataAccessApplicationApi.md#fetchuserdarapplicationheader) | **GET** /api/v1/users/{userId}/dar/applications/{id}/showHeader | UserDataAccessApplicationController@showHeader |
| [**FetchUserDarApplications**](UserDataAccessApplicationApi.md#fetchuserdarapplications) | **GET** /api/v1/users/{userId}/dar/applications | UserDataAccessApplicationController@index |

<a id="countalluserdarapplications"></a>
# **CountAllUserDarApplications**
> CountUniqueFieldsCollections200Response CountAllUserDarApplications (int userId)

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

<a id="countuserdarapplicationsbyfield"></a>
# **CountUserDarApplicationsByField**
> CountUniqueFieldsCollections200Response CountUserDarApplicationsByField (int userId, string field)

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

<a id="createuserdarapplicationanswers"></a>
# **CreateUserDarApplicationAnswers**
> CreateCategories200Response CreateUserDarApplicationAnswers (int userId, int id, CreateUserDarApplicationAnswersRequest createUserDarApplicationAnswersRequest)

UserDataAccessApplication@storeAnswers

Add answers to the user's DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |
| **createUserDarApplicationAnswersRequest** | [**CreateUserDarApplicationAnswersRequest**](CreateUserDarApplicationAnswersRequest.md) | UserDataAccessApplication definition |  |

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
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchuserdarapplicationanswers"></a>
# **FetchUserDarApplicationAnswers**
> FetchTeamDarApplicationAnswers200Response FetchUserDarApplicationAnswers (int userId, int id)

UserDataAccessApplicationController@showAnswers

Return answers from the user's DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**FetchTeamDarApplicationAnswers200Response**](FetchTeamDarApplicationAnswers200Response.md)

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

<a id="fetchuserdarapplicationdetails"></a>
# **FetchUserDarApplicationDetails**
> FetchTeamDarApplication200Response FetchUserDarApplicationDetails (int userId, int id)

UserDataAccessApplicationController@show

Return a DAR application belonging to the user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**FetchTeamDarApplication200Response**](FetchTeamDarApplication200Response.md)

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

<a id="fetchuserdarapplicationheader"></a>
# **FetchUserDarApplicationHeader**
> FetchTeamDarApplication200Response FetchUserDarApplicationHeader (int userId, int id)

UserDataAccessApplicationController@showHeader

Get header information about a specific DAR


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**FetchTeamDarApplication200Response**](FetchTeamDarApplication200Response.md)

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

<a id="fetchuserdarapplications"></a>
# **FetchUserDarApplications**
> FetchTeamDarApplications200Response FetchUserDarApplications (int userId)

UserDataAccessApplicationController@index

List of dar applications belonging to a user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |

### Return type

[**FetchTeamDarApplications200Response**](FetchTeamDarApplications200Response.md)

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

