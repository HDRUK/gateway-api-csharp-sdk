# GatewayApiSdk.Api.DataAccessApplicationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateDarApplications**](DataAccessApplicationApi.md#createdarapplications) | **POST** /api/v1/dar/applications | DataAccessApplication@store |
| [**DeleteDarApplicationFiles**](DataAccessApplicationApi.md#deletedarapplicationfiles) | **DELETE** /api/v1/dar/applications/{id}/files/{fileId} | DataAccessApplication@destroyFile |
| [**DeleteDarApplications**](DataAccessApplicationApi.md#deletedarapplications) | **DELETE** /api/v1/dar/applications/{id} | DataAccessApplication@destroy |
| [**DeleteTeamDarApplicationFile**](DataAccessApplicationApi.md#deleteteamdarapplicationfile) | **DELETE** /api/v1/teams/{teamId}/dar/applications/{id}/files/{fileId} | DataAccessApplication@destroyFile |
| [**DeleteUserDarApplication**](DataAccessApplicationApi.md#deleteuserdarapplication) | **DELETE** /api/v1/users/{userId}/dar/applications/{id} | DataAccessApplication@destroy |
| [**DeleteUserDarApplicationFile**](DataAccessApplicationApi.md#deleteuserdarapplicationfile) | **DELETE** /api/v1/users/{userId}/dar/applications/{id}/files/{fileId} | DataAccessApplication@destroyFile |
| [**FetchTeamDarApplicationAnswers**](DataAccessApplicationApi.md#fetchteamdarapplicationanswers) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/answers | DataAccessApplication@showAnswers |
| [**FetchTeamDarApplicationDownloadZip**](DataAccessApplicationApi.md#fetchteamdarapplicationdownloadzip) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/download | DataAccessApplication@download |
| [**FetchTeamDarApplicationFile**](DataAccessApplicationApi.md#fetchteamdarapplicationfile) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/files/{fileId}/download | DataAccessApplication@downloadFile |
| [**FetchTeamDarApplicationFiles**](DataAccessApplicationApi.md#fetchteamdarapplicationfiles) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/files | DataAccessApplication@showFiles |
| [**FetchTeamDarApplicationStatusHistory**](DataAccessApplicationApi.md#fetchteamdarapplicationstatushistory) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/status | DataAccessApplication@status |
| [**FetchUserDarApplicationFile**](DataAccessApplicationApi.md#fetchuserdarapplicationfile) | **GET** /api/v1/users/{userId}/dar/applications/{id}/files/{fileId}/download | DataAccessApplication@downloadFile |
| [**FetchUserDarApplicationFiles**](DataAccessApplicationApi.md#fetchuserdarapplicationfiles) | **GET** /api/v1/users/{userId}/dar/applications/{id}/files | DataAccessApplication@showFiles |
| [**PatchUserDarApplication**](DataAccessApplicationApi.md#patchuserdarapplication) | **PATCH** /api/v1/users/{userId}/dar/applications/{id} | DataAccessApplication@update |
| [**UpdateTeamDarApplication**](DataAccessApplicationApi.md#updateteamdarapplication) | **PATCH** /api/v1/teams/{teamId}/dar/applications/{id} | DataAccessApplication@update |
| [**UpdateUserDarApplication**](DataAccessApplicationApi.md#updateuserdarapplication) | **PUT** /api/v1/users/{userId}/dar/applications/{id} | DataAccessApplication@update |

<a id="createdarapplications"></a>
# **CreateDarApplications**
> CreateCategories200Response CreateDarApplications (CreateDarApplicationsRequest createDarApplicationsRequest)

DataAccessApplication@store

Creates a new DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createDarApplicationsRequest** | [**CreateDarApplicationsRequest**](CreateDarApplicationsRequest.md) | DataAccessApplication definition |  |

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

<a id="deletedarapplicationfiles"></a>
# **DeleteDarApplicationFiles**
> DeleteAliases200Response DeleteDarApplicationFiles (int id, string fileId)

DataAccessApplication@destroyFile

Delete a file associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR application id |  |
| **fileId** | **string** | File id |  |

### Return type

[**DeleteAliases200Response**](DeleteAliases200Response.md)

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

<a id="deletedarapplications"></a>
# **DeleteDarApplications**
> DeleteAliases200Response DeleteDarApplications (int id)

DataAccessApplication@destroy

Delete a system DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR application id |  |

### Return type

[**DeleteAliases200Response**](DeleteAliases200Response.md)

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

<a id="deleteteamdarapplicationfile"></a>
# **DeleteTeamDarApplicationFile**
> DeleteAliases200Response DeleteTeamDarApplicationFile (int teamId, int id, int fileId)

DataAccessApplication@destroyFile

Delete a file associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **fileId** | **int** | File id |  |

### Return type

[**DeleteAliases200Response**](DeleteAliases200Response.md)

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

<a id="deleteuserdarapplication"></a>
# **DeleteUserDarApplication**
> DeleteAliases200Response DeleteUserDarApplication (int userId, int id)

DataAccessApplication@destroy

Delete a users DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**DeleteAliases200Response**](DeleteAliases200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **401** | Unauthorized |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deleteuserdarapplicationfile"></a>
# **DeleteUserDarApplicationFile**
> DeleteAliases200Response DeleteUserDarApplicationFile (int id, int userId, string fileId)

DataAccessApplication@destroyFile

Delete a file associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR application id |  |
| **userId** | **int** | User id |  |
| **fileId** | **string** | File uuid |  |

### Return type

[**DeleteAliases200Response**](DeleteAliases200Response.md)

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

<a id="fetchteamdarapplicationanswers"></a>
# **FetchTeamDarApplicationAnswers**
> FetchTeamDarApplicationAnswers200Response FetchTeamDarApplicationAnswers (int teamId, int id)

DataAccessApplication@showAnswers

Return answers from a single DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
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

<a id="fetchteamdarapplicationdownloadzip"></a>
# **FetchTeamDarApplicationDownloadZip**
> void FetchTeamDarApplicationDownloadZip (int teamId, int id)

DataAccessApplication@download

Returns a DAR form as a CSV with attached files as a zip


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |

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

<a id="fetchteamdarapplicationfile"></a>
# **FetchTeamDarApplicationFile**
> void FetchTeamDarApplicationFile (int teamId, int id, string fileId)

DataAccessApplication@downloadFile

Download a file associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
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

<a id="fetchteamdarapplicationfiles"></a>
# **FetchTeamDarApplicationFiles**
> FetchTeamDarApplicationFiles200Response FetchTeamDarApplicationFiles (int teamId, int id)

DataAccessApplication@showFiles

Return a list of files associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**FetchTeamDarApplicationFiles200Response**](FetchTeamDarApplicationFiles200Response.md)

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

<a id="fetchteamdarapplicationstatushistory"></a>
# **FetchTeamDarApplicationStatusHistory**
> FetchTeamDarApplicationStatusHistory200Response FetchTeamDarApplicationStatusHistory (int teamId, int id)

DataAccessApplication@status

Return the status history of a single DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**FetchTeamDarApplicationStatusHistory200Response**](FetchTeamDarApplicationStatusHistory200Response.md)

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

<a id="fetchuserdarapplicationfile"></a>
# **FetchUserDarApplicationFile**
> void FetchUserDarApplicationFile (int id, int userId, string fileId)

DataAccessApplication@downloadFile

Download a file associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR application id |  |
| **userId** | **int** | User id |  |
| **fileId** | **string** | File id |  |

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

<a id="fetchuserdarapplicationfiles"></a>
# **FetchUserDarApplicationFiles**
> FetchTeamDarApplicationFiles200Response FetchUserDarApplicationFiles (int id, int userId)

DataAccessApplication@showFiles

Return a list of files associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR application id |  |
| **userId** | **int** | User id |  |

### Return type

[**FetchTeamDarApplicationFiles200Response**](FetchTeamDarApplicationFiles200Response.md)

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

<a id="patchuserdarapplication"></a>
# **PatchUserDarApplication**
> FetchTeamDarApplication200Response PatchUserDarApplication (int userId, int id, PatchUserDarApplicationRequest patchUserDarApplicationRequest)

DataAccessApplication@update

Edit a system DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |
| **patchUserDarApplicationRequest** | [**PatchUserDarApplicationRequest**](PatchUserDarApplicationRequest.md) | DataAccessApplication definition |  |

### Return type

[**FetchTeamDarApplication200Response**](FetchTeamDarApplication200Response.md)

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

<a id="updateteamdarapplication"></a>
# **UpdateTeamDarApplication**
> FetchTeamDarApplication200Response UpdateTeamDarApplication (int teamId, int id, UpdateTeamDarApplicationRequest updateTeamDarApplicationRequest)

DataAccessApplication@update

Edit a system DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **updateTeamDarApplicationRequest** | [**UpdateTeamDarApplicationRequest**](UpdateTeamDarApplicationRequest.md) | DataAccessApplication definition |  |

### Return type

[**FetchTeamDarApplication200Response**](FetchTeamDarApplication200Response.md)

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

<a id="updateuserdarapplication"></a>
# **UpdateUserDarApplication**
> FetchTeamDarApplication200Response UpdateUserDarApplication (int userId, int id, UpdateUserDarApplicationRequest updateUserDarApplicationRequest)

DataAccessApplication@update

Update a system DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |
| **updateUserDarApplicationRequest** | [**UpdateUserDarApplicationRequest**](UpdateUserDarApplicationRequest.md) | DataAccessApplication definition |  |

### Return type

[**FetchTeamDarApplication200Response**](FetchTeamDarApplication200Response.md)

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

