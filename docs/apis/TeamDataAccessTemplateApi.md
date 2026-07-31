# GatewayApiSdk.Api.TeamDataAccessTemplateApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call471df4f14ed1f13bf3a66f1a8b70e261**](TeamDataAccessTemplateApi.md#call471df4f14ed1f13bf3a66f1a8b70e261) | **DELETE** /api/v1/teams/{teamId}/dar/templates/{id}/files/{fileId} | TeamDataAccessTemplateController@destroyFile |
| [**Call883e72f80ed3577c8e6eca9f9437e554**](TeamDataAccessTemplateApi.md#call883e72f80ed3577c8e6eca9f9437e554) | **GET** /api/v1/teams/{teamId}/dar/templates | TeamDataAccessTemplateController@index |
| [**TeamDarTemplateCountUniqueFields**](TeamDataAccessTemplateApi.md#teamdartemplatecountuniquefields) | **GET** /api/v1/teams/{teamId}/dar/templates/count/{field} | TeamDataAccessTemplateController@count |

<a id="call471df4f14ed1f13bf3a66f1a8b70e261"></a>
# **Call471df4f14ed1f13bf3a66f1a8b70e261**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call471df4f14ed1f13bf3a66f1a8b70e261 (int teamId, int id, string fileId)

TeamDataAccessTemplateController@destroyFile

Delete a file associated with a DAR template


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR template id |  |
| **fileId** | **string** | File id |  |

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
| **401** | Unauthorized |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call883e72f80ed3577c8e6eca9f9437e554"></a>
# **Call883e72f80ed3577c8e6eca9f9437e554**
> Model234386e06c6b29d5aaca2ed8f89cb9aa200Response Call883e72f80ed3577c8e6eca9f9437e554 (int teamId, string published = null)

TeamDataAccessTemplateController@index

List of dar templates belonging to a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **published** | **string** | Template publication status to filter by (true, false) | [optional]  |

### Return type

[**Model234386e06c6b29d5aaca2ed8f89cb9aa200Response**](Model234386e06c6b29d5aaca2ed8f89cb9aa200Response.md)

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

<a id="teamdartemplatecountuniquefields"></a>
# **TeamDarTemplateCountUniqueFields**
> CountUniqueFieldsCollections200Response TeamDarTemplateCountUniqueFields (int teamId, string field)

TeamDataAccessTemplateController@count

Get Counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
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

