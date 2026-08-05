# GatewayApiSdk.Api.PublicationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CountUniqueFieldsPublications**](PublicationApi.md#countuniquefieldspublications) | **GET** /api/v1/publication/count/{field} | PublicationController@count |
| [**CreatePublications**](PublicationApi.md#createpublications) | **POST** /api/v1/publications | PublicationController@store |
| [**DeletePublications**](PublicationApi.md#deletepublications) | **DELETE** /api/v1/publications/{id} | PublicationController@destroy |
| [**EditPublications**](PublicationApi.md#editpublications) | **PATCH** /api/v1/publications/{id} | PublicationController@edit |
| [**FetchAllPublications**](PublicationApi.md#fetchallpublications) | **GET** /api/v1/publications | PublicationController@index |
| [**FetchAllPublicationsV2**](PublicationApi.md#fetchallpublicationsv2) | **GET** /api/v2/publications | PublicationController@indexActive |
| [**FetchPublications**](PublicationApi.md#fetchpublications) | **GET** /api/v1/publications/{id} | PublicationController@show |
| [**FetchPublicationsV2**](PublicationApi.md#fetchpublicationsv2) | **GET** /api/v2/publications/{id} | PublicationController@showActive |
| [**UpdatePublications**](PublicationApi.md#updatepublications) | **PUT** /api/v1/publications/{id} | PublicationController@update |

<a id="countuniquefieldspublications"></a>
# **CountUniqueFieldsPublications**
> CountUniqueFieldsCollections200Response CountUniqueFieldsPublications (string field, int ownerId, int teamId = null)

PublicationController@count

Get Counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **field** | **string** | name of the field to perform a count on |  |
| **ownerId** | **int** | owner id |  |
| **teamId** | **int** |  | [optional]  |

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

<a id="createpublications"></a>
# **CreatePublications**
> CreateDarIntegration201Response CreatePublications (CreatePublicationsRequest createPublicationsRequest)

PublicationController@store

Create a new publication


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createPublicationsRequest** | [**CreatePublicationsRequest**](CreatePublicationsRequest.md) | Pass user credentials |  |

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

<a id="deletepublications"></a>
# **DeletePublications**
> DeleteFederation200Response DeletePublications (int id)

PublicationController@destroy

Delete publication by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | publication id |  |

### Return type

[**DeleteFederation200Response**](DeleteFederation200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Error response |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="editpublications"></a>
# **EditPublications**
> FetchPublications200Response EditPublications (int id, UpdatePublicationsRequest updatePublicationsRequest, string unarchive = null)

PublicationController@edit

Edit publications


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | publications id |  |
| **updatePublicationsRequest** | [**UpdatePublicationsRequest**](UpdatePublicationsRequest.md) | Pass user credentials |  |
| **unarchive** | **string** | Unarchive a publication | [optional]  |

### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **400** | Error |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchallpublications"></a>
# **FetchAllPublications**
> FetchAllPublications200Response FetchAllPublications (string paperTitle = null, Int ownerId = null, Int teamId = null, string status = null)

PublicationController@index

Get All Publications


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **paperTitle** | **string** | Filter tools by paper title | [optional]  |
| **ownerId** | [**Int**](Int.md) | Filter tools by owner id | [optional]  |
| **teamId** | [**Int**](Int.md) | Filter tools by team id | [optional]  |
| **status** | **string** | Publication status to filter by (&#39;ACTIVE&#39;, &#39;DRAFT&#39;, &#39;ARCHIVED&#39;) | [optional]  |

### Return type

[**FetchAllPublications200Response**](FetchAllPublications200Response.md)

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

<a id="fetchallpublicationsv2"></a>
# **FetchAllPublicationsV2**
> FetchAllPublications200Response FetchAllPublicationsV2 (string paperTitle = null, bool withRelated = null, int perPage = null)

PublicationController@indexActive

Get All Publications


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **paperTitle** | **string** | Filter tools by paper title | [optional]  |
| **withRelated** | **bool** | Return related datasets | [optional]  |
| **perPage** | **int** | per page | [optional]  |

### Return type

[**FetchAllPublications200Response**](FetchAllPublications200Response.md)

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

<a id="fetchpublications"></a>
# **FetchPublications**
> FetchPublications200Response FetchPublications (int id)

PublicationController@show

Get publication by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | publication id |  |

### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchpublicationsv2"></a>
# **FetchPublicationsV2**
> FetchPublications200Response FetchPublicationsV2 (int id)

PublicationController@showActive

Get publication by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | publication id |  |

### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updatepublications"></a>
# **UpdatePublications**
> FetchPublications200Response UpdatePublications (int id, UpdatePublicationsRequest updatePublicationsRequest)

PublicationController@update

Update publications


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | publication id |  |
| **updatePublicationsRequest** | [**UpdatePublicationsRequest**](UpdatePublicationsRequest.md) | Pass user credentials |  |

### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **400** | Error |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

