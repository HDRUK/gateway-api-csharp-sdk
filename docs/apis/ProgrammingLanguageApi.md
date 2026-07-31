# GatewayApiSdk.Api.ProgrammingLanguageApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateProgrammingLanguages**](ProgrammingLanguageApi.md#createprogramminglanguages) | **POST** /api/v1/programming_languages | ProgrammingLanguage@store |
| [**DeleteProgrammingLanguages**](ProgrammingLanguageApi.md#deleteprogramminglanguages) | **DELETE** /api/v1/programming_languages/{id} | ProgrammingLanguage@destroy |
| [**EditProgrammingLanguages**](ProgrammingLanguageApi.md#editprogramminglanguages) | **PATCH** /api/v1/programming_languages/{id} | ProgrammingLanguage@update |
| [**FetchAllProgrammingLanguages**](ProgrammingLanguageApi.md#fetchallprogramminglanguages) | **GET** /api/v1/programming_languages | ProgrammingLanguage@index |
| [**FetchProgrammingLanguages**](ProgrammingLanguageApi.md#fetchprogramminglanguages) | **GET** /api/v1/programming_languages/{id} | ProgrammingLanguage@show |
| [**UpdateProgrammingLanguages**](ProgrammingLanguageApi.md#updateprogramminglanguages) | **PUT** /api/v1/programming_languages/{id} | ProgrammingLanguage@update |

<a id="createprogramminglanguages"></a>
# **CreateProgrammingLanguages**
> CreateCategories200Response CreateProgrammingLanguages (CreateCategoriesRequest createCategoriesRequest)

ProgrammingLanguage@store

Creates a new system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createCategoriesRequest** | [**CreateCategoriesRequest**](CreateCategoriesRequest.md) | Programming language definition |  |

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

<a id="deleteprogramminglanguages"></a>
# **DeleteProgrammingLanguages**
> DeleteAliases200Response DeleteProgrammingLanguages (int id)

ProgrammingLanguage@destroy

Delete a system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming language id |  |

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

<a id="editprogramminglanguages"></a>
# **EditProgrammingLanguages**
> UpdateProgrammingLanguages200Response EditProgrammingLanguages (int id, EditCategoriesRequest editCategoriesRequest)

ProgrammingLanguage@update

Edit a system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming language id |  |
| **editCategoriesRequest** | [**EditCategoriesRequest**](EditCategoriesRequest.md) | ProgrammingLanguage definition |  |

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

<a id="fetchallprogramminglanguages"></a>
# **FetchAllProgrammingLanguages**
> FetchAllProgrammingLanguages200Response FetchAllProgrammingLanguages ()

ProgrammingLanguage@index

Returns a list of programming languages enabled on the system


### Parameters
This endpoint does not need any parameter.
### Return type

[**FetchAllProgrammingLanguages200Response**](FetchAllProgrammingLanguages200Response.md)

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

<a id="fetchprogramminglanguages"></a>
# **FetchProgrammingLanguages**
> FetchProgrammingLanguages200Response FetchProgrammingLanguages (int id)

ProgrammingLanguage@show

Return a single system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming language id |  |

### Return type

[**FetchProgrammingLanguages200Response**](FetchProgrammingLanguages200Response.md)

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

<a id="updateprogramminglanguages"></a>
# **UpdateProgrammingLanguages**
> UpdateProgrammingLanguages200Response UpdateProgrammingLanguages (int id, UpdateCategoriesRequest updateCategoriesRequest)

ProgrammingLanguage@update

Update a system programming language


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming language id |  |
| **updateCategoriesRequest** | [**UpdateCategoriesRequest**](UpdateCategoriesRequest.md) | ProgrammingLanguage definition |  |

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

