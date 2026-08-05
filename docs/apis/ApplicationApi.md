# GatewayApiSdk.Api.ApplicationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateApplications**](ApplicationApi.md#createapplications) | **POST** /api/v1/applications | ApplicationController@store |
| [**DeleteApplications**](ApplicationApi.md#deleteapplications) | **DELETE** /api/v1/applications/{id} | ApplicationController@delete |
| [**EditApplications**](ApplicationApi.md#editapplications) | **PATCH** /api/v1/applications/{id} | ApplicationController@edit |
| [**FetchAllApplications**](ApplicationApi.md#fetchallapplications) | **GET** /api/v1/applications | ApplicationController@index |
| [**FetchAllSitemap**](ApplicationApi.md#fetchallsitemap) | **GET** /api/v1/sitemap | SiteMapController@index |
| [**FetchApplications**](ApplicationApi.md#fetchapplications) | **GET** /api/v1/applications/{id} | ApplicationController@show |
| [**PatchApplicationsClientId**](ApplicationApi.md#patchapplicationsclientid) | **PATCH** /api/v1/applications/{id}/clientid | ApplicationController@generateClientIdById |
| [**UpdateApplications**](ApplicationApi.md#updateapplications) | **PUT** /api/v1/applications/{id} | ApplicationController@update |

<a id="createapplications"></a>
# **CreateApplications**
> CreateApplications200Response CreateApplications (CreateApplicationsRequest createApplicationsRequest)

ApplicationController@store

Creates application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createApplicationsRequest** | [**CreateApplicationsRequest**](CreateApplicationsRequest.md) | Application definition |  |

### Return type

[**CreateApplications200Response**](CreateApplications200Response.md)

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

<a id="deleteapplications"></a>
# **DeleteApplications**
> DeleteApplications200Response DeleteApplications (int id)

ApplicationController@delete

Delete application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | application id |  |

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
| **404** | Not found response |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="editapplications"></a>
# **EditApplications**
> UpdateApplications200Response EditApplications (int id, EditApplicationsRequest editApplicationsRequest)

ApplicationController@edit

Edit application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | application id |  |
| **editApplicationsRequest** | [**EditApplicationsRequest**](EditApplicationsRequest.md) | ActivityLog definition |  |

### Return type

[**UpdateApplications200Response**](UpdateApplications200Response.md)

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

<a id="fetchallapplications"></a>
# **FetchAllApplications**
> FetchAllApplications200Response FetchAllApplications (int teamId = null, string text = null, string status = null)

ApplicationController@index

Returns a list of applications


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Filter Apps by the teamId | [optional]  |
| **text** | **string** | Search term to filter by application name or description. | [optional]  |
| **status** | **string** | Filter by application status is enabled or not (true or false). | [optional]  |

### Return type

[**FetchAllApplications200Response**](FetchAllApplications200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchallsitemap"></a>
# **FetchAllSitemap**
> FetchAllSitemap200Response FetchAllSitemap ()

SiteMapController@index

Returns a list of all ids and last updated date for Collections, Data Custodians, Data Custodian Networks, Durs, DataSets, Tools


### Parameters
This endpoint does not need any parameter.
### Return type

[**FetchAllSitemap200Response**](FetchAllSitemap200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchapplications"></a>
# **FetchApplications**
> FetchApplications200Response FetchApplications (int id)

ApplicationController@show

Get application by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | application id |  |

### Return type

[**FetchApplications200Response**](FetchApplications200Response.md)

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

<a id="patchapplicationsclientid"></a>
# **PatchApplicationsClientId**
> UpdateApplications200Response PatchApplicationsClientId (int id)

ApplicationController@generateClientIdById

Generate Client ID application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | application id |  |

### Return type

[**UpdateApplications200Response**](UpdateApplications200Response.md)

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

<a id="updateapplications"></a>
# **UpdateApplications**
> UpdateApplications200Response UpdateApplications (int id, UpdateApplicationsRequest updateApplicationsRequest)

ApplicationController@update

Update application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | application id |  |
| **updateApplicationsRequest** | [**UpdateApplicationsRequest**](UpdateApplicationsRequest.md) | ActivityLog definition |  |

### Return type

[**UpdateApplications200Response**](UpdateApplications200Response.md)

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

