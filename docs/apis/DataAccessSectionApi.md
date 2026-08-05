# GatewayApiSdk.Api.DataAccessSectionApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateDarSection**](DataAccessSectionApi.md#createdarsection) | **POST** /api/v1/dar/sections | DataAccessSection@store |
| [**DeleteDarSection**](DataAccessSectionApi.md#deletedarsection) | **DELETE** /api/v1/dar/sections/{id} | DataAccessSection@destroy |
| [**PatchDarSection**](DataAccessSectionApi.md#patchdarsection) | **PATCH** /api/v1/dar/sections/{id} | DataAccessSection@update |
| [**UpdateDarSection**](DataAccessSectionApi.md#updatedarsection) | **PUT** /api/v1/dar/sections/{id} | DataAccessSection@update |

<a id="createdarsection"></a>
# **CreateDarSection**
> CreateDarIntegration201Response CreateDarSection (CreateDarSectionRequest createDarSectionRequest)

DataAccessSection@store

Creates a new DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createDarSectionRequest** | [**CreateDarSectionRequest**](CreateDarSectionRequest.md) | DataAccessSection definition |  |

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

<a id="deletedarsection"></a>
# **DeleteDarSection**
> DeleteApplications200Response DeleteDarSection (int id)

DataAccessSection@destroy

Delete a system DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR section id |  |

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

<a id="patchdarsection"></a>
# **PatchDarSection**
> UpdateDarSection200Response PatchDarSection (int id, PatchDarSectionRequest patchDarSectionRequest)

DataAccessSection@update

Edit a system DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR section id |  |
| **patchDarSectionRequest** | [**PatchDarSectionRequest**](PatchDarSectionRequest.md) | DataAccessSection definition |  |

### Return type

[**UpdateDarSection200Response**](UpdateDarSection200Response.md)

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
> UpdateDarSection200Response UpdateDarSection (int id, CreateDarSectionRequest createDarSectionRequest)

DataAccessSection@update

Update a system DAR section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR section id |  |
| **createDarSectionRequest** | [**CreateDarSectionRequest**](CreateDarSectionRequest.md) | DataAccessSection definition |  |

### Return type

[**UpdateDarSection200Response**](UpdateDarSection200Response.md)

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

