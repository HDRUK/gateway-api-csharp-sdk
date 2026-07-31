# GatewayApiSdk.Api.CategoryApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateCategories**](CategoryApi.md#createcategories) | **POST** /api/v1/categories | Category@store |
| [**DeleteCategories**](CategoryApi.md#deletecategories) | **DELETE** /api/v1/categories/{id} | Category@destroy |
| [**EditCategories**](CategoryApi.md#editcategories) | **PATCH** /api/v1/categories/{id} | Category@update |
| [**FetchAllCategories**](CategoryApi.md#fetchallcategories) | **GET** /api/v1/categories | Category@index |
| [**FetchCategories**](CategoryApi.md#fetchcategories) | **GET** /api/v1/categories/{id} | Category@show |
| [**UpdateCategories**](CategoryApi.md#updatecategories) | **PUT** /api/v1/categories/{id} | Category@update |

<a id="createcategories"></a>
# **CreateCategories**
> CreateCategories200Response CreateCategories (CreateCategoriesRequest createCategoriesRequest)

Category@store

Creates a new tool category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createCategoriesRequest** | [**CreateCategoriesRequest**](CreateCategoriesRequest.md) | Category definition |  |

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

<a id="deletecategories"></a>
# **DeleteCategories**
> DeleteAliases200Response DeleteCategories (int id)

Category@destroy

Delete a tool category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | category id |  |

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

<a id="editcategories"></a>
# **EditCategories**
> UpdateCategories200Response EditCategories (int id, EditCategoriesRequest editCategoriesRequest)

Category@update

Edit a tool category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | category id |  |
| **editCategoriesRequest** | [**EditCategoriesRequest**](EditCategoriesRequest.md) | Category definition |  |

### Return type

[**UpdateCategories200Response**](UpdateCategories200Response.md)

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

<a id="fetchallcategories"></a>
# **FetchAllCategories**
> FetchAllCategories200Response FetchAllCategories (int perPage = null)

Category@index

Returns a list of categories enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | per page | [optional]  |

### Return type

[**FetchAllCategories200Response**](FetchAllCategories200Response.md)

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

<a id="fetchcategories"></a>
# **FetchCategories**
> FetchAllCategories200Response FetchCategories (int id)

Category@show

Return a single tool category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | category id |  |

### Return type

[**FetchAllCategories200Response**](FetchAllCategories200Response.md)

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

<a id="updatecategories"></a>
# **UpdateCategories**
> UpdateCategories200Response UpdateCategories (int id, UpdateCategoriesRequest updateCategoriesRequest)

Category@update

Update a tool category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | category id |  |
| **updateCategoriesRequest** | [**UpdateCategoriesRequest**](UpdateCategoriesRequest.md) | Category definition |  |

### Return type

[**UpdateCategories200Response**](UpdateCategories200Response.md)

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

