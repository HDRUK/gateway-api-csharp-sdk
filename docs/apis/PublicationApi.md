# GatewayApiSdk.Api.PublicationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CountTeamUniqueFieldsPublicationV2**](PublicationApi.md#countteamuniquefieldspublicationv2) | **GET** /api/v2/teams/{teamId}/publications/count/{field} | TeamPublicationController@count |
| [**CountUniqueFieldsPublications**](PublicationApi.md#countuniquefieldspublications) | **GET** /api/v1/publication/count/{field} | PublicationController@count |
| [**CountUserUniqueFieldsPublicationV2**](PublicationApi.md#countuseruniquefieldspublicationv2) | **GET** /api/v2/users/{userId}/publications/count/{field} | UserPublicationController@count |
| [**CreatePublications**](PublicationApi.md#createpublications) | **POST** /api/v1/publications | PublicationController@store |
| [**CreatePublicationsV2ByTeamId**](PublicationApi.md#createpublicationsv2byteamid) | **POST** /api/v2/teams/{teamId}/publications | TeamPublicationController@store |
| [**CreatePublicationsV2ByUserId**](PublicationApi.md#createpublicationsv2byuserid) | **POST** /api/v2/users/{userId}/publications | UserPublicationController@store |
| [**DeletePublications**](PublicationApi.md#deletepublications) | **DELETE** /api/v1/publications/{id} | PublicationController@destroy |
| [**DeletePublicationsV2ByTeamId**](PublicationApi.md#deletepublicationsv2byteamid) | **DELETE** /api/v2/teams/{teamId}/publications/{id} | TeamPublicationController@destroy |
| [**DeletePublicationsV2ByUserId**](PublicationApi.md#deletepublicationsv2byuserid) | **DELETE** /api/v2/users/{userId}/publications/{id} | UserPublicationController@destroy |
| [**EditPublications**](PublicationApi.md#editpublications) | **PATCH** /api/v1/publications/{id} | PublicationController@edit |
| [**EditPublicationsV2ByTeamId**](PublicationApi.md#editpublicationsv2byteamid) | **PATCH** /api/v2/teams/{teamId}/publications/{id} | TeamPublicationController@edit |
| [**EditPublicationsV2ByUserId**](PublicationApi.md#editpublicationsv2byuserid) | **PATCH** /api/v2/users/{userId}/publications/{id} | UserPublicationController@edit |
| [**FetchAllPublications**](PublicationApi.md#fetchallpublications) | **GET** /api/v1/publications | PublicationController@index |
| [**FetchAllPublicationsByTeamAndStatusV2**](PublicationApi.md#fetchallpublicationsbyteamandstatusv2) | **GET** /api/v2/teams/{teamId}/publications/status/{status} | TeamPublicationController@indexStatus |
| [**FetchAllPublicationsByUserAndStatusV2**](PublicationApi.md#fetchallpublicationsbyuserandstatusv2) | **GET** /api/v2/users/{userId}/publications/{status} | UserPublicationController@indexStatus |
| [**FetchAllPublicationsV2**](PublicationApi.md#fetchallpublicationsv2) | **GET** /api/v2/publications | PublicationController@indexActive |
| [**FetchPublications**](PublicationApi.md#fetchpublications) | **GET** /api/v1/publications/{id} | PublicationController@show |
| [**FetchPublicationsByTeamAndByIdV2**](PublicationApi.md#fetchpublicationsbyteamandbyidv2) | **GET** /api/v2/teams/{teamId}/publications/{id} | TeamPublicationController@show |
| [**FetchPublicationsByUserAndByIdV2**](PublicationApi.md#fetchpublicationsbyuserandbyidv2) | **GET** /api/v2/users/{userId}/publications/{id} | UserPublicationController@show |
| [**FetchPublicationsV2**](PublicationApi.md#fetchpublicationsv2) | **GET** /api/v2/publications/{id} | PublicationController@showActive |
| [**UpdatePublications**](PublicationApi.md#updatepublications) | **PUT** /api/v1/publications/{id} | PublicationController@update |
| [**UpdatePublicationsV2ByTeamId**](PublicationApi.md#updatepublicationsv2byteamid) | **PUT** /api/v2/teams/{teamId}/publications/{id} | TeamPublicationController@update |
| [**UpdatePublicationsV2ByUserId**](PublicationApi.md#updatepublicationsv2byuserid) | **PUT** /api/v2/users/{userId}/publications/{id} | UserPublicationController@update |

<a id="countteamuniquefieldspublicationv2"></a>
# **CountTeamUniqueFieldsPublicationV2**
> CountUniqueFieldsCollections200Response CountTeamUniqueFieldsPublicationV2 (int teamId, string field)

TeamPublicationController@count

Get team counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="countuseruniquefieldspublicationv2"></a>
# **CountUserUniqueFieldsPublicationV2**
> CountUniqueFieldsCollections200Response CountUserUniqueFieldsPublicationV2 (int userId, string field)

UserPublicationController@count

Get user counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
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

<a id="createpublications"></a>
# **CreatePublications**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreatePublications (CreatePublicationsRequest createPublicationsRequest)

PublicationController@store

Create a new publication


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createPublicationsRequest** | [**CreatePublicationsRequest**](CreatePublicationsRequest.md) | Pass user credentials |  |

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

<a id="createpublicationsv2byteamid"></a>
# **CreatePublicationsV2ByTeamId**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreatePublicationsV2ByTeamId (int teamId, CreatePublicationsRequest createPublicationsRequest)

TeamPublicationController@store

Create a new publication by team id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **createPublicationsRequest** | [**CreatePublicationsRequest**](CreatePublicationsRequest.md) | Pass user credentials |  |

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

<a id="createpublicationsv2byuserid"></a>
# **CreatePublicationsV2ByUserId**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreatePublicationsV2ByUserId (long userId, CreatePublicationsRequest createPublicationsRequest)

UserPublicationController@store

Create a new publication by user id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **long** | ID of the user |  |
| **createPublicationsRequest** | [**CreatePublicationsRequest**](CreatePublicationsRequest.md) | Pass user credentials |  |

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

<a id="deletepublicationsv2byteamid"></a>
# **DeletePublicationsV2ByTeamId**
> DeleteFederation200Response DeletePublicationsV2ByTeamId (int teamId, int id)

TeamPublicationController@destroy

Delete publication by team id and id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="deletepublicationsv2byuserid"></a>
# **DeletePublicationsV2ByUserId**
> DeleteFederation200Response DeletePublicationsV2ByUserId (long userId, int id)

UserPublicationController@destroy

Delete publication by user id and id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **long** | ID of the user |  |
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

<a id="editpublicationsv2byteamid"></a>
# **EditPublicationsV2ByTeamId**
> FetchPublications200Response EditPublicationsV2ByTeamId (int teamId, int id, UpdatePublicationsRequest updatePublicationsRequest)

TeamPublicationController@edit

Edit publications by team id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | publications id |  |
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

<a id="editpublicationsv2byuserid"></a>
# **EditPublicationsV2ByUserId**
> FetchPublications200Response EditPublicationsV2ByUserId (long userId, int id, UpdatePublicationsRequest updatePublicationsRequest)

UserPublicationController@edit

Edit publications by user id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **long** | ID of the user |  |
| **id** | **int** | publications id |  |
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

<a id="fetchallpublicationsbyteamandstatusv2"></a>
# **FetchAllPublicationsByTeamAndStatusV2**
> FetchAllPublications200Response FetchAllPublicationsByTeamAndStatusV2 (long teamId, string status, string paperTitle = null)

TeamPublicationController@indexStatus

Returns a list of a teams publications


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **long** | ID of the team |  |
| **status** | **string** | Status of the team (active, draft, or archived). Defaults to active if not provided. | [default to active] |
| **paperTitle** | **string** | Filter Publication by title | [optional]  |

### Return type

[**FetchAllPublications200Response**](FetchAllPublications200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchallpublicationsbyuserandstatusv2"></a>
# **FetchAllPublicationsByUserAndStatusV2**
> FetchAllPublications200Response FetchAllPublicationsByUserAndStatusV2 (long userId, string status, string paperTitle = null)

UserPublicationController@indexStatus

Returns a list of a users publications


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **long** | ID of the user |  |
| **status** | **string** | Status of the team (active, draft, or archived). Defaults to active if not provided. | [default to active] |
| **paperTitle** | **string** | Filter Publication by title | [optional]  |

### Return type

[**FetchAllPublications200Response**](FetchAllPublications200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **404** | Not Found |  -  |

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

<a id="fetchpublicationsbyteamandbyidv2"></a>
# **FetchPublicationsByTeamAndByIdV2**
> FetchPublications200Response FetchPublicationsByTeamAndByIdV2 (int teamId, int id)

TeamPublicationController@show

Get publication by team id and by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="fetchpublicationsbyuserandbyidv2"></a>
# **FetchPublicationsByUserAndByIdV2**
> FetchPublications200Response FetchPublicationsByUserAndByIdV2 (long userId, int id)

UserPublicationController@show

Get publication by user id and by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **long** | ID of the user |  |
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

<a id="updatepublicationsv2byteamid"></a>
# **UpdatePublicationsV2ByTeamId**
> FetchPublications200Response UpdatePublicationsV2ByTeamId (int teamId, int id, UpdatePublicationsRequest updatePublicationsRequest)

TeamPublicationController@update

Update publications by team id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="updatepublicationsv2byuserid"></a>
# **UpdatePublicationsV2ByUserId**
> FetchPublications200Response UpdatePublicationsV2ByUserId (long userId, int id, UpdatePublicationsRequest updatePublicationsRequest)

UserPublicationController@update

Update publications by user id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **long** | ID of the user |  |
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

