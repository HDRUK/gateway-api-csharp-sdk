# GatewayApiSdk.Api.ApplicationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**C724575805bbca0f084a3001d71abd53**](ApplicationApi.md#c724575805bbca0f084a3001d71abd53) | **PATCH** /api/v1/applications/{id}/clientid | ApplicationController@generateClientIdById |
| [**Call3c8adeb001330f5198ca1072be78e299**](ApplicationApi.md#call3c8adeb001330f5198ca1072be78e299) | **PUT** /api/v1/applications/{id} | ApplicationController@update |
| [**Call45ae3b415211ef0712a8ea070e66449f**](ApplicationApi.md#call45ae3b415211ef0712a8ea070e66449f) | **PATCH** /api/v1/applications/{id} | ApplicationController@edit |
| [**Ddca747ae792e5b6837b97c6ad510fd3**](ApplicationApi.md#ddca747ae792e5b6837b97c6ad510fd3) | **DELETE** /api/v1/applications/{id} | ApplicationController@delete |
| [**E210052adcf6fdcfc472998b430081aa**](ApplicationApi.md#e210052adcf6fdcfc472998b430081aa) | **POST** /api/v1/applications | ApplicationController@store |
| [**FetchAllApplications**](ApplicationApi.md#fetchallapplications) | **GET** /api/v1/applications | ApplicationController@index |
| [**FetchAllSitemap**](ApplicationApi.md#fetchallsitemap) | **GET** /api/v1/sitemap | SiteMapController@index |
| [**FetchApplications**](ApplicationApi.md#fetchapplications) | **GET** /api/v1/applications/{id} | ApplicationController@show |

<a id="c724575805bbca0f084a3001d71abd53"></a>
# **C724575805bbca0f084a3001d71abd53**
> Model3c8adeb001330f5198ca1072be78e299200Response C724575805bbca0f084a3001d71abd53 (int id)

ApplicationController@generateClientIdById

Generate Client ID application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | application id |  |

### Return type

[**Model3c8adeb001330f5198ca1072be78e299200Response**](Model3c8adeb001330f5198ca1072be78e299200Response.md)

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

<a id="call3c8adeb001330f5198ca1072be78e299"></a>
# **Call3c8adeb001330f5198ca1072be78e299**
> Model3c8adeb001330f5198ca1072be78e299200Response Call3c8adeb001330f5198ca1072be78e299 (int id, Model3c8adeb001330f5198ca1072be78e299Request model3c8adeb001330f5198ca1072be78e299Request)

ApplicationController@update

Update application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | application id |  |
| **model3c8adeb001330f5198ca1072be78e299Request** | [**Model3c8adeb001330f5198ca1072be78e299Request**](Model3c8adeb001330f5198ca1072be78e299Request.md) | ActivityLog definition |  |

### Return type

[**Model3c8adeb001330f5198ca1072be78e299200Response**](Model3c8adeb001330f5198ca1072be78e299200Response.md)

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

<a id="call45ae3b415211ef0712a8ea070e66449f"></a>
# **Call45ae3b415211ef0712a8ea070e66449f**
> Model3c8adeb001330f5198ca1072be78e299200Response Call45ae3b415211ef0712a8ea070e66449f (int id, Model45ae3b415211ef0712a8ea070e66449fRequest model45ae3b415211ef0712a8ea070e66449fRequest)

ApplicationController@edit

Edit application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | application id |  |
| **model45ae3b415211ef0712a8ea070e66449fRequest** | [**Model45ae3b415211ef0712a8ea070e66449fRequest**](Model45ae3b415211ef0712a8ea070e66449fRequest.md) | ActivityLog definition |  |

### Return type

[**Model3c8adeb001330f5198ca1072be78e299200Response**](Model3c8adeb001330f5198ca1072be78e299200Response.md)

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

<a id="ddca747ae792e5b6837b97c6ad510fd3"></a>
# **Ddca747ae792e5b6837b97c6ad510fd3**
> C29b5b3424f7317b69b4bda048ccfafb200Response Ddca747ae792e5b6837b97c6ad510fd3 (int id)

ApplicationController@delete

Delete application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | application id |  |

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

<a id="e210052adcf6fdcfc472998b430081aa"></a>
# **E210052adcf6fdcfc472998b430081aa**
> E210052adcf6fdcfc472998b430081aa200Response E210052adcf6fdcfc472998b430081aa (E210052adcf6fdcfc472998b430081aaRequest e210052adcf6fdcfc472998b430081aaRequest)

ApplicationController@store

Creates application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **e210052adcf6fdcfc472998b430081aaRequest** | [**E210052adcf6fdcfc472998b430081aaRequest**](E210052adcf6fdcfc472998b430081aaRequest.md) | Application definition |  |

### Return type

[**E210052adcf6fdcfc472998b430081aa200Response**](E210052adcf6fdcfc472998b430081aa200Response.md)

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

