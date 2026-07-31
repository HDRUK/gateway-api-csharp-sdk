# GatewayApiSdk.Api.WidgetsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**A439b274e045e4ae8ab3006c33290aff**](WidgetsApi.md#a439b274e045e4ae8ab3006c33290aff) | **GET** /api/v1/teams/{teamId}/widgets/data | WidgetController@getWidgetData |
| [**C9939b681f1c7deb438e5d7a25ea9509**](WidgetsApi.md#c9939b681f1c7deb438e5d7a25ea9509) | **PATCH** /api/v1/teams/{teamId}/widgets/{id} | Update an existing widget |
| [**CreateWidget**](WidgetsApi.md#createwidget) | **POST** /api/v1/teams/{teamId}/widgets | Create a new widget |
| [**DeleteWidget**](WidgetsApi.md#deletewidget) | **DELETE** /api/v1/teams/{teamId}/widgets/{id} | Delete a widget |
| [**FetchAllWidgets**](WidgetsApi.md#fetchallwidgets) | **GET** /api/v1/teams/{teamId}/widgets | WidgetController@index |
| [**FetchWidget**](WidgetsApi.md#fetchwidget) | **GET** /api/v1/teams/{teamId}/widgets/{id} | WidgetController@retrieve |
| [**RetrieveWidgetData**](WidgetsApi.md#retrievewidgetdata) | **GET** /api/v1/teams/{teamId}/widgets/{id}/data | Retrieve data related to a widget |
| [**TrackWidgetEvent**](WidgetsApi.md#trackwidgetevent) | **POST** /api/v1/teams/{teamId}/widgets/{id}/track | Record a widget analytics event |
| [**WidgetAnalytics**](WidgetsApi.md#widgetanalytics) | **GET** /api/v1/teams/{teamId}/widgets/analytics | Get widget analytics for a team |

<a id="a439b274e045e4ae8ab3006c33290aff"></a>
# **A439b274e045e4ae8ab3006c33290aff**
> A439b274e045e4ae8ab3006c33290aff200Response A439b274e045e4ae8ab3006c33290aff (int teamId, string teamIds)

WidgetController@getWidgetData

Fetch lightweight data (id, name, etc.) for multiple teams across datasets, tools, collections, and DURS


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team ID |  |
| **teamIds** | **string** | Comma-separated list of team IDs to filter data |  |

### Return type

[**A439b274e045e4ae8ab3006c33290aff200Response**](A439b274e045e4ae8ab3006c33290aff200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Aggregated data retrieved successfully |  -  |
| **400** | Invalid or missing teamIds parameter |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="c9939b681f1c7deb438e5d7a25ea9509"></a>
# **C9939b681f1c7deb438e5d7a25ea9509**
> C9939b681f1c7deb438e5d7a25ea9509200Response C9939b681f1c7deb438e5d7a25ea9509 (int teamId, int id, C9939b681f1c7deb438e5d7a25ea9509Request c9939b681f1c7deb438e5d7a25ea9509Request = null)

Update an existing widget

Updates an existing widget for a given team ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team ID |  |
| **id** | **int** | Widget ID |  |
| **c9939b681f1c7deb438e5d7a25ea9509Request** | [**C9939b681f1c7deb438e5d7a25ea9509Request**](C9939b681f1c7deb438e5d7a25ea9509Request.md) |  | [optional]  |

### Return type

[**C9939b681f1c7deb438e5d7a25ea9509200Response**](C9939b681f1c7deb438e5d7a25ea9509200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Widget successfully updated |  -  |
| **404** | Widget not found |  -  |
| **500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="createwidget"></a>
# **CreateWidget**
> CreateWidget201Response CreateWidget (int teamId, CreateWidgetRequest createWidgetRequest)

Create a new widget

Creates a new widget for a given team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team ID the widget belongs to |  |
| **createWidgetRequest** | [**CreateWidgetRequest**](CreateWidgetRequest.md) |  |  |

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Widget created successfully |  -  |
| **400** | Validation failed |  -  |
| **500** | Server error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletewidget"></a>
# **DeleteWidget**
> C29b5b3424f7317b69b4bda048ccfafb200Response DeleteWidget (int teamId, int id)

Delete a widget

Soft delete a widget belonging to a specific team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team ID |  |
| **id** | **int** | Widget ID |  |

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
| **404** | Widget not found |  -  |
| **200** | Widget deleted successfully |  -  |
| **500** | Server error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchallwidgets"></a>
# **FetchAllWidgets**
> FetchAllWidgets200Response FetchAllWidgets (int teamId)

WidgetController@index

Get All Widgets


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team ID |  |

### Return type

[**FetchAllWidgets200Response**](FetchAllWidgets200Response.md)

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

<a id="fetchwidget"></a>
# **FetchWidget**
> FetchWidget200Response FetchWidget (int teamId, int id)

WidgetController@retrieve

Get a single Widget


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team ID |  |
| **id** | **int** | Widget ID |  |

### Return type

[**FetchWidget200Response**](FetchWidget200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **404** | Widget not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="retrievewidgetdata"></a>
# **RetrieveWidgetData**
> RetrieveWidgetData200Response RetrieveWidgetData (int teamId, int id, string domainOrigin)

Retrieve data related to a widget

Fetches datasets, data uses, scripts, and collections linked to a widget


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team ID |  |
| **id** | **int** | Widget ID |  |
| **domainOrigin** | **string** | Optional domain URL to check against the widget&#39;s permitted_domains list |  |

### Return type

[**RetrieveWidgetData200Response**](RetrieveWidgetData200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **403** | Forbidden — domain not permitted for this widget |  -  |
| **200** | Widget data retrieved successfully |  -  |
| **404** | Widget not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="trackwidgetevent"></a>
# **TrackWidgetEvent**
> void TrackWidgetEvent (int teamId, int id, TrackWidgetEventRequest trackWidgetEventRequest)

Record a widget analytics event

Public endpoint for frontend clients to record user interactions with a widget (page views, code copies, gateway clicks, searches). No authentication required.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** |  |  |
| **id** | **int** |  |  |
| **trackWidgetEventRequest** | [**TrackWidgetEventRequest**](TrackWidgetEventRequest.md) |  |  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **204** | Event recorded |  -  |
| **404** | Widget not found |  -  |
| **422** | Validation error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="widgetanalytics"></a>
# **WidgetAnalytics**
> WidgetAnalytics200Response WidgetAnalytics (int teamId, string from = null, string to = null, string groupBy = null)

Get widget analytics for a team

Returns aggregated event counts per widget, per event type, and over time. Supports date range filtering and time-based grouping.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** |  |  |
| **from** | **string** | Start date (Y-m-d) | [optional]  |
| **to** | **string** | End date (Y-m-d) | [optional]  |
| **groupBy** | **string** | Time granularity | [optional] [default to day] |

### Return type

[**WidgetAnalytics200Response**](WidgetAnalytics200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Analytics data |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

