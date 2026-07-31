# GatewayApiSdk.Api.FormHydrationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**GetFormSchema**](FormHydrationApi.md#getformschema) | **GET** /api/v1/form_hydration/schema | Retrieve form schema data |
| [**OnboardingFormHydration**](FormHydrationApi.md#onboardingformhydration) | **GET** /api/v1/form_hydration | Retrieve form schema data |

<a id="getformschema"></a>
# **GetFormSchema**
> Object GetFormSchema (string model = null, string version = null)

Retrieve form schema data

Retrieves form schema data based on the provided model and version.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model** | **string** | The model for which form schema is requested. | [optional]  |
| **version** | **string** | The version of the model for which form schema is requested. | [optional]  |

### Return type

**Object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |
| **400** | Bad request. Missing required parameters or invalid parameters. |  -  |
| **500** | Internal server error. Failed to retrieve form schema data. |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="onboardingformhydration"></a>
# **OnboardingFormHydration**
> Object OnboardingFormHydration (string name = null, string version = null, string dataTypes = null)

Retrieve form schema data

Retrieves form schema data based on the provided model and version.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **name** | **string** | The model name for which form schema is requested. | [optional]  |
| **version** | **string** | The version of the model for which form schema is requested. | [optional]  |
| **dataTypes** | **string** | The data types of the dataset about to be onboarded. | [optional]  |

### Return type

**Object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |
| **400** | Bad request. Missing required parameters or invalid parameters. |  -  |
| **500** | Internal server error. Failed to retrieve form schema data. |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

