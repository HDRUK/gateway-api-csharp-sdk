# GatewayApiSdk.Api.TeamFederationsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateFederationTeam**](TeamFederationsApi.md#createfederationteam) | **POST** /api/v1/teams/{teamId}/federations | FederationController@store |
| [**DeleteFederation**](TeamFederationsApi.md#deletefederation) | **DELETE** /api/v1/teams/{teamId}/federations/{federationId} | FederationController@destroy |
| [**EditFederationTeam**](TeamFederationsApi.md#editfederationteam) | **PATCH** /api/v1/teams/{teamId}/federations/{federationId} | FederationController@edit |
| [**GetFederationByFederationIdAndTeamId**](TeamFederationsApi.md#getfederationbyfederationidandteamid) | **GET** /api/v1/teams/{teamId}/federations/{federationId} | FederationController@show |
| [**GetFederationHistory**](TeamFederationsApi.md#getfederationhistory) | **GET** /api/v1/teams/{teamId}/federations/{federationId}/history | FederationController@history |
| [**GetFederationTeamId**](TeamFederationsApi.md#getfederationteamid) | **GET** /api/v1/teams/{teamId}/federations | FederationController@index |
| [**RunFederation**](TeamFederationsApi.md#runfederation) | **GET** /api/v1/teams/{teamId}/federations/{federationId}/run | FederationController@runNow |
| [**TestFederation**](TeamFederationsApi.md#testfederation) | **POST** /api/v1/teams/{teamId}/federations/test | FederationController@testFederation |
| [**UpdateFederationTeam**](TeamFederationsApi.md#updatefederationteam) | **PUT** /api/v1/teams/{teamId}/federations/{federationId} | FederationController@update |

<a id="createfederationteam"></a>
# **CreateFederationTeam**
> CreateCategories200Response CreateFederationTeam (int teamId, CreateFederationTeamRequest createFederationTeamRequest)

FederationController@store

Create federation


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **createFederationTeamRequest** | [**CreateFederationTeamRequest**](CreateFederationTeamRequest.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletefederation"></a>
# **DeleteFederation**
> DeleteFederation200Response DeleteFederation (int teamId, int federationId)

FederationController@destroy

Delete federation for team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **federationId** | **int** | federation id |  |

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

<a id="editfederationteam"></a>
# **EditFederationTeam**
> CreateCategories200Response EditFederationTeam (int teamId, int federationId, CreateFederationTeamRequest createFederationTeamRequest)

FederationController@edit

Edit federation for team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **federationId** | **int** | federation id |  |
| **createFederationTeamRequest** | [**CreateFederationTeamRequest**](CreateFederationTeamRequest.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="getfederationbyfederationidandteamid"></a>
# **GetFederationByFederationIdAndTeamId**
> GetFederationByFederationIdAndTeamId200Response GetFederationByFederationIdAndTeamId (int teamId, int federationId)

FederationController@show

Get federation by federation id from team id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **federationId** | **int** | federation id |  |

### Return type

[**GetFederationByFederationIdAndTeamId200Response**](GetFederationByFederationIdAndTeamId200Response.md)

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

<a id="getfederationhistory"></a>
# **GetFederationHistory**
> GetFederationHistory200Response GetFederationHistory (int teamId, int federationId, int perPage = null)

FederationController@history

Get run history for a federation


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **federationId** | **int** | federation id |  |
| **perPage** | **int** | per page | [optional]  |

### Return type

[**GetFederationHistory200Response**](GetFederationHistory200Response.md)

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

<a id="getfederationteamid"></a>
# **GetFederationTeamId**
> GetFederationTeamId200Response GetFederationTeamId (int teamId)

FederationController@index

Get federations by team id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |

### Return type

[**GetFederationTeamId200Response**](GetFederationTeamId200Response.md)

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

<a id="runfederation"></a>
# **RunFederation**
> TestFederation200Response RunFederation (int teamId, int federationId)

FederationController@runNow

Run federation immediately


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **federationId** | **int** | federation id |  |

### Return type

[**TestFederation200Response**](TestFederation200Response.md)

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

<a id="testfederation"></a>
# **TestFederation**
> TestFederation200Response TestFederation (int teamId)

FederationController@testFederation

Test federation configuration


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |

### Return type

[**TestFederation200Response**](TestFederation200Response.md)

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

<a id="updatefederationteam"></a>
# **UpdateFederationTeam**
> CreateCategories200Response UpdateFederationTeam (int teamId, int federationId, UpdateFederationTeamRequest updateFederationTeamRequest)

FederationController@update

Update federation for team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **federationId** | **int** | federation id |  |
| **updateFederationTeamRequest** | [**UpdateFederationTeamRequest**](UpdateFederationTeamRequest.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

