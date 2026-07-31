# GatewayApiSdk.Api.SavedSearchApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateSavedSearches**](SavedSearchApi.md#createsavedsearches) | **POST** /api/v1/saved_searches | SavedSearch@store |
| [**DeleteSavedSearches**](SavedSearchApi.md#deletesavedsearches) | **DELETE** /api/v1/saved_searches/{id} | SavedSearch@destroy |
| [**EditSavedSearches**](SavedSearchApi.md#editsavedsearches) | **PATCH** /api/v1/saved_searches/{id} | SavedSearch@update |
| [**FetchAllSavedSearches**](SavedSearchApi.md#fetchallsavedsearches) | **GET** /api/v1/saved_searches | SavedSearch@index |
| [**FetchSavedSearches**](SavedSearchApi.md#fetchsavedsearches) | **GET** /api/v1/saved_searches/{id} | SavedSearch@show |
| [**UpdateSavedSearches**](SavedSearchApi.md#updatesavedsearches) | **PUT** /api/v1/saved_searches/{id} | SavedSearch@update |

<a id="createsavedsearches"></a>
# **CreateSavedSearches**
> CreateCategories200Response CreateSavedSearches (CreateSavedSearchesRequest createSavedSearchesRequest)

SavedSearch@store

Creates a new saved search


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createSavedSearchesRequest** | [**CreateSavedSearchesRequest**](CreateSavedSearchesRequest.md) | Saved search definition |  |

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

<a id="deletesavedsearches"></a>
# **DeleteSavedSearches**
> DeleteAliases200Response DeleteSavedSearches (int id)

SavedSearch@destroy

Delete a saved search


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | saved search id |  |

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

<a id="editsavedsearches"></a>
# **EditSavedSearches**
> UpdateSavedSearches200Response EditSavedSearches (int id, EditSavedSearchesRequest editSavedSearchesRequest)

SavedSearch@update

Edit a saved search


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | saved search id |  |
| **editSavedSearchesRequest** | [**EditSavedSearchesRequest**](EditSavedSearchesRequest.md) | Saved search definition |  |

### Return type

[**UpdateSavedSearches200Response**](UpdateSavedSearches200Response.md)

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

<a id="fetchallsavedsearches"></a>
# **FetchAllSavedSearches**
> FetchAllSavedSearches200Response FetchAllSavedSearches (int perPage = null)

SavedSearch@index

Returns a list of saved searches enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | Specify number of results per page | [optional]  |

### Return type

[**FetchAllSavedSearches200Response**](FetchAllSavedSearches200Response.md)

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

<a id="fetchsavedsearches"></a>
# **FetchSavedSearches**
> FetchAllSavedSearches200Response FetchSavedSearches (int id)

SavedSearch@show

Return a single saved search


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | saved search id |  |

### Return type

[**FetchAllSavedSearches200Response**](FetchAllSavedSearches200Response.md)

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

<a id="updatesavedsearches"></a>
# **UpdateSavedSearches**
> UpdateSavedSearches200Response UpdateSavedSearches (int id, UpdateSavedSearchesRequest updateSavedSearchesRequest)

SavedSearch@update

Update a saved search


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | saved search id |  |
| **updateSavedSearchesRequest** | [**UpdateSavedSearchesRequest**](UpdateSavedSearchesRequest.md) | Saved search definition |  |

### Return type

[**UpdateSavedSearches200Response**](UpdateSavedSearches200Response.md)

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

