# GatewayApiSdk.Api.TeamDataAccessTemplateApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**DeleteTeamDarTemplateFile**](TeamDataAccessTemplateApi.md#deleteteamdartemplatefile) | **DELETE** /api/v1/teams/{teamId}/dar/templates/{id}/files/{fileId} | TeamDataAccessTemplateController@destroyFile |
| [**FetchTeamDarTemplates**](TeamDataAccessTemplateApi.md#fetchteamdartemplates) | **GET** /api/v1/teams/{teamId}/dar/templates | TeamDataAccessTemplateController@index |
| [**TeamDarTemplateCountUniqueFields**](TeamDataAccessTemplateApi.md#teamdartemplatecountuniquefields) | **GET** /api/v1/teams/{teamId}/dar/templates/count/{field} | TeamDataAccessTemplateController@count |

<a id="deleteteamdartemplatefile"></a>
# **DeleteTeamDarTemplateFile**
> DeleteApplications200Response DeleteTeamDarTemplateFile (int teamId, int id, string fileId)

TeamDataAccessTemplateController@destroyFile

Delete a file associated with a DAR template


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR template id |  |
| **fileId** | **string** | File id |  |

### Return type

[**DeleteApplications200Response**](DeleteApplications200Response.md)

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

<a id="fetchteamdartemplates"></a>
# **FetchTeamDarTemplates**
> FetchDarTemplates200Response FetchTeamDarTemplates (int teamId, string published = null)

TeamDataAccessTemplateController@index

List of dar templates belonging to a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **published** | **string** | Template publication status to filter by (true, false) | [optional]  |

### Return type

[**FetchDarTemplates200Response**](FetchDarTemplates200Response.md)

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

