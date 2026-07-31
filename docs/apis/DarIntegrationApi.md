# GatewayApiSdk.Api.DarIntegrationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateDarIntegration**](DarIntegrationApi.md#createdarintegration) | **POST** /api/v1/dar-integration/{id} | DarIntegration@store |
| [**DeleteDarIntegration**](DarIntegrationApi.md#deletedarintegration) | **DELETE** /api/v1/dar-integrations/{id} | DarIntegration@destroy |
| [**EditDarIntegration**](DarIntegrationApi.md#editdarintegration) | **PATCH** /api/v1/dar-integration/{id} | DarIntegration@edit |
| [**FetchAllDarIntegrations**](DarIntegrationApi.md#fetchalldarintegrations) | **GET** /api/v1/dar-integration | DarIntegration@index |
| [**FetchDarIntegration**](DarIntegrationApi.md#fetchdarintegration) | **GET** /api/v1/dar-integration/{id} | DarIntegration@show |
| [**UpdateDarIntegration**](DarIntegrationApi.md#updatedarintegration) | **PUT** /api/v1/dar-integration/{id} | DarIntegration@update |

<a id="createdarintegration"></a>
# **CreateDarIntegration**
> CreateCategories200Response CreateDarIntegration (int id, UpdateDarIntegrationRequest updateDarIntegrationRequest)

DarIntegration@store

Creates a new DAR integration enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dar integration id |  |
| **updateDarIntegrationRequest** | [**UpdateDarIntegrationRequest**](UpdateDarIntegrationRequest.md) | DarIntegration definition |  |

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

<a id="deletedarintegration"></a>
# **DeleteDarIntegration**
> DeleteAliases200Response DeleteDarIntegration (int id)

DarIntegration@destroy

Delete a system Dar Integration


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dar integration id |  |

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

<a id="editdarintegration"></a>
# **EditDarIntegration**
> UpdateDarIntegration200Response EditDarIntegration (int id, EditDarIntegrationRequest editDarIntegrationRequest)

DarIntegration@edit

Edit a DAR integration enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dar integration id |  |
| **editDarIntegrationRequest** | [**EditDarIntegrationRequest**](EditDarIntegrationRequest.md) | DarIntegration definition |  |

### Return type

[**UpdateDarIntegration200Response**](UpdateDarIntegration200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Updated |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchalldarintegrations"></a>
# **FetchAllDarIntegrations**
> FetchAllDarIntegrations200Response FetchAllDarIntegrations ()

DarIntegration@index

Returns a list of DAR integrations enabled on the system


### Parameters
This endpoint does not need any parameter.
### Return type

[**FetchAllDarIntegrations200Response**](FetchAllDarIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdarintegration"></a>
# **FetchDarIntegration**
> FetchAllDarIntegrations200ResponseDataInner FetchDarIntegration (int id)

DarIntegration@show

Returns a single DAR integration enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dar integration id |  |

### Return type

[**FetchAllDarIntegrations200ResponseDataInner**](FetchAllDarIntegrations200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updatedarintegration"></a>
# **UpdateDarIntegration**
> UpdateDarIntegration200Response UpdateDarIntegration (int id, UpdateDarIntegrationRequest updateDarIntegrationRequest)

DarIntegration@update

Updates a DAR integration enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dar integration id |  |
| **updateDarIntegrationRequest** | [**UpdateDarIntegrationRequest**](UpdateDarIntegrationRequest.md) | DarIntegration definition |  |

### Return type

[**UpdateDarIntegration200Response**](UpdateDarIntegration200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Updated |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

