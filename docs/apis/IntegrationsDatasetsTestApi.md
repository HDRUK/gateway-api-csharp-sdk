# GatewayApiSdk.Api.IntegrationsDatasetsTestApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**IntegrationsDatasetsTest**](IntegrationsDatasetsTestApi.md#integrationsdatasetstest) | **POST** /api/v1/integrations/datasets/test | IntegrationDatasetController@datasetTest |

<a id="integrationsdatasetstest"></a>
# **IntegrationsDatasetsTest**
> CreateDarIntegration201Response IntegrationsDatasetsTest (DatasetsTestRequest datasetsTestRequest)

IntegrationDatasetController@datasetTest

Integrations datasets test


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **datasetsTestRequest** | [**DatasetsTestRequest**](DatasetsTestRequest.md) | Pass datasets payload |  |

### Return type

[**CreateDarIntegration201Response**](CreateDarIntegration201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

