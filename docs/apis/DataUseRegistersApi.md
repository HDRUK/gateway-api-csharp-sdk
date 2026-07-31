# GatewayApiSdk.Api.DataUseRegistersApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call220a00f946309dea9f126baed550c9cd**](DataUseRegistersApi.md#call220a00f946309dea9f126baed550c9cd) | **GET** /api/v2/dur/template | DurController@exportTemplate |
| [**Call2c16b33b0f6636db91657b64f4a7bbda**](DataUseRegistersApi.md#call2c16b33b0f6636db91657b64f4a7bbda) | **PUT** /api/v1/dur/{id} | Update a dur by id |
| [**Call3d9acaab46169ca5e55cf017e9659f8e**](DataUseRegistersApi.md#call3d9acaab46169ca5e55cf017e9659f8e) | **PATCH** /api/v1/dur/{id} | Edit a dur |
| [**Call491cd8b54449d3269b5d69d4d5732523**](DataUseRegistersApi.md#call491cd8b54449d3269b5d69d4d5732523) | **GET** /api/v1/dur/template | DurController@exportTemplate |
| [**CountTeamUniqueFieldsDurV2**](DataUseRegistersApi.md#countteamuniquefieldsdurv2) | **GET** /api/v2/teams/{teamId}/dur/count/{field} | TeamDurController@count |
| [**CreateDur**](DataUseRegistersApi.md#createdur) | **POST** /api/v1/dur | DurController@store |
| [**CreateDurByTeamV2**](DataUseRegistersApi.md#createdurbyteamv2) | **POST** /api/v2/teams/{teamId}/dur | TeamDurController@store |
| [**DeleteDursV2ByTeamId**](DataUseRegistersApi.md#deletedursv2byteamid) | **DELETE** /api/v2/teams/{teamId}/dur/{id} | TeamDurController@destroy |
| [**E78bbbfec43b70397fd580225bb968ce**](DataUseRegistersApi.md#e78bbbfec43b70397fd580225bb968ce) | **DELETE** /api/v1/dur/{id} | Delete a dur |
| [**EditDursV2ByTeamId**](DataUseRegistersApi.md#editdursv2byteamid) | **PATCH** /api/v2/teams/{teamId}/dur/{id} | TeamDurController@edit |
| [**ExportDurV2**](DataUseRegistersApi.md#exportdurv2) | **GET** /api/v2/dur/export | DurController@export |
| [**FetchAllDur**](DataUseRegistersApi.md#fetchalldur) | **GET** /api/v1/dur | DurController@index |
| [**FetchAllDurV2**](DataUseRegistersApi.md#fetchalldurv2) | **GET** /api/v2/dur | DurController@indexActive |
| [**FetchAllTeamDurStatus**](DataUseRegistersApi.md#fetchallteamdurstatus) | **GET** /api/v2/teams/{teamId}/dur/status/{status} | TeamDurController@indexStatus |
| [**FetchDurById**](DataUseRegistersApi.md#fetchdurbyid) | **GET** /api/v1/dur/{id} | DurController@show |
| [**FetchDurByIdV2**](DataUseRegistersApi.md#fetchdurbyidv2) | **GET** /api/v2/dur/{id} | DurController@showActive |
| [**FetchDurByTeamAndByIdV2**](DataUseRegistersApi.md#fetchdurbyteamandbyidv2) | **GET** /api/v1/teams/{teamId}/dur/{id} | TeamDurController@show |
| [**UpdateDurV2ByTeamId**](DataUseRegistersApi.md#updatedurv2byteamid) | **PUT** /api/v2/teams/{teamId}/dur/{id} | TeamDurController@update |
| [**UploadDur**](DataUseRegistersApi.md#uploaddur) | **POST** /api/v1/dur/upload | DurController@upload |

<a id="call220a00f946309dea9f126baed550c9cd"></a>
# **Call220a00f946309dea9f126baed550c9cd**
> Object Call220a00f946309dea9f126baed550c9cd ()

DurController@exportTemplate

Export Dur upload template


### Parameters
This endpoint does not need any parameter.
### Return type

**Object**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/csv, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | File download |  -  |
| **401** | Unauthorized |  -  |
| **404** | File Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call2c16b33b0f6636db91657b64f4a7bbda"></a>
# **Call2c16b33b0f6636db91657b64f4a7bbda**
> Model2c16b33b0f6636db91657b64f4a7bbda200Response Call2c16b33b0f6636db91657b64f4a7bbda (int id, CreateDurRequest createDurRequest)

Update a dur by id

Update a dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dur id |  |
| **createDurRequest** | [**CreateDurRequest**](CreateDurRequest.md) | Pass user credentials |  |

### Return type

[**Model2c16b33b0f6636db91657b64f4a7bbda200Response**](Model2c16b33b0f6636db91657b64f4a7bbda200Response.md)

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

<a id="call3d9acaab46169ca5e55cf017e9659f8e"></a>
# **Call3d9acaab46169ca5e55cf017e9659f8e**
> Model2c16b33b0f6636db91657b64f4a7bbda200Response Call3d9acaab46169ca5e55cf017e9659f8e (int id, CreateDurRequest createDurRequest, string unarchive = null)

Edit a dur

Edit a dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dur id |  |
| **createDurRequest** | [**CreateDurRequest**](CreateDurRequest.md) | Pass user credentials |  |
| **unarchive** | **string** | Unarchive a dur | [optional]  |

### Return type

[**Model2c16b33b0f6636db91657b64f4a7bbda200Response**](Model2c16b33b0f6636db91657b64f4a7bbda200Response.md)

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

<a id="call491cd8b54449d3269b5d69d4d5732523"></a>
# **Call491cd8b54449d3269b5d69d4d5732523**
> Object Call491cd8b54449d3269b5d69d4d5732523 ()

DurController@exportTemplate

Export Dur upload template


### Parameters
This endpoint does not need any parameter.
### Return type

**Object**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/csv, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | File download |  -  |
| **401** | Unauthorized |  -  |
| **404** | File Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="countteamuniquefieldsdurv2"></a>
# **CountTeamUniqueFieldsDurV2**
> CountUniqueFieldsCollections200Response CountTeamUniqueFieldsDurV2 (int teamId, string field)

TeamDurController@count

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

<a id="createdur"></a>
# **CreateDur**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateDur (CreateDurRequest createDurRequest)

DurController@store

Create a new dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createDurRequest** | [**CreateDurRequest**](CreateDurRequest.md) | Pass user credentials |  |

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

<a id="createdurbyteamv2"></a>
# **CreateDurByTeamV2**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateDurByTeamV2 (int teamId, CreateDurRequest createDurRequest)

TeamDurController@store

Create a new dur by team v2


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **createDurRequest** | [**CreateDurRequest**](CreateDurRequest.md) | Pass user credentials |  |

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

<a id="deletedursv2byteamid"></a>
# **DeleteDursV2ByTeamId**
> C29b5b3424f7317b69b4bda048ccfafb200Response DeleteDursV2ByTeamId (int teamId, int id)

TeamDurController@destroy

Delete a dur by team and id v2


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="e78bbbfec43b70397fd580225bb968ce"></a>
# **E78bbbfec43b70397fd580225bb968ce**
> C29b5b3424f7317b69b4bda048ccfafb200Response E78bbbfec43b70397fd580225bb968ce (int id)

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

<a id="editdursv2byteamid"></a>
# **EditDursV2ByTeamId**
> Model2c16b33b0f6636db91657b64f4a7bbda200Response EditDursV2ByTeamId (int teamId, int id, CreateDurRequest createDurRequest)

TeamDurController@edit

Edit a dur by team v2


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | dur id |  |
| **createDurRequest** | [**CreateDurRequest**](CreateDurRequest.md) | Pass user credentials |  |

### Return type

[**Model2c16b33b0f6636db91657b64f4a7bbda200Response**](Model2c16b33b0f6636db91657b64f4a7bbda200Response.md)

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

<a id="exportdurv2"></a>
# **ExportDurV2**
> string ExportDurV2 (int id = null)

DurController@export

Export CSV of one or more DURs


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dur id | [optional]  |

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/csv, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | CSV file |  -  |
| **401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchalldur"></a>
# **FetchAllDur**
> FetchAllDur200Response FetchAllDur (ProjectTitleAscupdatedAtAsc sort = null, string projectTitle = null, int perPage = null)

DurController@index

Returns a list of dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **sort** | [**ProjectTitleAscupdatedAtAsc**](ProjectTitleAscupdatedAtAsc.md) | Sort fields in the format field:direction, e.g., project_title:asc,updated_at:asc | [optional]  |
| **projectTitle** | **string** | Filter tools by project title | [optional]  |
| **perPage** | **int** | per page | [optional]  |

### Return type

[**FetchAllDur200Response**](FetchAllDur200Response.md)

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

<a id="fetchalldurv2"></a>
# **FetchAllDurV2**
> FetchAllDurV2200Response FetchAllDurV2 (ProjectTitleAscupdatedAtAsc sort = null, string projectTitle = null, int perPage = null, bool withRelated = null)

DurController@indexActive

Returns a list of active dur


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **sort** | [**ProjectTitleAscupdatedAtAsc**](ProjectTitleAscupdatedAtAsc.md) | Sort fields in the format field:direction, e.g., project_title:asc,updated_at:asc | [optional]  |
| **projectTitle** | **string** | Filter tools by project title | [optional]  |
| **perPage** | **int** | per page | [optional]  |
| **withRelated** | **bool** | Show related entities | [optional]  |

### Return type

[**FetchAllDurV2200Response**](FetchAllDurV2200Response.md)

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

<a id="fetchallteamdurstatus"></a>
# **FetchAllTeamDurStatus**
> FetchAllDur200Response FetchAllTeamDurStatus (int teamId, string status, ProjectTitleAscupdatedAtAsc sort = null, string projectTitle = null, int perPage = null, bool withRelated = null)

TeamDurController@indexStatus

Returns a list of dur owned by this team with given status


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **status** | **string** | Status of the DUR (active, draft, or archived). Defaults to active if not provided. | [default to active] |
| **sort** | [**ProjectTitleAscupdatedAtAsc**](ProjectTitleAscupdatedAtAsc.md) | Sort fields in the format field:direction, e.g., project_title:asc,updated_at:asc | [optional]  |
| **projectTitle** | **string** | Filter dur by project title | [optional]  |
| **perPage** | **int** | per page | [optional]  |
| **withRelated** | **bool** | Show related entities | [optional]  |

### Return type

[**FetchAllDur200Response**](FetchAllDur200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdurbyid"></a>
# **FetchDurById**
> FetchDurById200Response FetchDurById (int id)

DurController@show

Get dur by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | data use register id |  |

### Return type

[**FetchDurById200Response**](FetchDurById200Response.md)

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

<a id="fetchdurbyidv2"></a>
# **FetchDurByIdV2**
> Model2c16b33b0f6636db91657b64f4a7bbda200Response FetchDurByIdV2 (int id)

DurController@showActive

Get dur by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | data use register id |  |

### Return type

[**Model2c16b33b0f6636db91657b64f4a7bbda200Response**](Model2c16b33b0f6636db91657b64f4a7bbda200Response.md)

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

<a id="fetchdurbyteamandbyidv2"></a>
# **FetchDurByTeamAndByIdV2**
> Model2c16b33b0f6636db91657b64f4a7bbda200Response FetchDurByTeamAndByIdV2 (int teamId, int id)

TeamDurController@show

Get dur by team id and by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | data use register id |  |

### Return type

[**Model2c16b33b0f6636db91657b64f4a7bbda200Response**](Model2c16b33b0f6636db91657b64f4a7bbda200Response.md)

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

<a id="updatedurv2byteamid"></a>
# **UpdateDurV2ByTeamId**
> Model2c16b33b0f6636db91657b64f4a7bbda200Response UpdateDurV2ByTeamId (int teamId, int id, CreateDurRequest createDurRequest)

TeamDurController@update

Update a dur by team and id v2


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | dur id |  |
| **createDurRequest** | [**CreateDurRequest**](CreateDurRequest.md) | Pass user credentials |  |

### Return type

[**Model2c16b33b0f6636db91657b64f4a7bbda200Response**](Model2c16b33b0f6636db91657b64f4a7bbda200Response.md)

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

<a id="uploaddur"></a>
# **UploadDur**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response UploadDur (UploadDurRequest uploadDurRequest)

DurController@upload

Create a new dur with upload data


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **uploadDurRequest** | [**UploadDurRequest**](UploadDurRequest.md) | Pass user credentials |  |

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

