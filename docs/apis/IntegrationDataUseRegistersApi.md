# GatewayApiSdk.Api.IntegrationDataUseRegistersApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateDurIntegrations**](IntegrationDataUseRegistersApi.md#createdurintegrations) | **POST** /api/v1/integrations/dur | IntegrationDurController@store |
| [**DeleteDurIntegrations**](IntegrationDataUseRegistersApi.md#deletedurintegrations) | **DELETE** /api/v1/integrations/dur/{id} | Delete a dur |
| [**EditDurIntegrations**](IntegrationDataUseRegistersApi.md#editdurintegrations) | **PATCH** /api/v1/integrations/dur/{id} | Edit a dur |
| [**FetchAllDurIntegrations**](IntegrationDataUseRegistersApi.md#fetchalldurintegrations) | **GET** /api/v1/integrations/dur | IntegrationDurController@index |
| [**FetchDurByIdIntegrations**](IntegrationDataUseRegistersApi.md#fetchdurbyidintegrations) | **GET** /api/v1/integrations/dur/{id} | IntegrationDurController@show |
| [**UpdateDurIntegrations**](IntegrationDataUseRegistersApi.md#updatedurintegrations) | **PUT** /api/v1/integrations/dur/{id} | Update a dur by id |

<a id="createdurintegrations"></a>
# **CreateDurIntegrations**
> CreateCategories200Response CreateDurIntegrations (CreateDurIntegrationsRequest createDurIntegrationsRequest)

IntegrationDurController@store

Create a new dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createDurIntegrationsRequest** | [**CreateDurIntegrationsRequest**](CreateDurIntegrationsRequest.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletedurintegrations"></a>
# **DeleteDurIntegrations**
> DeleteAliases200Response DeleteDurIntegrations (int id)

Delete a dur

Delete a dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dur id |  |

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

<a id="editdurintegrations"></a>
# **EditDurIntegrations**
> UpdateDurIntegrations200Response EditDurIntegrations (int id, CreateDurIntegrationsRequest createDurIntegrationsRequest)

Edit a dur

Edit a dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dur id |  |
| **createDurIntegrationsRequest** | [**CreateDurIntegrationsRequest**](CreateDurIntegrationsRequest.md) | Pass user credentials |  |

### Return type

[**UpdateDurIntegrations200Response**](UpdateDurIntegrations200Response.md)

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

<a id="fetchalldurintegrations"></a>
# **FetchAllDurIntegrations**
> FetchAllDurIntegrations200Response FetchAllDurIntegrations (ProjectTitleAscupdatedAtAsc sort = null, int perPage = null)

IntegrationDurController@index

Returns a list of dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **sort** | [**ProjectTitleAscupdatedAtAsc**](ProjectTitleAscupdatedAtAsc.md) | Sort fields in the format field:direction, e.g., project_title:asc,updated_at:asc | [optional]  |
| **perPage** | **int** | per page | [optional]  |

### Return type

[**FetchAllDurIntegrations200Response**](FetchAllDurIntegrations200Response.md)

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

<a id="fetchdurbyidintegrations"></a>
# **FetchDurByIdIntegrations**
> FetchDurByIdIntegrations200Response FetchDurByIdIntegrations (int id)

IntegrationDurController@show

Get dur by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | data use register id |  |

### Return type

[**FetchDurByIdIntegrations200Response**](FetchDurByIdIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updatedurintegrations"></a>
# **UpdateDurIntegrations**
> UpdateDurIntegrations200Response UpdateDurIntegrations (int id, CreateDurIntegrationsRequest createDurIntegrationsRequest)

Update a dur by id

Update a dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dur id |  |
| **createDurIntegrationsRequest** | [**CreateDurIntegrationsRequest**](CreateDurIntegrationsRequest.md) | Pass user credentials |  |

### Return type

[**UpdateDurIntegrations200Response**](UpdateDurIntegrations200Response.md)

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

