# GatewayApiSdk.Api.EnquiryThreadApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateEnquiryThreads**](EnquiryThreadApi.md#createenquirythreads) | **POST** /api/v1/enquiry_threads | EnquiryThread@store |
| [**FetchAllEnquiryThreads**](EnquiryThreadApi.md#fetchallenquirythreads) | **GET** /api/v1/enquiry_threads | EnquiryThread@index |
| [**FetchEnquiryThreads**](EnquiryThreadApi.md#fetchenquirythreads) | **GET** /api/v1/enquiry_threads/{id} | EnquiryThread@show |

<a id="createenquirythreads"></a>
# **CreateEnquiryThreads**
> CreateCategories200Response CreateEnquiryThreads (CreateEnquiryThreadsRequest createEnquiryThreadsRequest)

EnquiryThread@store

Creates one or more new EnquiryThreads


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createEnquiryThreadsRequest** | [**CreateEnquiryThreadsRequest**](CreateEnquiryThreadsRequest.md) | EnquiryThread definition |  |

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

<a id="fetchallenquirythreads"></a>
# **FetchAllEnquiryThreads**
> FetchAllEnquiryThreads200Response FetchAllEnquiryThreads (int perPage = null)

EnquiryThread@index

Returns a list of EnquiryThreads from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | per page | [optional]  |

### Return type

[**FetchAllEnquiryThreads200Response**](FetchAllEnquiryThreads200Response.md)

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

<a id="fetchenquirythreads"></a>
# **FetchEnquiryThreads**
> FetchAllEnquiryThreads200Response FetchEnquiryThreads (int id)

EnquiryThread@show

Return a single EnquiryThread


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | EnquiryThread id |  |

### Return type

[**FetchAllEnquiryThreads200Response**](FetchAllEnquiryThreads200Response.md)

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

