# GatewayApiSdk.Api.CollectionsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CountUniqueFieldsCollections**](CollectionsApi.md#countuniquefieldscollections) | **GET** /api/v1/collections/count/{field} | CollectionController@count |
| [**CountUniqueFieldsCollectionsV2**](CollectionsApi.md#countuniquefieldscollectionsv2) | **GET** /api/v2/collections/count/{field} | CollectionController@count |
| [**CreateCollections**](CollectionsApi.md#createcollections) | **POST** /api/v2/collections | CollectionController@store |
| [**DeleteCollectionsV2**](CollectionsApi.md#deletecollectionsv2) | **DELETE** /api/v2/collections/{id} | Delete a collection |
| [**EditCollectionsV2**](CollectionsApi.md#editcollectionsv2) | **PATCH** /api/v2/collections/{id} | Edit a collection |
| [**FetchAllCollections**](CollectionsApi.md#fetchallcollections) | **GET** /api/v1/collections | CollectionController@index |
| [**FetchAllCollectionsV2**](CollectionsApi.md#fetchallcollectionsv2) | **GET** /api/v2/collections | CollectionController@index |
| [**FetchCollections**](CollectionsApi.md#fetchcollections) | **GET** /api/v1/collections/{id} | CollectionController@show |
| [**FetchCollectionsV2**](CollectionsApi.md#fetchcollectionsv2) | **GET** /api/v2/collections/{id} | CollectionController@show |
| [**UpdateCollectionsV2**](CollectionsApi.md#updatecollectionsv2) | **PUT** /api/v2/collections/{id} | Update a collection |

<a id="countuniquefieldscollections"></a>
# **CountUniqueFieldsCollections**
> CountUniqueFieldsCollections200Response CountUniqueFieldsCollections (string field, int teamId, int userId)

CollectionController@count

Get Counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **field** | **string** | name of the field to perform a count on |  |
| **teamId** | **int** | team id |  |
| **userId** | **int** | user id |  |

### Return type

[**CountUniqueFieldsCollections200Response**](CountUniqueFieldsCollections200Response.md)

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

<a id="countuniquefieldscollectionsv2"></a>
# **CountUniqueFieldsCollectionsV2**
> CountUniqueFieldsCollections200Response CountUniqueFieldsCollectionsV2 (string field)

CollectionController@count

Get Counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **field** | **string** | name of the field to perform a count on |  |

### Return type

[**CountUniqueFieldsCollections200Response**](CountUniqueFieldsCollections200Response.md)

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

<a id="createcollections"></a>
# **CreateCollections**
> CreateDarIntegration201Response CreateCollections (CreateCollectionsRequest createCollectionsRequest)

CollectionController@store

Create a new collection owned by an individual


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createCollectionsRequest** | [**CreateCollectionsRequest**](CreateCollectionsRequest.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletecollectionsv2"></a>
# **DeleteCollectionsV2**
> DeleteApplications200Response DeleteCollectionsV2 (int id)

Delete a collection

Delete a collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |

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

<a id="editcollectionsv2"></a>
# **EditCollectionsV2**
> FetchCollections200Response EditCollectionsV2 (int id, EditCollectionsV2Request editCollectionsV2Request, string unarchive = null)

Edit a collection

Edit a collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |
| **editCollectionsV2Request** | [**EditCollectionsV2Request**](EditCollectionsV2Request.md) | Pass user credentials |  |
| **unarchive** | **string** | Unarchive a collection | [optional]  |

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

<a id="fetchallcollections"></a>
# **FetchAllCollections**
> FetchAllCollections200Response FetchAllCollections (string name = null, int teamId = null, int userId = null, string title = null, string status = null, int perPage = null)

CollectionController@index

Returns a list of collections


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **name** | **string** | Filter collections by name | [optional]  |
| **teamId** | **int** | Filter collections by team ID | [optional]  |
| **userId** | **int** | Filter collections by user ID | [optional]  |
| **title** | **string** | Filter collections by title | [optional]  |
| **status** | **string** | Filter collections by status (DRAFT, ACTIVE, ARCHIVED) | [optional]  |
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

<a id="fetchallcollectionsv2"></a>
# **FetchAllCollectionsV2**
> FetchAllCollections200Response FetchAllCollectionsV2 ()

CollectionController@index

Returns a list of collections


### Parameters
This endpoint does not need any parameter.
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

<a id="fetchcollections"></a>
# **FetchCollections**
> FetchCollections200Response FetchCollections (int id, string viewType = null)

CollectionController@show

Get collection by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |
| **viewType** | **string** | Query flag to show full collection data or a trimmed version (defaults to full). | [optional] [default to &quot;full&quot;] |

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

<a id="fetchcollectionsv2"></a>
# **FetchCollectionsV2**
> FetchCollections200Response FetchCollectionsV2 (int id, string viewType = null)

CollectionController@show

Get collection by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |
| **viewType** | **string** | Query flag to show full collection data or a trimmed version (defaults to full). | [optional] [default to &quot;full&quot;] |

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

<a id="updatecollectionsv2"></a>
# **UpdateCollectionsV2**
> FetchCollections200Response UpdateCollectionsV2 (int id, UpdateCollectionsV2Request updateCollectionsV2Request)

Update a collection

Update a collection owned by an individual


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |
| **updateCollectionsV2Request** | [**UpdateCollectionsV2Request**](UpdateCollectionsV2Request.md) | Pass user credentials |  |

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

