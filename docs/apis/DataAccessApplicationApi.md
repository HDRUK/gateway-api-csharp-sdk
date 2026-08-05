# GatewayApiSdk.Api.DataAccessApplicationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**DeleteDarApplicationFiles**](DataAccessApplicationApi.md#deletedarapplicationfiles) | **DELETE** /api/v1/dar/applications/{id}/files/{fileId} | DataAccessApplication@destroyFile |
| [**DeleteDarApplications**](DataAccessApplicationApi.md#deletedarapplications) | **DELETE** /api/v1/dar/applications/{id} | DataAccessApplication@destroy |
| [**DeleteTeamDarApplicationFile**](DataAccessApplicationApi.md#deleteteamdarapplicationfile) | **DELETE** /api/v1/teams/{teamId}/dar/applications/{id}/files/{fileId} | DataAccessApplication@destroyFile |
| [**FetchTeamDarApplicationAnswers**](DataAccessApplicationApi.md#fetchteamdarapplicationanswers) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/answers | DataAccessApplication@showAnswers |
| [**FetchTeamDarApplicationDownloadZip**](DataAccessApplicationApi.md#fetchteamdarapplicationdownloadzip) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/download | DataAccessApplication@download |
| [**FetchTeamDarApplicationFile**](DataAccessApplicationApi.md#fetchteamdarapplicationfile) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/files/{fileId}/download | DataAccessApplication@downloadFile |
| [**FetchTeamDarApplicationFiles**](DataAccessApplicationApi.md#fetchteamdarapplicationfiles) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/files | DataAccessApplication@showFiles |
| [**FetchTeamDarApplicationStatusHistory**](DataAccessApplicationApi.md#fetchteamdarapplicationstatushistory) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/status | DataAccessApplication@status |
| [**UpdateTeamDarApplication**](DataAccessApplicationApi.md#updateteamdarapplication) | **PATCH** /api/v1/teams/{teamId}/dar/applications/{id} | DataAccessApplication@update |

<a id="deletedarapplicationfiles"></a>
# **DeleteDarApplicationFiles**
> DeleteApplications200Response DeleteDarApplicationFiles (int id, string fileId)

DataAccessApplication@destroyFile

Delete a file associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR application id |  |
| **fileId** | **string** | File id |  |

### Return type

[**DeleteApplications200Response**](DeleteApplications200Response.md)

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
> DeleteApplications200Response DeleteDarApplications (int id)

DataAccessApplication@destroy

Delete a system DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR application id |  |

### Return type

[**DeleteApplications200Response**](DeleteApplications200Response.md)

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
> DeleteApplications200Response DeleteTeamDarApplicationFile (int teamId, int id, int fileId)

DataAccessApplication@destroyFile

Delete a file associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **fileId** | **int** | File id |  |

### Return type

[**DeleteApplications200Response**](DeleteApplications200Response.md)

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

