# GatewayApiSdk.Api.NotificationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**A5ca86d5f19ecac396cb830333f307da**](NotificationApi.md#a5ca86d5f19ecac396cb830333f307da) | **PATCH** /api/v1/notifications/{id} | Notification@edit |
| [**B4f86f6c4f52e080b246d560038cdc9b**](NotificationApi.md#b4f86f6c4f52e080b246d560038cdc9b) | **PUT** /api/v1/notifications/{id} | Notification@update |
| [**Cac3bdde44f0be0512f7d05c0a6064e4**](NotificationApi.md#cac3bdde44f0be0512f7d05c0a6064e4) | **GET** /api/v1/notifications | Notification@index |
| [**Call1fd84d2c66035574da4902f416cbd96a**](NotificationApi.md#call1fd84d2c66035574da4902f416cbd96a) | **POST** /api/v1/notifications | Notification@store |
| [**Call22581e4d73af25a9036c6610c7e8fc72**](NotificationApi.md#call22581e4d73af25a9036c6610c7e8fc72) | **GET** /api/v1/notifications/{id} | Notification@show |
| [**Call3f8fe68ea04e79015d8aad5912cadbc1**](NotificationApi.md#call3f8fe68ea04e79015d8aad5912cadbc1) | **DELETE** /api/v1/notifications/{id} | Notification@destroy |

<a id="a5ca86d5f19ecac396cb830333f307da"></a>
# **A5ca86d5f19ecac396cb830333f307da**
> B4f86f6c4f52e080b246d560038cdc9b200Response A5ca86d5f19ecac396cb830333f307da (int id, A5ca86d5f19ecac396cb830333f307daRequest a5ca86d5f19ecac396cb830333f307daRequest)

Notification@edit

Edit a notification


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | notification id |  |
| **a5ca86d5f19ecac396cb830333f307daRequest** | [**A5ca86d5f19ecac396cb830333f307daRequest**](A5ca86d5f19ecac396cb830333f307daRequest.md) | Notification definition |  |

### Return type

[**B4f86f6c4f52e080b246d560038cdc9b200Response**](B4f86f6c4f52e080b246d560038cdc9b200Response.md)

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

<a id="b4f86f6c4f52e080b246d560038cdc9b"></a>
# **B4f86f6c4f52e080b246d560038cdc9b**
> B4f86f6c4f52e080b246d560038cdc9b200Response B4f86f6c4f52e080b246d560038cdc9b (int id, Model1fd84d2c66035574da4902f416cbd96aRequest model1fd84d2c66035574da4902f416cbd96aRequest)

Notification@update

Update a notification


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | notification id |  |
| **model1fd84d2c66035574da4902f416cbd96aRequest** | [**Model1fd84d2c66035574da4902f416cbd96aRequest**](Model1fd84d2c66035574da4902f416cbd96aRequest.md) | Notification definition |  |

### Return type

[**B4f86f6c4f52e080b246d560038cdc9b200Response**](B4f86f6c4f52e080b246d560038cdc9b200Response.md)

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

<a id="cac3bdde44f0be0512f7d05c0a6064e4"></a>
# **Cac3bdde44f0be0512f7d05c0a6064e4**
> Cac3bdde44f0be0512f7d05c0a6064e4200Response Cac3bdde44f0be0512f7d05c0a6064e4 ()

Notification@index

Returns a list of notifications enabled on the system


### Parameters
This endpoint does not need any parameter.
### Return type

[**Cac3bdde44f0be0512f7d05c0a6064e4200Response**](Cac3bdde44f0be0512f7d05c0a6064e4200Response.md)

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

<a id="call1fd84d2c66035574da4902f416cbd96a"></a>
# **Call1fd84d2c66035574da4902f416cbd96a**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Call1fd84d2c66035574da4902f416cbd96a (Model1fd84d2c66035574da4902f416cbd96aRequest model1fd84d2c66035574da4902f416cbd96aRequest)

Notification@store

Creates a new notification


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model1fd84d2c66035574da4902f416cbd96aRequest** | [**Model1fd84d2c66035574da4902f416cbd96aRequest**](Model1fd84d2c66035574da4902f416cbd96aRequest.md) | Notification definition |  |

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
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call22581e4d73af25a9036c6610c7e8fc72"></a>
# **Call22581e4d73af25a9036c6610c7e8fc72**
> Model22581e4d73af25a9036c6610c7e8fc72200Response Call22581e4d73af25a9036c6610c7e8fc72 (int id)

Notification@show

Return a single notification


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | notification id |  |

### Return type

[**Model22581e4d73af25a9036c6610c7e8fc72200Response**](Model22581e4d73af25a9036c6610c7e8fc72200Response.md)

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

<a id="call3f8fe68ea04e79015d8aad5912cadbc1"></a>
# **Call3f8fe68ea04e79015d8aad5912cadbc1**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call3f8fe68ea04e79015d8aad5912cadbc1 (int id)

Notification@destroy

Delete a notification


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | notification id |  |

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

