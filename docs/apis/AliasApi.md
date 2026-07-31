# GatewayApiSdk.Api.AliasApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateAliases**](AliasApi.md#createaliases) | **POST** /api/v1/aliases | AliasController@store |
| [**DeleteAliases**](AliasApi.md#deletealiases) | **DELETE** /api/v1/aliases/{id} | AliasController@destroy |
| [**EditAliases**](AliasApi.md#editaliases) | **PATCH** /api/v1/aliases/{id} | AliasController@edit |
| [**FetchAliases**](AliasApi.md#fetchaliases) | **GET** /api/v1/aliases/{id} | Return a single alias |
| [**FetchAllAliases**](AliasApi.md#fetchallaliases) | **GET** /api/v1/aliases | List of aliases |
| [**UpdateAliases**](AliasApi.md#updatealiases) | **PUT** /api/v1/aliases/{id} | AliasController@update |

<a id="createaliases"></a>
# **CreateAliases**
> CreateAliases200Response CreateAliases (CreateAliasesRequest createAliasesRequest)

AliasController@store

Creates a new alias


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createAliasesRequest** | [**CreateAliasesRequest**](CreateAliasesRequest.md) | Alias definition |  |

### Return type

[**CreateAliases200Response**](CreateAliases200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletealiases"></a>
# **DeleteAliases**
> DeleteAliases200Response DeleteAliases (int id)

AliasController@destroy

Delete an alias


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | alias id |  |

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

<a id="editaliases"></a>
# **EditAliases**
> UpdateAliases200Response EditAliases (int id, EditAliasesRequest editAliasesRequest)

AliasController@edit

Edit a alias


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | alias id |  |
| **editAliasesRequest** | [**EditAliasesRequest**](EditAliasesRequest.md) | Alias definition |  |

### Return type

[**UpdateAliases200Response**](UpdateAliases200Response.md)

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

<a id="fetchaliases"></a>
# **FetchAliases**
> FetchAliases200Response FetchAliases (int id)

Return a single alias

Return a single alias


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | alias id |  |

### Return type

[**FetchAliases200Response**](FetchAliases200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchallaliases"></a>
# **FetchAllAliases**
> FetchAllAliases200Response FetchAllAliases ()

List of aliases

Returns a list of aliases


### Parameters
This endpoint does not need any parameter.
### Return type

[**FetchAllAliases200Response**](FetchAllAliases200Response.md)

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

<a id="updatealiases"></a>
# **UpdateAliases**
> UpdateAliases200Response UpdateAliases (int id, CreateAliasesRequest createAliasesRequest)

AliasController@update

Update a alias


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | alias id |  |
| **createAliasesRequest** | [**CreateAliasesRequest**](CreateAliasesRequest.md) | Alias definition |  |

### Return type

[**UpdateAliases200Response**](UpdateAliases200Response.md)

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

