# GatewayApiSdk.Api.ProjectGrantApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**FetchAllProjectGrants**](ProjectGrantApi.md#fetchallprojectgrants) | **GET** /api/v1/project_grants | ProjectGrantController@index |
| [**FetchProjectGrant**](ProjectGrantApi.md#fetchprojectgrant) | **GET** /api/v1/project_grants/{id} | ProjectGrantController@show |

<a id="fetchallprojectgrants"></a>
# **FetchAllProjectGrants**
> FetchAllProjectGrants200Response FetchAllProjectGrants (string pid = null, int version = null, string projectGrantName = null, int userId = null, int teamId = null, bool withRelated = null)

ProjectGrantController@index

Get all project grants


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **pid** | **string** | Filter by dataset pid | [optional]  |
| **version** | **int** | Filter by dataset version number | [optional]  |
| **projectGrantName** | **string** | Filter by project grant name | [optional]  |
| **userId** | **int** | Filter by owning user id | [optional]  |
| **teamId** | **int** | Filter by owning team id | [optional]  |
| **withRelated** | **bool** |  | [optional]  |

### Return type

[**FetchAllProjectGrants200Response**](FetchAllProjectGrants200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchprojectgrant"></a>
# **FetchProjectGrant**
> CountUniqueFieldsCollections200Response FetchProjectGrant (int id, bool withRelated = null)

ProjectGrantController@show

Get a single project grant


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** |  |  |
| **withRelated** | **bool** |  | [optional]  |

### Return type

[**CountUniqueFieldsCollections200Response**](CountUniqueFieldsCollections200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

