# GatewayApiSdk.Api.EnquiryThreadApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**A961db529080eb3a29e4b7cc13dabaaa**](EnquiryThreadApi.md#a961db529080eb3a29e4b7cc13dabaaa) | **POST** /api/v1/enquiry_threads | EnquiryThread@store |
| [**Call4321ab5e45636e3e917c94fd21edac28**](EnquiryThreadApi.md#call4321ab5e45636e3e917c94fd21edac28) | **GET** /api/v1/enquiry_threads | EnquiryThread@index |
| [**Fd828cd8df74859b18600bb6b36edf83**](EnquiryThreadApi.md#fd828cd8df74859b18600bb6b36edf83) | **GET** /api/v1/enquiry_threads/{id} | EnquiryThread@show |

<a id="a961db529080eb3a29e4b7cc13dabaaa"></a>
# **A961db529080eb3a29e4b7cc13dabaaa**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response A961db529080eb3a29e4b7cc13dabaaa (A961db529080eb3a29e4b7cc13dabaaaRequest a961db529080eb3a29e4b7cc13dabaaaRequest)

EnquiryThread@store

Creates one or more new EnquiryThreads


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **a961db529080eb3a29e4b7cc13dabaaaRequest** | [**A961db529080eb3a29e4b7cc13dabaaaRequest**](A961db529080eb3a29e4b7cc13dabaaaRequest.md) | EnquiryThread definition |  |

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

<a id="call4321ab5e45636e3e917c94fd21edac28"></a>
# **Call4321ab5e45636e3e917c94fd21edac28**
> Model4321ab5e45636e3e917c94fd21edac28200Response Call4321ab5e45636e3e917c94fd21edac28 (int perPage = null)

EnquiryThread@index

Returns a list of EnquiryThreads from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | per page | [optional]  |

### Return type

[**Model4321ab5e45636e3e917c94fd21edac28200Response**](Model4321ab5e45636e3e917c94fd21edac28200Response.md)

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

<a id="fd828cd8df74859b18600bb6b36edf83"></a>
# **Fd828cd8df74859b18600bb6b36edf83**
> Model4321ab5e45636e3e917c94fd21edac28200Response Fd828cd8df74859b18600bb6b36edf83 (int id)

EnquiryThread@show

Return a single EnquiryThread


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | EnquiryThread id |  |

### Return type

[**Model4321ab5e45636e3e917c94fd21edac28200Response**](Model4321ab5e45636e3e917c94fd21edac28200Response.md)

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

