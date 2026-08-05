# GatewayApiSdk.Api.NotificationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**DeleteNotifications**](NotificationApi.md#deletenotifications) | **DELETE** /api/v1/notifications/{id} | Notification@destroy |

<a id="deletenotifications"></a>
# **DeleteNotifications**
> DeleteApplications200Response DeleteNotifications (int id)

Notification@destroy

Delete a notification


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | notification id |  |

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

