# GatewayApiSdk.Api.LibraryApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateLibraries**](LibraryApi.md#createlibraries) | **POST** /api/v1/libraries | Library@store |
| [**DeleteLibraries**](LibraryApi.md#deletelibraries) | **DELETE** /api/v1/libraries/{id} | Library@destroy |
| [**EditLibraries**](LibraryApi.md#editlibraries) | **PATCH** /api/v1/libraries/{id} | Library@update |
| [**FetchLibraries**](LibraryApi.md#fetchlibraries) | **GET** /api/v1/libraries/{id} | Return a single library |
| [**ListLibraries**](LibraryApi.md#listlibraries) | **GET** /api/v1/libraries | Retrieve a list of libraries |
| [**UpdateLibraries**](LibraryApi.md#updatelibraries) | **PUT** /api/v1/libraries/{id} | Library@update |

<a id="createlibraries"></a>
# **CreateLibraries**
> CreateCategories200Response CreateLibraries (CreateLibrariesRequest createLibrariesRequest)

Library@store

Creates a new library


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createLibrariesRequest** | [**CreateLibrariesRequest**](CreateLibrariesRequest.md) | library definition |  |

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
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletelibraries"></a>
# **DeleteLibraries**
> DeleteAliases200Response DeleteLibraries (int id)

Library@destroy

Delete a library


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | library id |  |

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

<a id="editlibraries"></a>
# **EditLibraries**
> UpdateLibraries200Response EditLibraries (int id, CreateLibrariesRequest createLibrariesRequest)

Library@update

Edit a library


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | library id |  |
| **createLibrariesRequest** | [**CreateLibrariesRequest**](CreateLibrariesRequest.md) | library definition |  |

### Return type

[**UpdateLibraries200Response**](UpdateLibraries200Response.md)

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

<a id="fetchlibraries"></a>
# **FetchLibraries**
> FetchLibraries200Response FetchLibraries (int id)

Return a single library

Return a single library


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | library id |  |

### Return type

[**FetchLibraries200Response**](FetchLibraries200Response.md)

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

<a id="listlibraries"></a>
# **ListLibraries**
> ListLibraries200Response ListLibraries (int perPage = null)

Retrieve a list of libraries

Returns a paginated list of libraries along with associated datasets and teams.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | Specify the number of libraries per page | [optional] [default to 10] |

### Return type

[**ListLibraries200Response**](ListLibraries200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updatelibraries"></a>
# **UpdateLibraries**
> UpdateLibraries200Response UpdateLibraries (int id, CreateLibrariesRequest createLibrariesRequest)

Library@update

Update a library


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | library id |  |
| **createLibrariesRequest** | [**CreateLibrariesRequest**](CreateLibrariesRequest.md) | library definition |  |

### Return type

[**UpdateLibraries200Response**](UpdateLibraries200Response.md)

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

