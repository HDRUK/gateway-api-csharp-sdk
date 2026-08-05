# GatewayApiSdk.Api.CustomerSatisfactionApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateCsat**](CustomerSatisfactionApi.md#createcsat) | **POST** /api/v1/csat | Create Customer Satisfaction Score |
| [**EditCsat**](CustomerSatisfactionApi.md#editcsat) | **PATCH** /api/v1/csat/{id} | Update Customer Satisfaction Description |

<a id="createcsat"></a>
# **CreateCsat**
> DeleteApplications200Response CreateCsat (CreateCsatRequest createCsatRequest)

Create Customer Satisfaction Score

Creates a customer satisfaction score between 0 and 5


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createCsatRequest** | [**CreateCsatRequest**](CreateCsatRequest.md) | Customer Satisfaction score |  |

### Return type

[**DeleteApplications200Response**](DeleteApplications200Response.md)

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

<a id="editcsat"></a>
# **EditCsat**
> EditCsat200Response EditCsat (int id, EditCsatRequest editCsatRequest)

Update Customer Satisfaction Description

Update a description for a satisfaction score entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID of the CSAT entry |  |
| **editCsatRequest** | [**EditCsatRequest**](EditCsatRequest.md) | Reason to update |  |

### Return type

[**EditCsat200Response**](EditCsat200Response.md)

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

