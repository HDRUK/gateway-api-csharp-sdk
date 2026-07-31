# GatewayApiSdk.Api.KeywordApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateKeywords**](KeywordApi.md#createkeywords) | **POST** /api/v1/keywords | KeywordController@store |
| [**DeleteKeywords**](KeywordApi.md#deletekeywords) | **DELETE** /api/v1/keywords/{id} | KeywordController@destroy |
| [**EditKeywords**](KeywordApi.md#editkeywords) | **PATCH** /api/v1/keywords/{id} | KeywordController@update |
| [**FetchAllKeywords**](KeywordApi.md#fetchallkeywords) | **GET** /api/v1/keywords | KeywordController@index |
| [**FetchKeywords**](KeywordApi.md#fetchkeywords) | **GET** /api/v1/keywords/{id} | KeywordController@show |
| [**UpdateKeywords**](KeywordApi.md#updatekeywords) | **PUT** /api/v1/keywords/{id} | KeywordController@update |

<a id="createkeywords"></a>
# **CreateKeywords**
> CreateCategories200Response CreateKeywords (CreateCategoriesRequest createCategoriesRequest)

KeywordController@store

Creates a new keyword


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createCategoriesRequest** | [**CreateCategoriesRequest**](CreateCategoriesRequest.md) | Keyword definition |  |

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
| **409** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletekeywords"></a>
# **DeleteKeywords**
> DeleteAliases200Response DeleteKeywords (int id)

KeywordController@destroy

Delete a keyword by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | keyword id |  |

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

<a id="editkeywords"></a>
# **EditKeywords**
> UpdateKeywords200Response EditKeywords (int id, EditCategoriesRequest editCategoriesRequest)

KeywordController@update

Edit a keyword by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | keyword id |  |
| **editCategoriesRequest** | [**EditCategoriesRequest**](EditCategoriesRequest.md) | Category definition |  |

### Return type

[**UpdateKeywords200Response**](UpdateKeywords200Response.md)

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

<a id="fetchallkeywords"></a>
# **FetchAllKeywords**
> FetchAllKeywords200Response FetchAllKeywords (int perPage = null)

KeywordController@index

Returns a list of keywords


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | Alternative output schema version. | [optional]  |

### Return type

[**FetchAllKeywords200Response**](FetchAllKeywords200Response.md)

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

<a id="fetchkeywords"></a>
# **FetchKeywords**
> FetchKeywords200Response FetchKeywords (int id)

KeywordController@show

Return a single keyword


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | keyword id |  |

### Return type

[**FetchKeywords200Response**](FetchKeywords200Response.md)

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

<a id="updatekeywords"></a>
# **UpdateKeywords**
> UpdateKeywords200Response UpdateKeywords (int id, UpdateCategoriesRequest updateCategoriesRequest)

KeywordController@update

Update a keyword by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | keyword id |  |
| **updateCategoriesRequest** | [**UpdateCategoriesRequest**](UpdateCategoriesRequest.md) | Keyword definition |  |

### Return type

[**UpdateKeywords200Response**](UpdateKeywords200Response.md)

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

