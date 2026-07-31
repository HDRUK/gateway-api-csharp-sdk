# GatewayApiSdk.Api.NotificationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateNotifications**](NotificationApi.md#createnotifications) | **POST** /api/v1/notifications | Notification@store |
| [**DeleteNotifications**](NotificationApi.md#deletenotifications) | **DELETE** /api/v1/notifications/{id} | Notification@destroy |
| [**EditNotifications**](NotificationApi.md#editnotifications) | **PATCH** /api/v1/notifications/{id} | Notification@edit |
| [**FetchAllNotifications**](NotificationApi.md#fetchallnotifications) | **GET** /api/v1/notifications | Notification@index |
| [**FetchNotifications**](NotificationApi.md#fetchnotifications) | **GET** /api/v1/notifications/{id} | Notification@show |
| [**UpdateNotifications**](NotificationApi.md#updatenotifications) | **PUT** /api/v1/notifications/{id} | Notification@update |

<a id="createnotifications"></a>
# **CreateNotifications**
> CreateCategories200Response CreateNotifications (CreateNotificationsRequest createNotificationsRequest)

Notification@store

Creates a new notification


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createNotificationsRequest** | [**CreateNotificationsRequest**](CreateNotificationsRequest.md) | Notification definition |  |

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
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletenotifications"></a>
# **DeleteNotifications**
> DeleteAliases200Response DeleteNotifications (int id)

Notification@destroy

Delete a notification


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | notification id |  |

### Return type

[**DeleteAliases200Response**](DeleteAliases200Response.md)

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

<a id="editnotifications"></a>
# **EditNotifications**
> UpdateNotifications200Response EditNotifications (int id, EditNotificationsRequest editNotificationsRequest)

Notification@edit

Edit a notification


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | notification id |  |
| **editNotificationsRequest** | [**EditNotificationsRequest**](EditNotificationsRequest.md) | Notification definition |  |

### Return type

[**UpdateNotifications200Response**](UpdateNotifications200Response.md)

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

<a id="fetchallnotifications"></a>
# **FetchAllNotifications**
> FetchAllNotifications200Response FetchAllNotifications ()

Notification@index

Returns a list of notifications enabled on the system


### Parameters
This endpoint does not need any parameter.
### Return type

[**FetchAllNotifications200Response**](FetchAllNotifications200Response.md)

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

<a id="fetchnotifications"></a>
# **FetchNotifications**
> FetchNotifications200Response FetchNotifications (int id)

Notification@show

Return a single notification


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | notification id |  |

### Return type

[**FetchNotifications200Response**](FetchNotifications200Response.md)

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

<a id="updatenotifications"></a>
# **UpdateNotifications**
> UpdateNotifications200Response UpdateNotifications (int id, CreateNotificationsRequest createNotificationsRequest)

Notification@update

Update a notification


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | notification id |  |
| **createNotificationsRequest** | [**CreateNotificationsRequest**](CreateNotificationsRequest.md) | Notification definition |  |

### Return type

[**UpdateNotifications200Response**](UpdateNotifications200Response.md)

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

