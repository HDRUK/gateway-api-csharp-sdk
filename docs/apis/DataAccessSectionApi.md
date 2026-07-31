# GatewayApiSdk.Api.DataAccessSectionApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateDarSection**](DataAccessSectionApi.md#createdarsection) | **POST** /api/v1/dar/sections | DataAccessSection@store |
| [**DeleteDarSection**](DataAccessSectionApi.md#deletedarsection) | **DELETE** /api/v1/dar/sections/{id} | DataAccessSection@destroy |
| [**FetchDarSection**](DataAccessSectionApi.md#fetchdarsection) | **GET** /api/v1/dar/sections/{id} | DataAccessSection@show |
| [**FetchDarSections**](DataAccessSectionApi.md#fetchdarsections) | **GET** /api/v1/dar/sections | DataAccessSection@index |
| [**PatchDarSection**](DataAccessSectionApi.md#patchdarsection) | **PATCH** /api/v1/dar/sections/{id} | DataAccessSection@update |
| [**UpdateDarSection**](DataAccessSectionApi.md#updatedarsection) | **PUT** /api/v1/dar/sections/{id} | DataAccessSection@update |

<a id="createdarsection"></a>
# **CreateDarSection**
> CreateCategories200Response CreateDarSection (CreateDarSectionRequest createDarSectionRequest)

DataAccessSection@store

Creates a new DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createDarSectionRequest** | [**CreateDarSectionRequest**](CreateDarSectionRequest.md) | DataAccessSection definition |  |

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

<a id="deletedarsection"></a>
# **DeleteDarSection**
> DeleteAliases200Response DeleteDarSection (int id)

DataAccessSection@destroy

Delete a system DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR section id |  |

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

<a id="fetchdarsection"></a>
# **FetchDarSection**
> FetchDarSection200Response FetchDarSection (int id)

DataAccessSection@show

Return a single DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR section id |  |

### Return type

[**FetchDarSection200Response**](FetchDarSection200Response.md)

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

<a id="fetchdarsections"></a>
# **FetchDarSections**
> FetchDarSections200Response FetchDarSections (int perPage = null)

DataAccessSection@index

List of DAR sections


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | per page | [optional]  |

### Return type

[**FetchDarSections200Response**](FetchDarSections200Response.md)

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

<a id="patchdarsection"></a>
# **PatchDarSection**
> FetchDarSection200Response PatchDarSection (int id, PatchDarSectionRequest patchDarSectionRequest)

DataAccessSection@update

Edit a system DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR section id |  |
| **patchDarSectionRequest** | [**PatchDarSectionRequest**](PatchDarSectionRequest.md) | DataAccessSection definition |  |

### Return type

[**FetchDarSection200Response**](FetchDarSection200Response.md)

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

<a id="updatedarsection"></a>
# **UpdateDarSection**
> FetchDarSection200Response UpdateDarSection (int id, CreateDarSectionRequest createDarSectionRequest)

DataAccessSection@update

Update a system DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR section id |  |
| **createDarSectionRequest** | [**CreateDarSectionRequest**](CreateDarSectionRequest.md) | DataAccessSection definition |  |

### Return type

[**FetchDarSection200Response**](FetchDarSection200Response.md)

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

