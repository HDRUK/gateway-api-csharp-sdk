# GatewayApiSdk.Api.LicenseApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**B34ab4eadc1eaed469678151e6e71b9f**](LicenseApi.md#b34ab4eadc1eaed469678151e6e71b9f) | **GET** /api/v1/licenses | License@index |
| [**Call2721b23c1df3b4e71706e4ab04f9b0a8**](LicenseApi.md#call2721b23c1df3b4e71706e4ab04f9b0a8) | **POST** /api/v1/licenses | License@store |
| [**Call50c6be78401c528ffdf4ed00414e7678**](LicenseApi.md#call50c6be78401c528ffdf4ed00414e7678) | **GET** /api/v1/licenses/{id} | License@show |
| [**Call98a20646cb4164cddd79725baf3dcf61**](LicenseApi.md#call98a20646cb4164cddd79725baf3dcf61) | **PUT** /api/v1/licenses/{id} | License@update |
| [**Call991d716a8c83b7e3c4747583eeffc0ee**](LicenseApi.md#call991d716a8c83b7e3c4747583eeffc0ee) | **DELETE** /api/v1/licenses/{id} | License@destroy |
| [**Fc8a99b7173f11228400fac2754185fa**](LicenseApi.md#fc8a99b7173f11228400fac2754185fa) | **PATCH** /api/v1/licenses/{id} | License@edit |

<a id="b34ab4eadc1eaed469678151e6e71b9f"></a>
# **B34ab4eadc1eaed469678151e6e71b9f**
> B34ab4eadc1eaed469678151e6e71b9f200Response B34ab4eadc1eaed469678151e6e71b9f ()

License@index

Returns a list of licenses available


### Parameters
This endpoint does not need any parameter.
### Return type

[**B34ab4eadc1eaed469678151e6e71b9f200Response**](B34ab4eadc1eaed469678151e6e71b9f200Response.md)

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

<a id="call2721b23c1df3b4e71706e4ab04f9b0a8"></a>
# **Call2721b23c1df3b4e71706e4ab04f9b0a8**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Call2721b23c1df3b4e71706e4ab04f9b0a8 (Model2721b23c1df3b4e71706e4ab04f9b0a8Request model2721b23c1df3b4e71706e4ab04f9b0a8Request)

License@store

Creates a new license


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model2721b23c1df3b4e71706e4ab04f9b0a8Request** | [**Model2721b23c1df3b4e71706e4ab04f9b0a8Request**](Model2721b23c1df3b4e71706e4ab04f9b0a8Request.md) | License definition |  |

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

<a id="call50c6be78401c528ffdf4ed00414e7678"></a>
# **Call50c6be78401c528ffdf4ed00414e7678**
> Model50c6be78401c528ffdf4ed00414e7678200Response Call50c6be78401c528ffdf4ed00414e7678 (int id)

License@show

Return a single license


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | License ID |  |

### Return type

[**Model50c6be78401c528ffdf4ed00414e7678200Response**](Model50c6be78401c528ffdf4ed00414e7678200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call98a20646cb4164cddd79725baf3dcf61"></a>
# **Call98a20646cb4164cddd79725baf3dcf61**
> Model98a20646cb4164cddd79725baf3dcf61200Response Call98a20646cb4164cddd79725baf3dcf61 (int id, Model2721b23c1df3b4e71706e4ab04f9b0a8Request model2721b23c1df3b4e71706e4ab04f9b0a8Request)

License@update

Update a tool license


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | license id |  |
| **model2721b23c1df3b4e71706e4ab04f9b0a8Request** | [**Model2721b23c1df3b4e71706e4ab04f9b0a8Request**](Model2721b23c1df3b4e71706e4ab04f9b0a8Request.md) | Category definition |  |

### Return type

[**Model98a20646cb4164cddd79725baf3dcf61200Response**](Model98a20646cb4164cddd79725baf3dcf61200Response.md)

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

<a id="call991d716a8c83b7e3c4747583eeffc0ee"></a>
# **Call991d716a8c83b7e3c4747583eeffc0ee**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call991d716a8c83b7e3c4747583eeffc0ee (int id)

License@destroy

Delete a License


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | License id |  |

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

<a id="fc8a99b7173f11228400fac2754185fa"></a>
# **Fc8a99b7173f11228400fac2754185fa**
> Model98a20646cb4164cddd79725baf3dcf61200Response Fc8a99b7173f11228400fac2754185fa (int id, Model2721b23c1df3b4e71706e4ab04f9b0a8Request model2721b23c1df3b4e71706e4ab04f9b0a8Request)

License@edit

Edit a tool license


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | license id |  |
| **model2721b23c1df3b4e71706e4ab04f9b0a8Request** | [**Model2721b23c1df3b4e71706e4ab04f9b0a8Request**](Model2721b23c1df3b4e71706e4ab04f9b0a8Request.md) | Category definition |  |

### Return type

[**Model98a20646cb4164cddd79725baf3dcf61200Response**](Model98a20646cb4164cddd79725baf3dcf61200Response.md)

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

