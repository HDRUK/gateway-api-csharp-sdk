# GatewayApiSdk.Api.CollectionsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CountTeamUniqueFieldsCollectionV2**](CollectionsApi.md#countteamuniquefieldscollectionv2) | **GET** /api/v2/teams/{teamId}/collections/count/{field} | TeamCollectionController@count |
| [**CountUniqueFieldsCollections**](CollectionsApi.md#countuniquefieldscollections) | **GET** /api/v1/collections/count/{field} | CollectionController@count |
| [**CountUniqueFieldsCollectionsV2**](CollectionsApi.md#countuniquefieldscollectionsv2) | **GET** /api/v2/collections/count/{field} | CollectionController@count |
| [**CountUserUniqueFieldsCollectionV2**](CollectionsApi.md#countuseruniquefieldscollectionv2) | **GET** /api/v2/users/{userId}/collections/count/{field} | UserCollectionController@count |
| [**CreateCollections**](CollectionsApi.md#createcollections) | **POST** /api/v2/collections | CollectionController@store |
| [**CreateTeamCollections**](CollectionsApi.md#createteamcollections) | **POST** /api/v1/teams/{teamId}/collections | CollectionController@store |
| [**CreateTeamCollectionsV2**](CollectionsApi.md#createteamcollectionsv2) | **POST** /api/v2/teams/{teamId}/collections | TeamCollectionController@store |
| [**CreateUserCollections**](CollectionsApi.md#createusercollections) | **POST** /api/v2/users/collections | UserCollectionController@store |
| [**DeleteCollectionsV2**](CollectionsApi.md#deletecollectionsv2) | **DELETE** /api/v2/collections/{id} | Delete a collection |
| [**DeleteTeamCollections**](CollectionsApi.md#deleteteamcollections) | **DELETE** /api/v1/teams/{teamId}/collections/{id} | Delete a collection |
| [**DeleteTeamCollectionsV2**](CollectionsApi.md#deleteteamcollectionsv2) | **DELETE** /api/v2/teams/{teamId}/collections/{id} | Delete a collection |
| [**DeleteUserCollectionsV2**](CollectionsApi.md#deleteusercollectionsv2) | **DELETE** /api/v2/users/{userId}/collections/{id} | Delete a collection |
| [**EditCollectionsV2**](CollectionsApi.md#editcollectionsv2) | **PATCH** /api/v2/collections/{id} | Edit a collection |
| [**EditTeamCollections**](CollectionsApi.md#editteamcollections) | **PATCH** /api/v1/teams/{teamId}/collections/{id} | Edit a collection |
| [**EditTeamCollectionsV2**](CollectionsApi.md#editteamcollectionsv2) | **PATCH** /api/v2/teams/{teamId}/collections/{id} | Edit a collection |
| [**EditUserCollectionsV2**](CollectionsApi.md#editusercollectionsv2) | **PATCH** /api/v2/users/{userId}/collections/{id} | Edit a collection |
| [**FetchAllCollections**](CollectionsApi.md#fetchallcollections) | **GET** /api/v1/collections | CollectionController@index |
| [**FetchAllCollectionsV2**](CollectionsApi.md#fetchallcollectionsv2) | **GET** /api/v2/collections | CollectionController@index |
| [**FetchCollections**](CollectionsApi.md#fetchcollections) | **GET** /api/v1/collections/{id} | CollectionController@show |
| [**FetchCollectionsV2**](CollectionsApi.md#fetchcollectionsv2) | **GET** /api/v2/collections/{id} | CollectionController@show |
| [**FetchTeamActiveCollectionsV2**](CollectionsApi.md#fetchteamactivecollectionsv2) | **GET** /api/v2/teams/{teamId}/collections/status/active | TeamCollectionController@indexActive |
| [**FetchTeamArchivedCollectionsV2**](CollectionsApi.md#fetchteamarchivedcollectionsv2) | **GET** /api/v2/teams/{teamId}/collections/status/archived | TeamCollectionController@indexArchived |
| [**FetchTeamCollectionV2**](CollectionsApi.md#fetchteamcollectionv2) | **GET** /api/v2/teams/{teamId}/collections/{id} | TeamCollectionController@show |
| [**FetchTeamDraftCollectionsV2**](CollectionsApi.md#fetchteamdraftcollectionsv2) | **GET** /api/v2/teams/{teamId}/collections/status/draft | TeamCollectionController@indexDraft |
| [**FetchUserArchivedCollectionsV2**](CollectionsApi.md#fetchuserarchivedcollectionsv2) | **GET** /api/v2/users/{userId}/collections/status/archived | UserCollectionController@indexArchived |
| [**FetchUserCollectionV2**](CollectionsApi.md#fetchusercollectionv2) | **GET** /api/v2/users/{userId}/collections/{id} | CollectionController@show |
| [**FetchUserCollectionsV2**](CollectionsApi.md#fetchusercollectionsv2) | **GET** /api/v2/users/{userId}/collections/status/active | UserCollectionController@indexActive |
| [**FetchUserDraftCollectionsV2**](CollectionsApi.md#fetchuserdraftcollectionsv2) | **GET** /api/v2/users/{userId}/collections/status/draft | UserCollectionController@indexDraft |
| [**UpdateCollectionsV2**](CollectionsApi.md#updatecollectionsv2) | **PUT** /api/v2/collections/{id} | Update a collection |
| [**UpdateTeamCollections**](CollectionsApi.md#updateteamcollections) | **PUT** /api/v1/teams/{teamId}/collections/{id} | Update a collection |
| [**UpdateTeamCollectionsV2**](CollectionsApi.md#updateteamcollectionsv2) | **PUT** /api/v2/teams/{teamId}/collections/{id} | Update a collection |
| [**UpdateUserCollectionsV2**](CollectionsApi.md#updateusercollectionsv2) | **PUT** /api/v2/users/{userId}/collections/{id} | Update a collection |

<a id="countteamuniquefieldscollectionv2"></a>
# **CountTeamUniqueFieldsCollectionV2**
> CountUniqueFieldsCollections200Response CountTeamUniqueFieldsCollectionV2 (int teamId, string field)

TeamCollectionController@count

Get user counts for distinct entries of a field in the model


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

<a id="countuseruniquefieldscollectionv2"></a>
# **CountUserUniqueFieldsCollectionV2**
> CountUniqueFieldsCollections200Response CountUserUniqueFieldsCollectionV2 (int userId, string field)

UserCollectionController@count

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

<a id="createcollections"></a>
# **CreateCollections**
> CreateCategories200Response CreateCollections (CreateCollectionsRequest createCollectionsRequest)

CollectionController@store

Create a new collection owned by an individual


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createCollectionsRequest** | [**CreateCollectionsRequest**](CreateCollectionsRequest.md) | Pass user credentials |  |

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

<a id="createteamcollections"></a>
# **CreateTeamCollections**
> CreateCategories200Response CreateTeamCollections (int teamId, CreateTeamCollectionsRequest createTeamCollectionsRequest)

CollectionController@store

Create a new collection for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **createTeamCollectionsRequest** | [**CreateTeamCollectionsRequest**](CreateTeamCollectionsRequest.md) | Pass user credentials |  |

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

<a id="createteamcollectionsv2"></a>
# **CreateTeamCollectionsV2**
> CreateCategories200Response CreateTeamCollectionsV2 (int teamId, CreateTeamCollectionsRequest createTeamCollectionsRequest)

TeamCollectionController@store

Create a new collection for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **createTeamCollectionsRequest** | [**CreateTeamCollectionsRequest**](CreateTeamCollectionsRequest.md) | Pass user credentials |  |

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

<a id="createusercollections"></a>
# **CreateUserCollections**
> CreateCategories200Response CreateUserCollections (CreateCollectionsRequest createCollectionsRequest)

UserCollectionController@store

Create a new collection owned by an individual


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createCollectionsRequest** | [**CreateCollectionsRequest**](CreateCollectionsRequest.md) | Pass user credentials |  |

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

<a id="deletecollectionsv2"></a>
# **DeleteCollectionsV2**
> DeleteAliases200Response DeleteCollectionsV2 (int id)

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

<a id="deleteteamcollections"></a>
# **DeleteTeamCollections**
> DeleteAliases200Response DeleteTeamCollections (int teamId, int id)

Delete a collection

Delete a collection owned by a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="deleteteamcollectionsv2"></a>
# **DeleteTeamCollectionsV2**
> DeleteAliases200Response DeleteTeamCollectionsV2 (int teamId, int id)

Delete a collection

Delete a collection owned by a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="deleteusercollectionsv2"></a>
# **DeleteUserCollectionsV2**
> DeleteAliases200Response DeleteUserCollectionsV2 (int userId, int id)

Delete a collection

Delete a collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
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

<a id="editteamcollections"></a>
# **EditTeamCollections**
> FetchCollections200Response EditTeamCollections (int teamId, int id, EditTeamCollectionsRequest editTeamCollectionsRequest, string unarchive = null)

Edit a collection

Edit a collection owned by a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | collection id |  |
| **editTeamCollectionsRequest** | [**EditTeamCollectionsRequest**](EditTeamCollectionsRequest.md) | Pass user credentials |  |
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

<a id="editteamcollectionsv2"></a>
# **EditTeamCollectionsV2**
> FetchCollections200Response EditTeamCollectionsV2 (int teamId, int id, EditTeamCollectionsRequest editTeamCollectionsRequest)

Edit a collection

Edit a collection owned by a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | collection id |  |
| **editTeamCollectionsRequest** | [**EditTeamCollectionsRequest**](EditTeamCollectionsRequest.md) | Pass user credentials |  |

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

<a id="editusercollectionsv2"></a>
# **EditUserCollectionsV2**
> FetchCollections200Response EditUserCollectionsV2 (int userId, int id, EditCollectionsV2Request editCollectionsV2Request)

Edit a collection

Edit a collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
| **id** | **int** | collection id |  |
| **editCollectionsV2Request** | [**EditCollectionsV2Request**](EditCollectionsV2Request.md) | Pass user credentials |  |

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

<a id="fetchteamactivecollectionsv2"></a>
# **FetchTeamActiveCollectionsV2**
> FetchAllCollections200Response FetchTeamActiveCollectionsV2 (int teamId)

TeamCollectionController@indexActive

Returns a list of a teams collections


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |

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

<a id="fetchteamarchivedcollectionsv2"></a>
# **FetchTeamArchivedCollectionsV2**
> FetchAllCollections200Response FetchTeamArchivedCollectionsV2 (int teamId)

TeamCollectionController@indexArchived

Returns a list of a teams archived collections


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |

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

<a id="fetchteamcollectionv2"></a>
# **FetchTeamCollectionV2**
> FetchCollections200Response FetchTeamCollectionV2 (int teamId, int id)

TeamCollectionController@show

Get collection by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="fetchteamdraftcollectionsv2"></a>
# **FetchTeamDraftCollectionsV2**
> FetchAllCollections200Response FetchTeamDraftCollectionsV2 (int teamId)

TeamCollectionController@indexDraft

Returns a list of a teams draft collections


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |

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

<a id="fetchuserarchivedcollectionsv2"></a>
# **FetchUserArchivedCollectionsV2**
> FetchAllCollections200Response FetchUserArchivedCollectionsV2 (int userId)

UserCollectionController@indexArchived

Returns a list of a users archived collections


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |

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

<a id="fetchusercollectionv2"></a>
# **FetchUserCollectionV2**
> FetchCollections200Response FetchUserCollectionV2 (int userId, int id)

CollectionController@show

Get collection by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
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

<a id="fetchusercollectionsv2"></a>
# **FetchUserCollectionsV2**
> FetchAllCollections200Response FetchUserCollectionsV2 (int userId)

UserCollectionController@indexActive

Returns a list of a users collections


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |

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

<a id="fetchuserdraftcollectionsv2"></a>
# **FetchUserDraftCollectionsV2**
> FetchAllCollections200Response FetchUserDraftCollectionsV2 (int userId)

UserCollectionController@indexDraft

Returns a list of a users draft collections


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |

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

<a id="updateteamcollections"></a>
# **UpdateTeamCollections**
> FetchCollections200Response UpdateTeamCollections (int teamId, int id, UpdateTeamCollectionsRequest updateTeamCollectionsRequest)

Update a collection

Update a collection owned by a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="updateteamcollectionsv2"></a>
# **UpdateTeamCollectionsV2**
> FetchCollections200Response UpdateTeamCollectionsV2 (int teamId, int id, UpdateTeamCollectionsRequest updateTeamCollectionsRequest)

Update a collection

Update a collection owned by a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="updateusercollectionsv2"></a>
# **UpdateUserCollectionsV2**
> FetchCollections200Response UpdateUserCollectionsV2 (int userId, int id, UpdateCollectionsV2Request updateCollectionsV2Request)

Update a collection

Update a collection owned by an individual


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
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

