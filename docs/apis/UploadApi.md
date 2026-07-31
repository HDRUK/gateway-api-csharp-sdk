# GatewayApiSdk.Api.UploadApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateFiles**](UploadApi.md#createfiles) | **POST** /api/v1/files | Upload@upload |
| [**DeleteFilesProcessed**](UploadApi.md#deletefilesprocessed) | **DELETE** /api/v1/files/processed/{id} | Upload@destroy |
| [**FetchFiles**](UploadApi.md#fetchfiles) | **GET** /api/v1/files/{uuid} | Upload@show |
| [**FetchFilesProcessedContent**](UploadApi.md#fetchfilesprocessedcontent) | **GET** /api/v1/files/processed/{uuid}/download | Upload@content |

<a id="createfiles"></a>
# **CreateFiles**
> CreateFiles200Response CreateFiles (string entityFlag = null, int teamId = null, int applicationId = null, int questionId = null)

Upload@upload

Upload a file to the gateway-api via scanning sub-service


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **entityFlag** | **string** | Flag to indicate the purpose of the file upload e.g. dur-from-upload | [optional]  |
| **teamId** | **int** | Id of team associated with the file upload | [optional]  |
| **applicationId** | **int** | Id of dar application associated with the file upload | [optional]  |
| **questionId** | **int** | Id of the question in the dar application associated with the file upload | [optional]  |

### Return type

[**CreateFiles200Response**](CreateFiles200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Upload complete |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletefilesprocessed"></a>
# **DeleteFilesProcessed**
> DeleteAliases200Response DeleteFilesProcessed (string id)

Upload@destroy

Delete a processed file


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **string** | file uuid |  |

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

<a id="fetchfiles"></a>
# **FetchFiles**
> FetchFiles200Response FetchFiles (string uuid)

Upload@show

Get the scanning status of an upload


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **uuid** | **string** | upload id |  |

### Return type

[**FetchFiles200Response**](FetchFiles200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchfilesprocessedcontent"></a>
# **FetchFilesProcessedContent**
> FetchFilesProcessedContent200Response FetchFilesProcessedContent (string uuid)

Upload@content

Get the content of a processed file


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **uuid** | **string** | upload id |  |

### Return type

[**FetchFilesProcessedContent200Response**](FetchFilesProcessedContent200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

