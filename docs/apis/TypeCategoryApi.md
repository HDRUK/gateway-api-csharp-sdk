# GatewayApiSdk.Api.TypeCategoryApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateTypeCategories**](TypeCategoryApi.md#createtypecategories) | **POST** /api/v1/type_categories | TypeCategory@store |
| [**DeleteTypeCategories**](TypeCategoryApi.md#deletetypecategories) | **DELETE** /api/v1/type_categories/{id} | TypeCategory@destroy |
| [**EditTypeCategories**](TypeCategoryApi.md#edittypecategories) | **PATCH** /api/v1/type_categories/{id} | TypeCategory@update |
| [**FetchAllTypeCategories**](TypeCategoryApi.md#fetchalltypecategories) | **GET** /api/v1/type_categories | TypeCategory@index |
| [**FetchTypeCategories**](TypeCategoryApi.md#fetchtypecategories) | **GET** /api/v1/type_categories/{id} | TypeCategory@show |
| [**UpdateTypeCategories**](TypeCategoryApi.md#updatetypecategories) | **PUT** /api/v1/type_categories/{id} | TypeCategory@update |

<a id="createtypecategories"></a>
# **CreateTypeCategories**
> CreateCategories200Response CreateTypeCategories (CreateTypeCategoriesRequest createTypeCategoriesRequest)

TypeCategory@store

Creates a new system type category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createTypeCategoriesRequest** | [**CreateTypeCategoriesRequest**](CreateTypeCategoriesRequest.md) | Programming language definition |  |

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

<a id="deletetypecategories"></a>
# **DeleteTypeCategories**
> DeleteAliases200Response DeleteTypeCategories (int id)

TypeCategory@destroy

Delete a system type category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | type category id |  |

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

<a id="edittypecategories"></a>
# **EditTypeCategories**
> UpdateTypeCategories200Response EditTypeCategories (int id, EditCategoriesRequest editCategoriesRequest)

TypeCategory@update

Edit a system type category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | type category id |  |
| **editCategoriesRequest** | [**EditCategoriesRequest**](EditCategoriesRequest.md) | TypeCategory definition |  |

### Return type

[**UpdateTypeCategories200Response**](UpdateTypeCategories200Response.md)

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

<a id="fetchalltypecategories"></a>
# **FetchAllTypeCategories**
> FetchAllTypeCategories200Response FetchAllTypeCategories ()

TypeCategory@index

Returns a list of type categories enabled on the system


### Parameters
This endpoint does not need any parameter.
### Return type

[**FetchAllTypeCategories200Response**](FetchAllTypeCategories200Response.md)

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

<a id="fetchtypecategories"></a>
# **FetchTypeCategories**
> FetchTypeCategories200Response FetchTypeCategories (int id)

TypeCategory@show

Return a single system type category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | type category id |  |

### Return type

[**FetchTypeCategories200Response**](FetchTypeCategories200Response.md)

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

<a id="updatetypecategories"></a>
# **UpdateTypeCategories**
> UpdateTypeCategories200Response UpdateTypeCategories (int id, UpdateTypeCategoriesRequest updateTypeCategoriesRequest)

TypeCategory@update

Update a system type category


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | type category id |  |
| **updateTypeCategoriesRequest** | [**UpdateTypeCategoriesRequest**](UpdateTypeCategoriesRequest.md) | TypeCategory definition |  |

### Return type

[**UpdateTypeCategories200Response**](UpdateTypeCategories200Response.md)

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

