# GatewayApiSdk.Api.DataAccessTemplateApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateDarTemplate**](DataAccessTemplateApi.md#createdartemplate) | **POST** /api/v1/dar/templates | DataAccessTemplate@store |
| [**DeleteDarTemplate**](DataAccessTemplateApi.md#deletedartemplate) | **DELETE** /api/v1/dar/templates/{id} | DataAccessTemplate@destroy |
| [**FetchDarTemplate**](DataAccessTemplateApi.md#fetchdartemplate) | **GET** /api/v1/dar/templates/{id} | DataAccessTemplate@show |
| [**FetchDarTemplates**](DataAccessTemplateApi.md#fetchdartemplates) | **GET** /api/v1/dar/templates | DataAccessTemplate@index |
| [**PatchDarTemplate**](DataAccessTemplateApi.md#patchdartemplate) | **PATCH** /api/v1/dar/templates/{id} | DataAccessTemplate@update |
| [**UpdateDarTemplate**](DataAccessTemplateApi.md#updatedartemplate) | **PUT** /api/v1/dar/templates/{id} | DataAccessTemplate@update |

<a id="createdartemplate"></a>
# **CreateDarTemplate**
> CreateDarIntegration201Response CreateDarTemplate (CreateDarTemplateRequest createDarTemplateRequest)

DataAccessTemplate@store

Creates a new DAR template


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createDarTemplateRequest** | [**CreateDarTemplateRequest**](CreateDarTemplateRequest.md) | DataAccessTemplate definition |  |

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
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletedartemplate"></a>
# **DeleteDarTemplate**
> DeleteApplications200Response DeleteDarTemplate (int id)

DataAccessTemplate@destroy

Delete a system DAR template


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR template id |  |

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

<a id="fetchdartemplate"></a>
# **FetchDarTemplate**
> FetchDarTemplate200Response FetchDarTemplate (int id)

DataAccessTemplate@show

Return a single DAR template


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR template id |  |

### Return type

[**FetchDarTemplate200Response**](FetchDarTemplate200Response.md)

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

<a id="fetchdartemplates"></a>
# **FetchDarTemplates**
> FetchDarTemplates200Response FetchDarTemplates (int withQuestions = null, string published = null)

DataAccessTemplate@index

List of DAR templates


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **withQuestions** | **int** | Include questions in response | [optional]  |
| **published** | **string** | Template publication status to filter by (true, false) | [optional]  |

### Return type

[**FetchDarTemplates200Response**](FetchDarTemplates200Response.md)

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

<a id="patchdartemplate"></a>
# **PatchDarTemplate**
> PatchDarTemplate200Response PatchDarTemplate (int id, PatchDarTemplateRequest patchDarTemplateRequest, int sectionId = null)

DataAccessTemplate@update

Edit a system DAR template


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR template id |  |
| **patchDarTemplateRequest** | [**PatchDarTemplateRequest**](PatchDarTemplateRequest.md) | DataAccessTemplate definition |  |
| **sectionId** | **int** | Section id | [optional]  |

### Return type

[**PatchDarTemplate200Response**](PatchDarTemplate200Response.md)

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

<a id="updatedartemplate"></a>
# **UpdateDarTemplate**
> FetchDarTemplate200Response UpdateDarTemplate (int id, UpdateDarTemplateRequest updateDarTemplateRequest)

DataAccessTemplate@update

Update a system DAR template


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR template id |  |
| **updateDarTemplateRequest** | [**UpdateDarTemplateRequest**](UpdateDarTemplateRequest.md) | DataAccessTemplate definition |  |

### Return type

[**FetchDarTemplate200Response**](FetchDarTemplate200Response.md)

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

