# GatewayApiSdk.Api.ToolsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CountTeamUniqueFieldsToolsV2**](ToolsApi.md#countteamuniquefieldstoolsv2) | **GET** /api/v2/teams/{teamId}/tools/count/{field} | TeamToolController@count |
| [**CountUniqueFieldsTools**](ToolsApi.md#countuniquefieldstools) | **GET** /api/v1/tools/count/{field} | ToolController@count |
| [**CountUserUniqueFieldsToolsV2**](ToolsApi.md#countuseruniquefieldstoolsv2) | **GET** /api/v2/users/{userId}/tools/count/{field} | UserToolController@count |
| [**CreateTools**](ToolsApi.md#createtools) | **POST** /api/v1/tools | ToolController@store |
| [**CreateToolsByTeamV2**](ToolsApi.md#createtoolsbyteamv2) | **POST** /api/v2/teams/{teamId}/tools | ToolController@store |
| [**CreateToolsByUserV2**](ToolsApi.md#createtoolsbyuserv2) | **POST** /api/v2/users/{userId}/tools | UserToolController@store |
| [**CreateToolsIntegrations**](ToolsApi.md#createtoolsintegrations) | **POST** /api/v1/integrations/tools | IntegrationToolController@store |
| [**DeleteTools**](ToolsApi.md#deletetools) | **DELETE** /api/v1/tools/{id} | ToolController@destroy |
| [**DeleteToolsByTeamidV2**](ToolsApi.md#deletetoolsbyteamidv2) | **DELETE** /api/v2/teams/{teamId}/tools/{id} | TeamToolController@destroy |
| [**DeleteToolsByUserV2**](ToolsApi.md#deletetoolsbyuserv2) | **DELETE** /api/v2/users/{userId}/tools/{id} | UserToolController@destroy |
| [**DeleteToolsIntegrations**](ToolsApi.md#deletetoolsintegrations) | **DELETE** /api/v1/integrations/tools/{id} | IntegrationToolController@destroy |
| [**EditTools**](ToolsApi.md#edittools) | **PATCH** /api/v1/tools/{id} | ToolController@edit |
| [**EditToolsByTeamidV2**](ToolsApi.md#edittoolsbyteamidv2) | **PATCH** /api/v2/teams/{teamId}/tools/{id} | TeamToolController@edit |
| [**EditToolsByUserV2**](ToolsApi.md#edittoolsbyuserv2) | **PATCH** /api/v2/users/{userId}/tools/{id} | UserToolController@edit |
| [**EditToolsIntegrations**](ToolsApi.md#edittoolsintegrations) | **PATCH** /api/v1/integrations/tools/{id} | IntegrationToolController@edit |
| [**FetchAllToolByTeamAndStatusV2**](ToolsApi.md#fetchalltoolbyteamandstatusv2) | **GET** /api/v2/teams/{teamId}/tools/status/{status} | TeamToolController@indexStatus |
| [**FetchAllToolByUserAndStatusV2**](ToolsApi.md#fetchalltoolbyuserandstatusv2) | **GET** /api/v2/users/{userId}/tools/status/{status} | UserToolController@indexStatus |
| [**FetchAllTools**](ToolsApi.md#fetchalltools) | **GET** /api/v1/tools | Fetch all tools |
| [**FetchAllToolsIntegrations**](ToolsApi.md#fetchalltoolsintegrations) | **GET** /api/v1/integrations/tools | IntegrationToolController@index |
| [**FetchAllToolsV2**](ToolsApi.md#fetchalltoolsv2) | **GET** /api/v2/tools | ToolController@indexActive |
| [**FetchTools**](ToolsApi.md#fetchtools) | **GET** /api/v1/tools/{id} | ToolController@show |
| [**FetchToolsByTeamAndByIdV2**](ToolsApi.md#fetchtoolsbyteamandbyidv2) | **GET** /api/v2/teams/{teamId}/tools/{id} | TeamToolController@show |
| [**FetchToolsByUserAndByIdV2**](ToolsApi.md#fetchtoolsbyuserandbyidv2) | **GET** /api/v2/users/{userId}/tools/{id} | UserToolController@show |
| [**FetchToolsIntegrations**](ToolsApi.md#fetchtoolsintegrations) | **GET** /api/v1/integrations/tools/{id} | IntegrationToolController@show |
| [**FetchToolsV2**](ToolsApi.md#fetchtoolsv2) | **GET** /api/v2/tools/{id} | ToolController@showActive |
| [**UpdateTools**](ToolsApi.md#updatetools) | **PUT** /api/v1/tools/{id} | ToolController@update |
| [**UpdateToolsByTeamidV2**](ToolsApi.md#updatetoolsbyteamidv2) | **PUT** /api/v2/teams/{teamId}/tools/{id} | TeamToolController@update |
| [**UpdateToolsByUserV2**](ToolsApi.md#updatetoolsbyuserv2) | **PUT** /api/v2/users/{userId}/tools/{id} | UserToolController@update |
| [**UpdateToolsIntegrations**](ToolsApi.md#updatetoolsintegrations) | **PUT** /api/v1/integrations/tools/{id} | IntegrationToolController@update |

<a id="countteamuniquefieldstoolsv2"></a>
# **CountTeamUniqueFieldsToolsV2**
> CountUniqueFieldsCollections200Response CountTeamUniqueFieldsToolsV2 (int teamId, string field)

TeamToolController@count

Get team counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
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

<a id="countuniquefieldstools"></a>
# **CountUniqueFieldsTools**
> CountUniqueFieldsCollections200Response CountUniqueFieldsTools (string field, int teamId)

ToolController@count

Get Counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **field** | **string** | name of the field to perform a count on |  |
| **teamId** | **int** | team id |  |

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

<a id="countuseruniquefieldstoolsv2"></a>
# **CountUserUniqueFieldsToolsV2**
> CountUniqueFieldsCollections200Response CountUserUniqueFieldsToolsV2 (int userId, string field)

UserToolController@count

Get user counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
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

<a id="createtools"></a>
# **CreateTools**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateTools (CreateToolsRequest createToolsRequest)

ToolController@store

Create a new tool


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createToolsRequest** | [**CreateToolsRequest**](CreateToolsRequest.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **400** | bad request |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="createtoolsbyteamv2"></a>
# **CreateToolsByTeamV2**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateToolsByTeamV2 (int teamId, CreateToolsRequest createToolsRequest)

ToolController@store

Create a new tool by team v2


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **createToolsRequest** | [**CreateToolsRequest**](CreateToolsRequest.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **400** | bad request |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="createtoolsbyuserv2"></a>
# **CreateToolsByUserV2**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateToolsByUserV2 (int userId, CreateToolsRequest createToolsRequest)

UserToolController@store

Create a new tool by user v2


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
| **createToolsRequest** | [**CreateToolsRequest**](CreateToolsRequest.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **400** | bad request |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="createtoolsintegrations"></a>
# **CreateToolsIntegrations**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateToolsIntegrations (CreateToolsIntegrationsRequest createToolsIntegrationsRequest)

IntegrationToolController@store

Create a new tool


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createToolsIntegrationsRequest** | [**CreateToolsIntegrationsRequest**](CreateToolsIntegrationsRequest.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **400** | bad request |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletetools"></a>
# **DeleteTools**
> DeleteFederation200Response DeleteTools (int id)

ToolController@destroy

Delete tool by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | tool id |  |

### Return type

[**DeleteFederation200Response**](DeleteFederation200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **404** | Error response |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletetoolsbyteamidv2"></a>
# **DeleteToolsByTeamidV2**
> DeleteFederation200Response DeleteToolsByTeamidV2 (int teamId, int id)

TeamToolController@destroy

Delete tool by id and by team_id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | tool id |  |

### Return type

[**DeleteFederation200Response**](DeleteFederation200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **404** | Error response |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletetoolsbyuserv2"></a>
# **DeleteToolsByUserV2**
> DeleteFederation200Response DeleteToolsByUserV2 (int userId, int id)

UserToolController@destroy

Delete tool by id and by user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
| **id** | **int** | tool id |  |

### Return type

[**DeleteFederation200Response**](DeleteFederation200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **404** | Error response |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletetoolsintegrations"></a>
# **DeleteToolsIntegrations**
> DeleteFederation200Response DeleteToolsIntegrations (int id)

IntegrationToolController@destroy

Delete tool by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | tool id |  |

### Return type

[**DeleteFederation200Response**](DeleteFederation200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **404** | Error response |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="edittools"></a>
# **EditTools**
> FetchToolsIntegrations200Response EditTools (int id, UpdateToolsRequest updateToolsRequest, string unarchive = null)

ToolController@edit

Edit tool by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | tool id |  |
| **updateToolsRequest** | [**UpdateToolsRequest**](UpdateToolsRequest.md) | Pass user credentials |  |
| **unarchive** | **string** | Unarchive a tool | [optional]  |

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **400** | bad request |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="edittoolsbyteamidv2"></a>
# **EditToolsByTeamidV2**
> FetchToolsIntegrations200Response EditToolsByTeamidV2 (int teamId, int id, UpdateToolsRequest updateToolsRequest)

TeamToolController@edit

Edit tool by id and by teamid


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | tool id |  |
| **updateToolsRequest** | [**UpdateToolsRequest**](UpdateToolsRequest.md) | Pass user credentials |  |

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **400** | bad request |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="edittoolsbyuserv2"></a>
# **EditToolsByUserV2**
> FetchToolsIntegrations200Response EditToolsByUserV2 (int userId, int id, UpdateToolsRequest updateToolsRequest)

UserToolController@edit

Edit tool by id and by user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
| **id** | **int** | tool id |  |
| **updateToolsRequest** | [**UpdateToolsRequest**](UpdateToolsRequest.md) | Pass user credentials |  |

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **400** | bad request |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="edittoolsintegrations"></a>
# **EditToolsIntegrations**
> FetchToolsIntegrations200Response EditToolsIntegrations (int id, UpdateToolsIntegrationsRequest updateToolsIntegrationsRequest)

IntegrationToolController@edit

Edit tool by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | tool id |  |
| **updateToolsIntegrationsRequest** | [**UpdateToolsIntegrationsRequest**](UpdateToolsIntegrationsRequest.md) | Pass user credentials |  |

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Created |  -  |
| **400** | bad request |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchalltoolbyteamandstatusv2"></a>
# **FetchAllToolByTeamAndStatusV2**
> FetchAllToolsIntegrations200Response FetchAllToolByTeamAndStatusV2 (long teamId, string status)

TeamToolController@indexStatus

Returns a list of a teams tools with given status


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **long** | ID of the team |  |
| **status** | **string** | Status of the tool (active, draft, or archived). Defaults to active if not provided. | [default to active] |

### Return type

[**FetchAllToolsIntegrations200Response**](FetchAllToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchalltoolbyuserandstatusv2"></a>
# **FetchAllToolByUserAndStatusV2**
> FetchAllToolsIntegrations200Response FetchAllToolByUserAndStatusV2 (long userId, string status)

UserToolController@indexStatus

Returns a list of a user tools


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **long** | ID of the user |  |
| **status** | **string** | Status of the tool (active, draft, or archived). Defaults to active if not provided. | [default to active] |

### Return type

[**FetchAllToolsIntegrations200Response**](FetchAllToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchalltools"></a>
# **FetchAllTools**
> FetchAllTools200Response FetchAllTools (string mongoId = null, int teamId = null, int userId = null, string title = null, string sort = null)

Fetch all tools

Get all tools with optional filters and sorting


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **mongoId** | **string** | Filter tools by mongo ID | [optional]  |
| **teamId** | **int** | Filter tools by team ID | [optional]  |
| **userId** | **int** | Filter tools by user ID | [optional]  |
| **title** | **string** | Filter tools by title | [optional]  |
| **sort** | **string** | Sort tools by a specific field and direction, e.g., &#39;name:asc&#39; or &#39;created_at:desc&#39; | [optional]  |

### Return type

[**FetchAllTools200Response**](FetchAllTools200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **400** | Bad request response |  -  |
| **500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchalltoolsintegrations"></a>
# **FetchAllToolsIntegrations**
> FetchAllToolsIntegrations200Response FetchAllToolsIntegrations ()

IntegrationToolController@index

Get All Tools


### Parameters
This endpoint does not need any parameter.
### Return type

[**FetchAllToolsIntegrations200Response**](FetchAllToolsIntegrations200Response.md)

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

<a id="fetchalltoolsv2"></a>
# **FetchAllToolsV2**
> FetchAllTools200Response FetchAllToolsV2 (string name = null, string sort = null)

ToolController@indexActive

Get all tools with optional filters and sorting


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **name** | **string** | Filter tools by name | [optional]  |
| **sort** | **string** | Sort tools by a specific field and direction, e.g., &#39;name:asc&#39; or &#39;created_at:desc&#39; | [optional]  |

### Return type

[**FetchAllTools200Response**](FetchAllTools200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **400** | Bad request response |  -  |
| **500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchtools"></a>
# **FetchTools**
> FetchToolsIntegrations200Response FetchTools (int id, string viewType = null)

ToolController@show

Get tool by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | tool id |  |
| **viewType** | **string** | Query flag to show full tool data or a trimmed version (defaults to full). | [optional] [default to &quot;full&quot;] |

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchtoolsbyteamandbyidv2"></a>
# **FetchToolsByTeamAndByIdV2**
> FetchToolsIntegrations200Response FetchToolsByTeamAndByIdV2 (int teamId, int id, string viewType = null)

TeamToolController@show

Get tool by team id and by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | tool id |  |
| **viewType** | **string** | Query flag to show full tool data or a trimmed version (defaults to full). | [optional] [default to &quot;full&quot;] |

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchtoolsbyuserandbyidv2"></a>
# **FetchToolsByUserAndByIdV2**
> FetchToolsIntegrations200Response FetchToolsByUserAndByIdV2 (int userId, int id, string viewType = null)

UserToolController@show

Get tool by user id and by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
| **id** | **int** | tool id |  |
| **viewType** | **string** | Query flag to show full tool data or a trimmed version (defaults to full). | [optional] [default to &quot;full&quot;] |

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchtoolsintegrations"></a>
# **FetchToolsIntegrations**
> FetchToolsIntegrations200Response FetchToolsIntegrations (int id)

IntegrationToolController@show

Get tool by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | tool id |  |

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchtoolsv2"></a>
# **FetchToolsV2**
> FetchToolsIntegrations200Response FetchToolsV2 (int id)

ToolController@showActive

Get tool by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | tool id |  |

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updatetools"></a>
# **UpdateTools**
> FetchToolsIntegrations200Response UpdateTools (int id, UpdateToolsRequest updateToolsRequest)

ToolController@update

Update tool by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | tool id |  |
| **updateToolsRequest** | [**UpdateToolsRequest**](UpdateToolsRequest.md) | Pass user credentials |  |

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **400** | bad request |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updatetoolsbyteamidv2"></a>
# **UpdateToolsByTeamidV2**
> FetchToolsIntegrations200Response UpdateToolsByTeamidV2 (int teamId, int id, UpdateToolsRequest updateToolsRequest)

TeamToolController@update

Update tools by team id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | tool id |  |
| **updateToolsRequest** | [**UpdateToolsRequest**](UpdateToolsRequest.md) | Pass user credentials |  |

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **400** | bad request |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updatetoolsbyuserv2"></a>
# **UpdateToolsByUserV2**
> FetchToolsIntegrations200Response UpdateToolsByUserV2 (int userId, int id, UpdateToolsRequest updateToolsRequest)

UserToolController@update

Update tools by user id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | user id |  |
| **id** | **int** | tool id |  |
| **updateToolsRequest** | [**UpdateToolsRequest**](UpdateToolsRequest.md) | Pass user credentials |  |

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **400** | bad request |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updatetoolsintegrations"></a>
# **UpdateToolsIntegrations**
> FetchToolsIntegrations200Response UpdateToolsIntegrations (int id, UpdateToolsIntegrationsRequest updateToolsIntegrationsRequest)

IntegrationToolController@update

Update tool by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | tool id |  |
| **updateToolsIntegrationsRequest** | [**UpdateToolsIntegrationsRequest**](UpdateToolsIntegrationsRequest.md) | Pass user credentials |  |

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Created |  -  |
| **400** | bad request |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

