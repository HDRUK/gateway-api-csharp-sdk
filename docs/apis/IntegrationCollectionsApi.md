# GatewayApiSdk.Api.IntegrationCollectionsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call03c4b87e83a5e290cee5b9bfd43f9b0d**](IntegrationCollectionsApi.md#call03c4b87e83a5e290cee5b9bfd43f9b0d) | **PUT** /api/v1/integrations/collections/{id} | Update a collection |
| [**Call9909f9e058a98d63144b44938dbb0939**](IntegrationCollectionsApi.md#call9909f9e058a98d63144b44938dbb0939) | **DELETE** /api/v1/integrations/collections/{id} | Delete a collection |
| [**CreateCollectionsIntegrations**](IntegrationCollectionsApi.md#createcollectionsintegrations) | **POST** /api/v1/integrations/collections | IntegrationCollectionController@store |
| [**E935d442a0adfe7fa4fffabbfd45512c**](IntegrationCollectionsApi.md#e935d442a0adfe7fa4fffabbfd45512c) | **PATCH** /api/v1/integrations/collections/{id} | Edit a collection |
| [**FetchAllCollectionsIntegrations**](IntegrationCollectionsApi.md#fetchallcollectionsintegrations) | **GET** /api/v1/integrations/collections | IntegrationCollectionController@index |
| [**FetchCollectionsIntegrations**](IntegrationCollectionsApi.md#fetchcollectionsintegrations) | **GET** /api/v1/integrations/collections/{id} | IntegrationCollectionController@show |

<a id="call03c4b87e83a5e290cee5b9bfd43f9b0d"></a>
# **Call03c4b87e83a5e290cee5b9bfd43f9b0d**
> FetchCollections200Response Call03c4b87e83a5e290cee5b9bfd43f9b0d (int id, A18eed83ffe8ac895df3e1efa5ffb421Request a18eed83ffe8ac895df3e1efa5ffb421Request)

Update a collection

Update a collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |
| **a18eed83ffe8ac895df3e1efa5ffb421Request** | [**A18eed83ffe8ac895df3e1efa5ffb421Request**](A18eed83ffe8ac895df3e1efa5ffb421Request.md) | Pass user credentials |  |

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

<a id="call9909f9e058a98d63144b44938dbb0939"></a>
# **Call9909f9e058a98d63144b44938dbb0939**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call9909f9e058a98d63144b44938dbb0939 (int id)

Delete a collection

Delete a collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |

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

<a id="createcollectionsintegrations"></a>
# **CreateCollectionsIntegrations**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateCollectionsIntegrations (A18eed83ffe8ac895df3e1efa5ffb421Request a18eed83ffe8ac895df3e1efa5ffb421Request)

IntegrationCollectionController@store

Create a new collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **a18eed83ffe8ac895df3e1efa5ffb421Request** | [**A18eed83ffe8ac895df3e1efa5ffb421Request**](A18eed83ffe8ac895df3e1efa5ffb421Request.md) | Pass user credentials |  |

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

<a id="e935d442a0adfe7fa4fffabbfd45512c"></a>
# **E935d442a0adfe7fa4fffabbfd45512c**
> FetchCollections200Response E935d442a0adfe7fa4fffabbfd45512c (int id, A18eed83ffe8ac895df3e1efa5ffb421Request a18eed83ffe8ac895df3e1efa5ffb421Request)

Edit a collection

Edit a collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |
| **a18eed83ffe8ac895df3e1efa5ffb421Request** | [**A18eed83ffe8ac895df3e1efa5ffb421Request**](A18eed83ffe8ac895df3e1efa5ffb421Request.md) | Pass user credentials |  |

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

