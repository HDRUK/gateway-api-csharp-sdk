# GatewayApiSdk.Api.TeamDataAccessApplicationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CountTeamDarApplications**](TeamDataAccessApplicationApi.md#countteamdarapplications) | **GET** /api/v1/teams/{teamId}/dar/applications/count | TeamDataAccessApplicationController@allCounts |
| [**CountUniqueFieldsDarApplications**](TeamDataAccessApplicationApi.md#countuniquefieldsdarapplications) | **GET** /api/v1/teams/{teamId}/dar/applications/count/{field} | TeamDataAccessApplicationController@count |
| [**FetchTeamDarApplication**](TeamDataAccessApplicationApi.md#fetchteamdarapplication) | **GET** /api/v1/teams/{teamId}/dar/applications/{id} | TeamDataAccessApplicationController@show |
| [**FetchTeamDarApplicationHeader**](TeamDataAccessApplicationApi.md#fetchteamdarapplicationheader) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/showHeader | TeamDataAccessApplicationController@showHeader |
| [**FetchTeamDarApplications**](TeamDataAccessApplicationApi.md#fetchteamdarapplications) | **GET** /api/v1/teams/{teamId}/dar/applications | TeamDataAccessApplicationController@index |

<a id="countteamdarapplications"></a>
# **CountTeamDarApplications**
> CountUniqueFieldsCollections200Response CountTeamDarApplications (int teamId)

TeamDataAccessApplicationController@allCounts

Get Counts for all status fields in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |

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

<a id="countuniquefieldsdarapplications"></a>
# **CountUniqueFieldsDarApplications**
> CountUniqueFieldsCollections200Response CountUniqueFieldsDarApplications (int teamId, string field)

TeamDataAccessApplicationController@count

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

<a id="fetchteamdarapplication"></a>
# **FetchTeamDarApplication**
> FetchTeamDarApplication200Response FetchTeamDarApplication (int teamId, int id)

TeamDataAccessApplicationController@show

Return a single DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**FetchTeamDarApplication200Response**](FetchTeamDarApplication200Response.md)

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

<a id="fetchteamdarapplicationheader"></a>
# **FetchTeamDarApplicationHeader**
> FetchTeamDarApplicationHeader200Response FetchTeamDarApplicationHeader (int teamId, int id)

TeamDataAccessApplicationController@showHeader

Get header information about a specific DAR


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**FetchTeamDarApplicationHeader200Response**](FetchTeamDarApplicationHeader200Response.md)

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

<a id="fetchteamdarapplications"></a>
# **FetchTeamDarApplications**
> FetchTeamDarApplications200Response FetchTeamDarApplications (int teamId)

TeamDataAccessApplicationController@index

List of dar applications belonging to a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |

### Return type

[**FetchTeamDarApplications200Response**](FetchTeamDarApplications200Response.md)

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

