# GatewayApiSdk.Api.ProgrammingPackageApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateProgrammingPackages**](ProgrammingPackageApi.md#createprogrammingpackages) | **POST** /api/v1/programming_packages | ProgrammingPackage@store |
| [**DeleteProgrammingPackages**](ProgrammingPackageApi.md#deleteprogrammingpackages) | **DELETE** /api/v1/programming_packages/{id} | ProgrammingPackage@destroy |
| [**EditProgrammingPackages**](ProgrammingPackageApi.md#editprogrammingpackages) | **PATCH** /api/v1/programming_packages/{id} | ProgrammingPackage@update |
| [**FetchAllProgrammingPackages**](ProgrammingPackageApi.md#fetchallprogrammingpackages) | **GET** /api/v1/programming_packages | ProgrammingPackage@index |
| [**FetchProgrammingPackages**](ProgrammingPackageApi.md#fetchprogrammingpackages) | **GET** /api/v1/programming_packages/{id} | ProgrammingPackage@show |
| [**UpdateProgrammingPackages**](ProgrammingPackageApi.md#updateprogrammingpackages) | **PUT** /api/v1/programming_packages/{id} | ProgrammingPackage@update |

<a id="createprogrammingpackages"></a>
# **CreateProgrammingPackages**
> CreateCategories200Response CreateProgrammingPackages (CreateCategoriesRequest createCategoriesRequest)

ProgrammingPackage@store

Creates a new system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createCategoriesRequest** | [**CreateCategoriesRequest**](CreateCategoriesRequest.md) | Programming package definition |  |

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

<a id="deleteprogrammingpackages"></a>
# **DeleteProgrammingPackages**
> DeleteAliases200Response DeleteProgrammingPackages (int id)

ProgrammingPackage@destroy

Delete a system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming package id |  |

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

<a id="editprogrammingpackages"></a>
# **EditProgrammingPackages**
> UpdateProgrammingPackages200Response EditProgrammingPackages (int id, EditCategoriesRequest editCategoriesRequest)

ProgrammingPackage@update

Edit a system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming package id |  |
| **editCategoriesRequest** | [**EditCategoriesRequest**](EditCategoriesRequest.md) | ProgrammingPackage definition |  |

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

<a id="fetchallprogrammingpackages"></a>
# **FetchAllProgrammingPackages**
> FetchAllProgrammingPackages200Response FetchAllProgrammingPackages ()

ProgrammingPackage@index

Returns a list of programming packages enabled on the system


### Parameters
This endpoint does not need any parameter.
### Return type

[**FetchAllProgrammingPackages200Response**](FetchAllProgrammingPackages200Response.md)

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

<a id="fetchprogrammingpackages"></a>
# **FetchProgrammingPackages**
> FetchProgrammingPackages200Response FetchProgrammingPackages (int id)

ProgrammingPackage@show

Return a single system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming package id |  |

### Return type

[**FetchProgrammingPackages200Response**](FetchProgrammingPackages200Response.md)

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

<a id="updateprogrammingpackages"></a>
# **UpdateProgrammingPackages**
> UpdateProgrammingPackages200Response UpdateProgrammingPackages (int id, UpdateCategoriesRequest updateCategoriesRequest)

ProgrammingPackage@update

Update a system programming package


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | programming package id |  |
| **updateCategoriesRequest** | [**UpdateCategoriesRequest**](UpdateCategoriesRequest.md) | ProgrammingPackage definition |  |

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

