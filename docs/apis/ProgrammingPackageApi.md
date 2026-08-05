# GatewayApiSdk.Api.ProgrammingPackageApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateProgrammingPackages**](ProgrammingPackageApi.md#createprogrammingpackages) | **POST** /api/v1/programming_packages | ProgrammingPackage@store |
| [**DeleteProgrammingPackages**](ProgrammingPackageApi.md#deleteprogrammingpackages) | **DELETE** /api/v1/programming_packages/{id} | ProgrammingPackage@destroy |
| [**EditProgrammingPackages**](ProgrammingPackageApi.md#editprogrammingpackages) | **PATCH** /api/v1/programming_packages/{id} | ProgrammingPackage@update |
| [**UpdateProgrammingPackages**](ProgrammingPackageApi.md#updateprogrammingpackages) | **PUT** /api/v1/programming_packages/{id} | ProgrammingPackage@update |

<a id="createprogrammingpackages"></a>
# **CreateProgrammingPackages**
> CreateDarIntegration201Response CreateProgrammingPackages (CreateProgrammingLanguagesRequest createProgrammingLanguagesRequest)

ProgrammingPackage@store

Creates a new system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createProgrammingLanguagesRequest** | [**CreateProgrammingLanguagesRequest**](CreateProgrammingLanguagesRequest.md) | Programming package definition |  |

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

<a id="deleteprogrammingpackages"></a>
# **DeleteProgrammingPackages**
> DeleteApplications200Response DeleteProgrammingPackages (int id)

ProgrammingPackage@destroy

Delete a system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming package id |  |

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

<a id="editprogrammingpackages"></a>
# **EditProgrammingPackages**
> UpdateProgrammingPackages200Response EditProgrammingPackages (int id, EditProgrammingLanguagesRequest editProgrammingLanguagesRequest)

ProgrammingPackage@update

Edit a system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming package id |  |
| **editProgrammingLanguagesRequest** | [**EditProgrammingLanguagesRequest**](EditProgrammingLanguagesRequest.md) | ProgrammingPackage definition |  |

### Return type

[**UpdateProgrammingPackages200Response**](UpdateProgrammingPackages200Response.md)

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

<a id="updateprogrammingpackages"></a>
# **UpdateProgrammingPackages**
> UpdateProgrammingPackages200Response UpdateProgrammingPackages (int id, UpdateProgrammingLanguagesRequest updateProgrammingLanguagesRequest)

ProgrammingPackage@update

Update a system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming package id |  |
| **updateProgrammingLanguagesRequest** | [**UpdateProgrammingLanguagesRequest**](UpdateProgrammingLanguagesRequest.md) | ProgrammingPackage definition |  |

### Return type

[**UpdateProgrammingPackages200Response**](UpdateProgrammingPackages200Response.md)

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

