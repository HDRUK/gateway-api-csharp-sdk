# GatewayApiSdk.Api.CollectionsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**A18eed83ffe8ac895df3e1efa5ffb421**](CollectionsApi.md#a18eed83ffe8ac895df3e1efa5ffb421) | **PUT** /api/v1/teams/{teamId}/collections/{id} | Update a collection |
| [**B2e32406fe513dd0c0747a0864b5ed28**](CollectionsApi.md#b2e32406fe513dd0c0747a0864b5ed28) | **DELETE** /api/v2/collections/{id} | Delete a collection |
| [**Call22bf9932e93726b8338c13e489c7d96e**](CollectionsApi.md#call22bf9932e93726b8338c13e489c7d96e) | **PUT** /api/v2/users/{userId}/collections/{id} | Update a collection |
| [**Call2e589ea17282e3818437328b1a6d2c45**](CollectionsApi.md#call2e589ea17282e3818437328b1a6d2c45) | **PATCH** /api/v2/teams/{teamId}/collections/{id} | Edit a collection |
| [**Call63175dd3a255646e0428a630af683e21**](CollectionsApi.md#call63175dd3a255646e0428a630af683e21) | **PATCH** /api/v2/users/{userId}/collections/{id} | Edit a collection |
| [**Call6907582348e596c660cc65263dc3a4fc**](CollectionsApi.md#call6907582348e596c660cc65263dc3a4fc) | **DELETE** /api/v1/teams/{teamId}/collections/{id} | Delete a collection |
| [**Call75c378b5764d9d73e14fe2d65c654910**](CollectionsApi.md#call75c378b5764d9d73e14fe2d65c654910) | **PATCH** /api/v1/teams/{teamId}/collections/{id} | Edit a collection |
| [**Call78c554f5fb0f01c8d788a5789fd0c35b**](CollectionsApi.md#call78c554f5fb0f01c8d788a5789fd0c35b) | **DELETE** /api/v2/users/{userId}/collections/{id} | Delete a collection |
| [**Call8abb5928cecc676521f3e3d8eea0c49c**](CollectionsApi.md#call8abb5928cecc676521f3e3d8eea0c49c) | **PUT** /api/v2/collections/{id} | Update a collection |
| [**Call94ae4ab159160f6240a4bc00d2e6fe5f**](CollectionsApi.md#call94ae4ab159160f6240a4bc00d2e6fe5f) | **PUT** /api/v2/teams/{teamId}/collections/{id} | Update a collection |
| [**Call9c525a2aaf8e8a81cbcdf1a3033bb1bb**](CollectionsApi.md#call9c525a2aaf8e8a81cbcdf1a3033bb1bb) | **DELETE** /api/v2/teams/{teamId}/collections/{id} | Delete a collection |
| [**CountTeamUniqueFieldsCollectionV2**](CollectionsApi.md#countteamuniquefieldscollectionv2) | **GET** /api/v2/teams/{teamId}/collections/count/{field} | TeamCollectionController@count |
| [**CountUniqueFieldsCollections**](CollectionsApi.md#countuniquefieldscollections) | **GET** /api/v1/collections/count/{field} | CollectionController@count |
| [**CountUniqueFieldsCollectionsV2**](CollectionsApi.md#countuniquefieldscollectionsv2) | **GET** /api/v2/collections/count/{field} | CollectionController@count |
| [**CountUserUniqueFieldsCollectionV2**](CollectionsApi.md#countuseruniquefieldscollectionv2) | **GET** /api/v2/users/{userId}/collections/count/{field} | UserCollectionController@count |
| [**CreateCollections**](CollectionsApi.md#createcollections) | **POST** /api/v2/collections | CollectionController@store |
| [**CreateTeamCollections**](CollectionsApi.md#createteamcollections) | **POST** /api/v1/teams/{teamId}/collections | CollectionController@store |
| [**CreateTeamCollectionsV2**](CollectionsApi.md#createteamcollectionsv2) | **POST** /api/v2/teams/{teamId}/collections | TeamCollectionController@store |
| [**CreateUserCollections**](CollectionsApi.md#createusercollections) | **POST** /api/v2/users/collections | UserCollectionController@store |
| [**D183a285f65bdc0e6341ed79b3a63670**](CollectionsApi.md#d183a285f65bdc0e6341ed79b3a63670) | **PATCH** /api/v2/collections/{id} | Edit a collection |
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

<a id="a18eed83ffe8ac895df3e1efa5ffb421"></a>
# **A18eed83ffe8ac895df3e1efa5ffb421**
> FetchCollections200Response A18eed83ffe8ac895df3e1efa5ffb421 (int teamId, int id, A18eed83ffe8ac895df3e1efa5ffb421Request a18eed83ffe8ac895df3e1efa5ffb421Request)

Update a collection

Update a collection owned by a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="b2e32406fe513dd0c0747a0864b5ed28"></a>
# **B2e32406fe513dd0c0747a0864b5ed28**
> C29b5b3424f7317b69b4bda048ccfafb200Response B2e32406fe513dd0c0747a0864b5ed28 (int id)

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

<a id="call22bf9932e93726b8338c13e489c7d96e"></a>
# **Call22bf9932e93726b8338c13e489c7d96e**
> FetchCollections200Response Call22bf9932e93726b8338c13e489c7d96e (int userId, int id, Model8abb5928cecc676521f3e3d8eea0c49cRequest model8abb5928cecc676521f3e3d8eea0c49cRequest)

Update a collection

Update a collection owned by an individual


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
| **id** | **int** | collection id |  |
| **model8abb5928cecc676521f3e3d8eea0c49cRequest** | [**Model8abb5928cecc676521f3e3d8eea0c49cRequest**](Model8abb5928cecc676521f3e3d8eea0c49cRequest.md) | Pass user credentials |  |

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

<a id="call2e589ea17282e3818437328b1a6d2c45"></a>
# **Call2e589ea17282e3818437328b1a6d2c45**
> FetchCollections200Response Call2e589ea17282e3818437328b1a6d2c45 (int teamId, int id, Model75c378b5764d9d73e14fe2d65c654910Request model75c378b5764d9d73e14fe2d65c654910Request)

Edit a collection

Edit a collection owned by a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | collection id |  |
| **model75c378b5764d9d73e14fe2d65c654910Request** | [**Model75c378b5764d9d73e14fe2d65c654910Request**](Model75c378b5764d9d73e14fe2d65c654910Request.md) | Pass user credentials |  |

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

<a id="call63175dd3a255646e0428a630af683e21"></a>
# **Call63175dd3a255646e0428a630af683e21**
> FetchCollections200Response Call63175dd3a255646e0428a630af683e21 (int userId, int id, D183a285f65bdc0e6341ed79b3a63670Request d183a285f65bdc0e6341ed79b3a63670Request)

Edit a collection

Edit a collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
| **id** | **int** | collection id |  |
| **d183a285f65bdc0e6341ed79b3a63670Request** | [**D183a285f65bdc0e6341ed79b3a63670Request**](D183a285f65bdc0e6341ed79b3a63670Request.md) | Pass user credentials |  |

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

<a id="call6907582348e596c660cc65263dc3a4fc"></a>
# **Call6907582348e596c660cc65263dc3a4fc**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call6907582348e596c660cc65263dc3a4fc (int teamId, int id)

Delete a collection

Delete a collection owned by a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="call75c378b5764d9d73e14fe2d65c654910"></a>
# **Call75c378b5764d9d73e14fe2d65c654910**
> FetchCollections200Response Call75c378b5764d9d73e14fe2d65c654910 (int teamId, int id, Model75c378b5764d9d73e14fe2d65c654910Request model75c378b5764d9d73e14fe2d65c654910Request, string unarchive = null)

Edit a collection

Edit a collection owned by a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | collection id |  |
| **model75c378b5764d9d73e14fe2d65c654910Request** | [**Model75c378b5764d9d73e14fe2d65c654910Request**](Model75c378b5764d9d73e14fe2d65c654910Request.md) | Pass user credentials |  |
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

<a id="call78c554f5fb0f01c8d788a5789fd0c35b"></a>
# **Call78c554f5fb0f01c8d788a5789fd0c35b**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call78c554f5fb0f01c8d788a5789fd0c35b (int userId, int id)

Delete a collection

Delete a collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
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

<a id="call8abb5928cecc676521f3e3d8eea0c49c"></a>
# **Call8abb5928cecc676521f3e3d8eea0c49c**
> FetchCollections200Response Call8abb5928cecc676521f3e3d8eea0c49c (int id, Model8abb5928cecc676521f3e3d8eea0c49cRequest model8abb5928cecc676521f3e3d8eea0c49cRequest)

Update a collection

Update a collection owned by an individual


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |
| **model8abb5928cecc676521f3e3d8eea0c49cRequest** | [**Model8abb5928cecc676521f3e3d8eea0c49cRequest**](Model8abb5928cecc676521f3e3d8eea0c49cRequest.md) | Pass user credentials |  |

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

<a id="call94ae4ab159160f6240a4bc00d2e6fe5f"></a>
# **Call94ae4ab159160f6240a4bc00d2e6fe5f**
> FetchCollections200Response Call94ae4ab159160f6240a4bc00d2e6fe5f (int teamId, int id, A18eed83ffe8ac895df3e1efa5ffb421Request a18eed83ffe8ac895df3e1efa5ffb421Request)

Update a collection

Update a collection owned by a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="call9c525a2aaf8e8a81cbcdf1a3033bb1bb"></a>
# **Call9c525a2aaf8e8a81cbcdf1a3033bb1bb**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call9c525a2aaf8e8a81cbcdf1a3033bb1bb (int teamId, int id)

Delete a collection

Delete a collection owned by a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateCollections (CreateCollectionsRequest createCollectionsRequest)

CollectionController@store

Create a new collection owned by an individual


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createCollectionsRequest** | [**CreateCollectionsRequest**](CreateCollectionsRequest.md) | Pass user credentials |  |

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

<a id="createteamcollections"></a>
# **CreateTeamCollections**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateTeamCollections (int teamId, CreateTeamCollectionsRequest createTeamCollectionsRequest)

CollectionController@store

Create a new collection for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **createTeamCollectionsRequest** | [**CreateTeamCollectionsRequest**](CreateTeamCollectionsRequest.md) | Pass user credentials |  |

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

<a id="createteamcollectionsv2"></a>
# **CreateTeamCollectionsV2**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateTeamCollectionsV2 (int teamId, CreateTeamCollectionsRequest createTeamCollectionsRequest)

TeamCollectionController@store

Create a new collection for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **createTeamCollectionsRequest** | [**CreateTeamCollectionsRequest**](CreateTeamCollectionsRequest.md) | Pass user credentials |  |

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

<a id="createusercollections"></a>
# **CreateUserCollections**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateUserCollections (CreateCollectionsRequest createCollectionsRequest)

UserCollectionController@store

Create a new collection owned by an individual


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createCollectionsRequest** | [**CreateCollectionsRequest**](CreateCollectionsRequest.md) | Pass user credentials |  |

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

<a id="d183a285f65bdc0e6341ed79b3a63670"></a>
# **D183a285f65bdc0e6341ed79b3a63670**
> FetchCollections200Response D183a285f65bdc0e6341ed79b3a63670 (int id, D183a285f65bdc0e6341ed79b3a63670Request d183a285f65bdc0e6341ed79b3a63670Request, string unarchive = null)

Edit a collection

Edit a collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | collection id |  |
| **d183a285f65bdc0e6341ed79b3a63670Request** | [**D183a285f65bdc0e6341ed79b3a63670Request**](D183a285f65bdc0e6341ed79b3a63670Request.md) | Pass user credentials |  |
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

