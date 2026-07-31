# GatewayApiSdk.Api.UploadApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Ba8ab1a2710efebacb7909736d7d2d52**](UploadApi.md#ba8ab1a2710efebacb7909736d7d2d52) | **DELETE** /api/v1/files/processed/{id} | Upload@destroy |
| [**Call21a780f609f0b91c198ab5de91dc27c6**](UploadApi.md#call21a780f609f0b91c198ab5de91dc27c6) | **GET** /api/v1/files/processed/{uuid}/download | Upload@content |
| [**E72aa4b4f0a80caa9fe872bdff983455**](UploadApi.md#e72aa4b4f0a80caa9fe872bdff983455) | **GET** /api/v1/files/{uuid} | Upload@show |
| [**Fceeda218a8998a137b9d7692e7947b6**](UploadApi.md#fceeda218a8998a137b9d7692e7947b6) | **POST** /api/v1/files | Upload@upload |

<a id="ba8ab1a2710efebacb7909736d7d2d52"></a>
# **Ba8ab1a2710efebacb7909736d7d2d52**
> C29b5b3424f7317b69b4bda048ccfafb200Response Ba8ab1a2710efebacb7909736d7d2d52 (string id)

Upload@destroy

Delete a processed file


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **string** | file uuid |  |

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

<a id="call21a780f609f0b91c198ab5de91dc27c6"></a>
# **Call21a780f609f0b91c198ab5de91dc27c6**
> Model21a780f609f0b91c198ab5de91dc27c6200Response Call21a780f609f0b91c198ab5de91dc27c6 (string uuid)

Upload@content

Get the content of a processed file


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **uuid** | **string** | upload id |  |

### Return type

[**Model21a780f609f0b91c198ab5de91dc27c6200Response**](Model21a780f609f0b91c198ab5de91dc27c6200Response.md)

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

<a id="e72aa4b4f0a80caa9fe872bdff983455"></a>
# **E72aa4b4f0a80caa9fe872bdff983455**
> E72aa4b4f0a80caa9fe872bdff983455200Response E72aa4b4f0a80caa9fe872bdff983455 (string uuid)

Upload@show

Get the scanning status of an upload


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **uuid** | **string** | upload id |  |

### Return type

[**E72aa4b4f0a80caa9fe872bdff983455200Response**](E72aa4b4f0a80caa9fe872bdff983455200Response.md)

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

<a id="fceeda218a8998a137b9d7692e7947b6"></a>
# **Fceeda218a8998a137b9d7692e7947b6**
> Fceeda218a8998a137b9d7692e7947b6200Response Fceeda218a8998a137b9d7692e7947b6 (string entityFlag = null, int teamId = null, int applicationId = null, int questionId = null)

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

[**Fceeda218a8998a137b9d7692e7947b6200Response**](Fceeda218a8998a137b9d7692e7947b6200Response.md)

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

