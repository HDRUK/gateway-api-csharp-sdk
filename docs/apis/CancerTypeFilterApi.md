# GatewayApiSdk.Api.CancerTypeFilterApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**GetCancerTypeFilter**](CancerTypeFilterApi.md#getcancertypefilter) | **GET** /api/v1/cancer-type-filters/{filter_id} | Get a single cancer type filter |
| [**GetCancerTypeFilters**](CancerTypeFilterApi.md#getcancertypefilters) | **GET** /api/v1/cancer-type-filters | Get all cancer type filters |

<a id="getcancertypefilter"></a>
# **GetCancerTypeFilter**
> GetCancerTypeFilter200Response GetCancerTypeFilter (string filterId)

Get a single cancer type filter

Returns a single cancer type filter with its children by filter_id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **filterId** | **string** | Filter ID (e.g., 0_0, 0_0_2_59) |  |

### Return type

[**GetCancerTypeFilter200Response**](GetCancerTypeFilter200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **404** | Not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="getcancertypefilters"></a>
# **GetCancerTypeFilters**
> GetCancerTypeFilters200Response GetCancerTypeFilters (int parentId = null, int level = null)

Get all cancer type filters

Returns a hierarchical tree of cancer type filters


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **parentId** | **int** | Filter by parent ID | [optional]  |
| **level** | **int** | Filter by hierarchy level | [optional]  |

### Return type

[**GetCancerTypeFilters200Response**](GetCancerTypeFilters200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

