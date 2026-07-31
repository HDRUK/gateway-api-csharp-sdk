# GatewayApiSdk.Api.IntegrationDataUseRegistersApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call3c0f53b5284c481bc135c2035d40c017**](IntegrationDataUseRegistersApi.md#call3c0f53b5284c481bc135c2035d40c017) | **PATCH** /api/v1/integrations/dur/{id} | Edit a dur |
| [**Call3c79eaaecaae1de1b86c443337841895**](IntegrationDataUseRegistersApi.md#call3c79eaaecaae1de1b86c443337841895) | **PUT** /api/v1/integrations/dur/{id} | Update a dur by id |
| [**Call7170e7dc71293d3b5042d6cb03298eb4**](IntegrationDataUseRegistersApi.md#call7170e7dc71293d3b5042d6cb03298eb4) | **DELETE** /api/v1/integrations/dur/{id} | Delete a dur |
| [**CreateDurIntegrations**](IntegrationDataUseRegistersApi.md#createdurintegrations) | **POST** /api/v1/integrations/dur | IntegrationDurController@store |
| [**FetchAllDurIntegrations**](IntegrationDataUseRegistersApi.md#fetchalldurintegrations) | **GET** /api/v1/integrations/dur | IntegrationDurController@index |
| [**FetchDurByIdIntegrations**](IntegrationDataUseRegistersApi.md#fetchdurbyidintegrations) | **GET** /api/v1/integrations/dur/{id} | IntegrationDurController@show |

<a id="call3c0f53b5284c481bc135c2035d40c017"></a>
# **Call3c0f53b5284c481bc135c2035d40c017**
> Model3c79eaaecaae1de1b86c443337841895200Response Call3c0f53b5284c481bc135c2035d40c017 (int id, CreateDurIntegrationsRequest createDurIntegrationsRequest)

Edit a dur

Edit a dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dur id |  |
| **createDurIntegrationsRequest** | [**CreateDurIntegrationsRequest**](CreateDurIntegrationsRequest.md) | Pass user credentials |  |

### Return type

[**Model3c79eaaecaae1de1b86c443337841895200Response**](Model3c79eaaecaae1de1b86c443337841895200Response.md)

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

<a id="call3c79eaaecaae1de1b86c443337841895"></a>
# **Call3c79eaaecaae1de1b86c443337841895**
> Model3c79eaaecaae1de1b86c443337841895200Response Call3c79eaaecaae1de1b86c443337841895 (int id, CreateDurIntegrationsRequest createDurIntegrationsRequest)

Update a dur by id

Update a dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dur id |  |
| **createDurIntegrationsRequest** | [**CreateDurIntegrationsRequest**](CreateDurIntegrationsRequest.md) | Pass user credentials |  |

### Return type

[**Model3c79eaaecaae1de1b86c443337841895200Response**](Model3c79eaaecaae1de1b86c443337841895200Response.md)

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

<a id="call7170e7dc71293d3b5042d6cb03298eb4"></a>
# **Call7170e7dc71293d3b5042d6cb03298eb4**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call7170e7dc71293d3b5042d6cb03298eb4 (int id)

Delete a dur

Delete a dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dur id |  |

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

<a id="createdurintegrations"></a>
# **CreateDurIntegrations**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateDurIntegrations (CreateDurIntegrationsRequest createDurIntegrationsRequest)

IntegrationDurController@store

Create a new dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createDurIntegrationsRequest** | [**CreateDurIntegrationsRequest**](CreateDurIntegrationsRequest.md) | Pass user credentials |  |

### Return type

[**Dd76b8d73b7ea8b4951f03d7c0904c92200Response**](Dd76b8d73b7ea8b4951f03d7c0904c92200Response.md)

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

