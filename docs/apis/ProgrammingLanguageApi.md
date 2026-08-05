# GatewayApiSdk.Api.ProgrammingLanguageApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateProgrammingLanguages**](ProgrammingLanguageApi.md#createprogramminglanguages) | **POST** /api/v1/programming_languages | ProgrammingLanguage@store |
| [**DeleteProgrammingLanguages**](ProgrammingLanguageApi.md#deleteprogramminglanguages) | **DELETE** /api/v1/programming_languages/{id} | ProgrammingLanguage@destroy |
| [**EditProgrammingLanguages**](ProgrammingLanguageApi.md#editprogramminglanguages) | **PATCH** /api/v1/programming_languages/{id} | ProgrammingLanguage@update |
| [**UpdateProgrammingLanguages**](ProgrammingLanguageApi.md#updateprogramminglanguages) | **PUT** /api/v1/programming_languages/{id} | ProgrammingLanguage@update |

<a id="createprogramminglanguages"></a>
# **CreateProgrammingLanguages**
> CreateDarIntegration201Response CreateProgrammingLanguages (CreateProgrammingLanguagesRequest createProgrammingLanguagesRequest)

ProgrammingLanguage@store

Creates a new system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createProgrammingLanguagesRequest** | [**CreateProgrammingLanguagesRequest**](CreateProgrammingLanguagesRequest.md) | Programming language definition |  |

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

<a id="deleteprogramminglanguages"></a>
# **DeleteProgrammingLanguages**
> DeleteApplications200Response DeleteProgrammingLanguages (int id)

ProgrammingLanguage@destroy

Delete a system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming language id |  |

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

<a id="editprogramminglanguages"></a>
# **EditProgrammingLanguages**
> UpdateProgrammingLanguages200Response EditProgrammingLanguages (int id, EditProgrammingLanguagesRequest editProgrammingLanguagesRequest)

ProgrammingLanguage@update

Edit a system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming language id |  |
| **editProgrammingLanguagesRequest** | [**EditProgrammingLanguagesRequest**](EditProgrammingLanguagesRequest.md) | ProgrammingLanguage definition |  |

### Return type

[**UpdateProgrammingLanguages200Response**](UpdateProgrammingLanguages200Response.md)

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

<a id="updateprogramminglanguages"></a>
# **UpdateProgrammingLanguages**
> UpdateProgrammingLanguages200Response UpdateProgrammingLanguages (int id, UpdateProgrammingLanguagesRequest updateProgrammingLanguagesRequest)

ProgrammingLanguage@update

Update a system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming language id |  |
| **updateProgrammingLanguagesRequest** | [**UpdateProgrammingLanguagesRequest**](UpdateProgrammingLanguagesRequest.md) | ProgrammingLanguage definition |  |

### Return type

[**UpdateProgrammingLanguages200Response**](UpdateProgrammingLanguages200Response.md)

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

