# GatewayApiSdk.Api.SavedSearchApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call39500344ecf1a14150bbe26c4a138c56**](SavedSearchApi.md#call39500344ecf1a14150bbe26c4a138c56) | **POST** /api/v1/saved_searches | SavedSearch@store |
| [**Call3b59d921ea47286a669054ef67350b03**](SavedSearchApi.md#call3b59d921ea47286a669054ef67350b03) | **PUT** /api/v1/saved_searches/{id} | SavedSearch@update |
| [**Call4f2a3c56631a5fccb45a9e7972df02b0**](SavedSearchApi.md#call4f2a3c56631a5fccb45a9e7972df02b0) | **GET** /api/v1/saved_searches | SavedSearch@index |
| [**Call8d6878e4937dd67c5e2480c6f4e9149f**](SavedSearchApi.md#call8d6878e4937dd67c5e2480c6f4e9149f) | **GET** /api/v1/saved_searches/{id} | SavedSearch@show |
| [**Cdcdceead49fe1554534af83c50c8af5**](SavedSearchApi.md#cdcdceead49fe1554534af83c50c8af5) | **DELETE** /api/v1/saved_searches/{id} | SavedSearch@destroy |
| [**Fa314398c7a73002fee4ffc7e62e9fb6**](SavedSearchApi.md#fa314398c7a73002fee4ffc7e62e9fb6) | **PATCH** /api/v1/saved_searches/{id} | SavedSearch@update |

<a id="call39500344ecf1a14150bbe26c4a138c56"></a>
# **Call39500344ecf1a14150bbe26c4a138c56**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Call39500344ecf1a14150bbe26c4a138c56 (Model39500344ecf1a14150bbe26c4a138c56Request model39500344ecf1a14150bbe26c4a138c56Request)

SavedSearch@store

Creates a new saved search


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model39500344ecf1a14150bbe26c4a138c56Request** | [**Model39500344ecf1a14150bbe26c4a138c56Request**](Model39500344ecf1a14150bbe26c4a138c56Request.md) | Saved search definition |  |

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
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call3b59d921ea47286a669054ef67350b03"></a>
# **Call3b59d921ea47286a669054ef67350b03**
> Model3b59d921ea47286a669054ef67350b03200Response Call3b59d921ea47286a669054ef67350b03 (int id, Model3b59d921ea47286a669054ef67350b03Request model3b59d921ea47286a669054ef67350b03Request)

SavedSearch@update

Update a saved search


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | saved search id |  |
| **model3b59d921ea47286a669054ef67350b03Request** | [**Model3b59d921ea47286a669054ef67350b03Request**](Model3b59d921ea47286a669054ef67350b03Request.md) | Saved search definition |  |

### Return type

[**Model3b59d921ea47286a669054ef67350b03200Response**](Model3b59d921ea47286a669054ef67350b03200Response.md)

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

<a id="call4f2a3c56631a5fccb45a9e7972df02b0"></a>
# **Call4f2a3c56631a5fccb45a9e7972df02b0**
> Model4f2a3c56631a5fccb45a9e7972df02b0200Response Call4f2a3c56631a5fccb45a9e7972df02b0 (int perPage = null)

SavedSearch@index

Returns a list of saved searches enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | Specify number of results per page | [optional]  |

### Return type

[**Model4f2a3c56631a5fccb45a9e7972df02b0200Response**](Model4f2a3c56631a5fccb45a9e7972df02b0200Response.md)

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

<a id="call8d6878e4937dd67c5e2480c6f4e9149f"></a>
# **Call8d6878e4937dd67c5e2480c6f4e9149f**
> Model4f2a3c56631a5fccb45a9e7972df02b0200Response Call8d6878e4937dd67c5e2480c6f4e9149f (int id)

SavedSearch@show

Return a single saved search


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | saved search id |  |

### Return type

[**Model4f2a3c56631a5fccb45a9e7972df02b0200Response**](Model4f2a3c56631a5fccb45a9e7972df02b0200Response.md)

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

<a id="cdcdceead49fe1554534af83c50c8af5"></a>
# **Cdcdceead49fe1554534af83c50c8af5**
> C29b5b3424f7317b69b4bda048ccfafb200Response Cdcdceead49fe1554534af83c50c8af5 (int id)

SavedSearch@destroy

Delete a saved search


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | saved search id |  |

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

<a id="fa314398c7a73002fee4ffc7e62e9fb6"></a>
# **Fa314398c7a73002fee4ffc7e62e9fb6**
> Model3b59d921ea47286a669054ef67350b03200Response Fa314398c7a73002fee4ffc7e62e9fb6 (int id, Fa314398c7a73002fee4ffc7e62e9fb6Request fa314398c7a73002fee4ffc7e62e9fb6Request)

SavedSearch@update

Edit a saved search


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | saved search id |  |
| **fa314398c7a73002fee4ffc7e62e9fb6Request** | [**Fa314398c7a73002fee4ffc7e62e9fb6Request**](Fa314398c7a73002fee4ffc7e62e9fb6Request.md) | Saved search definition |  |

### Return type

[**Model3b59d921ea47286a669054ef67350b03200Response**](Model3b59d921ea47286a669054ef67350b03200Response.md)

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

