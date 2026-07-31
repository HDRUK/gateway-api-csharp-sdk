# GatewayApiSdk.Api.IntegrationCollectionsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateCollectionsIntegrations**](IntegrationCollectionsApi.md#createcollectionsintegrations) | **POST** /api/v1/integrations/collections | IntegrationCollectionController@store |
| [**DeleteCollectionsIntegrations**](IntegrationCollectionsApi.md#deletecollectionsintegrations) | **DELETE** /api/v1/integrations/collections/{id} | Delete a collection |
| [**EditCollectionsIntegrations**](IntegrationCollectionsApi.md#editcollectionsintegrations) | **PATCH** /api/v1/integrations/collections/{id} | Edit a collection |
| [**FetchAllCollectionsIntegrations**](IntegrationCollectionsApi.md#fetchallcollectionsintegrations) | **GET** /api/v1/integrations/collections | IntegrationCollectionController@index |
| [**FetchCollectionsIntegrations**](IntegrationCollectionsApi.md#fetchcollectionsintegrations) | **GET** /api/v1/integrations/collections/{id} | IntegrationCollectionController@show |
| [**UpdateCollectionsIntegrations**](IntegrationCollectionsApi.md#updatecollectionsintegrations) | **PUT** /api/v1/integrations/collections/{id} | Update a collection |

<a id="createcollectionsintegrations"></a>
# **CreateCollectionsIntegrations**
> CreateCategories200Response CreateCollectionsIntegrations (UpdateTeamCollectionsRequest updateTeamCollectionsRequest)

IntegrationCollectionController@store

Create a new collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **updateTeamCollectionsRequest** | [**UpdateTeamCollectionsRequest**](UpdateTeamCollectionsRequest.md) | Pass user credentials |  |

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

<a id="deletecollectionsintegrations"></a>
# **DeleteCollectionsIntegrations**
> DeleteAliases200Response DeleteCollectionsIntegrations (int id)

Delete a collection

Delete a collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |

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

<a id="editcollectionsintegrations"></a>
# **EditCollectionsIntegrations**
> FetchCollections200Response EditCollectionsIntegrations (int id, UpdateTeamCollectionsRequest updateTeamCollectionsRequest)

Edit a collection

Edit a collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |
| **updateTeamCollectionsRequest** | [**UpdateTeamCollectionsRequest**](UpdateTeamCollectionsRequest.md) | Pass user credentials |  |

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

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

<a id="fetchallcollectionsintegrations"></a>
# **FetchAllCollectionsIntegrations**
> FetchAllCollections200Response FetchAllCollectionsIntegrations (string name = null, int perPage = null)

IntegrationCollectionController@index

Returns a list of collections


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **name** | **string** | Filter collections by name | [optional]  |
| **perPage** | **int** | per page | [optional]  |

### Return type

[**FetchAllCollections200Response**](FetchAllCollections200Response.md)

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

<a id="fetchcollectionsintegrations"></a>
# **FetchCollectionsIntegrations**
> FetchCollections200Response FetchCollectionsIntegrations (int id)

IntegrationCollectionController@show

Get collection by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

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

<a id="updatecollectionsintegrations"></a>
# **UpdateCollectionsIntegrations**
> FetchCollections200Response UpdateCollectionsIntegrations (int id, UpdateTeamCollectionsRequest updateTeamCollectionsRequest)

Update a collection

Update a collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |
| **updateTeamCollectionsRequest** | [**UpdateTeamCollectionsRequest**](UpdateTeamCollectionsRequest.md) | Pass user credentials |  |

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

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

