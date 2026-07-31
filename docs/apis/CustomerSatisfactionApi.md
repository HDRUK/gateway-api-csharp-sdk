# GatewayApiSdk.Api.CustomerSatisfactionApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call2e155418e5f0de41829414447919439e**](CustomerSatisfactionApi.md#call2e155418e5f0de41829414447919439e) | **PATCH** /api/v1/csat/{id} | Update Customer Satisfaction Description |
| [**Call3604171bd1ea2588906fe1cf65353366**](CustomerSatisfactionApi.md#call3604171bd1ea2588906fe1cf65353366) | **POST** /api/v1/csat | Create Customer Satisfaction Score |

<a id="call2e155418e5f0de41829414447919439e"></a>
# **Call2e155418e5f0de41829414447919439e**
> Model2e155418e5f0de41829414447919439e200Response Call2e155418e5f0de41829414447919439e (int id, Model2e155418e5f0de41829414447919439eRequest model2e155418e5f0de41829414447919439eRequest)

Update Customer Satisfaction Description

Update a description for a satisfaction score entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID of the CSAT entry |  |
| **model2e155418e5f0de41829414447919439eRequest** | [**Model2e155418e5f0de41829414447919439eRequest**](Model2e155418e5f0de41829414447919439eRequest.md) | Reason to update |  |

### Return type

[**Model2e155418e5f0de41829414447919439e200Response**](Model2e155418e5f0de41829414447919439e200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Update successful |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call3604171bd1ea2588906fe1cf65353366"></a>
# **Call3604171bd1ea2588906fe1cf65353366**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call3604171bd1ea2588906fe1cf65353366 (Model3604171bd1ea2588906fe1cf65353366Request model3604171bd1ea2588906fe1cf65353366Request)

Create Customer Satisfaction Score

Creates a customer satisfaction score between 0 and 5


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model3604171bd1ea2588906fe1cf65353366Request** | [**Model3604171bd1ea2588906fe1cf65353366Request**](Model3604171bd1ea2588906fe1cf65353366Request.md) | Customer Satisfaction score |  |

### Return type

[**C29b5b3424f7317b69b4bda048ccfafb200Response**](C29b5b3424f7317b69b4bda048ccfafb200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Resource Created |  -  |
| **422** | Validation Error |  -  |
| **500** | Internal Server Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

