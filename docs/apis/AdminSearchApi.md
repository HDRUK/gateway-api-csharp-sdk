# GatewayApiSdk.Api.AdminSearchApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call4ff0fc5e7c66284608ce55dc6cb7d846**](AdminSearchApi.md#call4ff0fc5e7c66284608ce55dc6cb7d846) | **POST** /api/v1/admin/search/feature | Activate or deactivate a search-related Pennant feature flag |
| [**Call8918bd9dfb8e055a335f3c0695428e73**](AdminSearchApi.md#call8918bd9dfb8e055a335f3c0695428e73) | **GET** /api/v1/admin/search/status | Get Typesense collection status for every onboarded search entity |
| [**Call92a06ea019f5560b5c9e76e02fe38e31**](AdminSearchApi.md#call92a06ea019f5560b5c9e76e02fe38e31) | **POST** /api/v1/admin/search/reindex | Queue a drop+recreate+import of a search entity&#39;s Typesense collection |

<a id="call4ff0fc5e7c66284608ce55dc6cb7d846"></a>
# **Call4ff0fc5e7c66284608ce55dc6cb7d846**
> void Call4ff0fc5e7c66284608ce55dc6cb7d846 (Model4ff0fc5e7c66284608ce55dc6cb7d846Request model4ff0fc5e7c66284608ce55dc6cb7d846Request)

Activate or deactivate a search-related Pennant feature flag


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model4ff0fc5e7c66284608ce55dc6cb7d846Request** | [**Model4ff0fc5e7c66284608ce55dc6cb7d846Request**](Model4ff0fc5e7c66284608ce55dc6cb7d846Request.md) |  |  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **422** | Unknown feature |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call8918bd9dfb8e055a335f3c0695428e73"></a>
# **Call8918bd9dfb8e055a335f3c0695428e73**
> void Call8918bd9dfb8e055a335f3c0695428e73 ()

Get Typesense collection status for every onboarded search entity


### Parameters
This endpoint does not need any parameter.
### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call92a06ea019f5560b5c9e76e02fe38e31"></a>
# **Call92a06ea019f5560b5c9e76e02fe38e31**
> void Call92a06ea019f5560b5c9e76e02fe38e31 (Model92a06ea019f5560b5c9e76e02fe38e31Request model92a06ea019f5560b5c9e76e02fe38e31Request)

Queue a drop+recreate+import of a search entity's Typesense collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model92a06ea019f5560b5c9e76e02fe38e31Request** | [**Model92a06ea019f5560b5c9e76e02fe38e31Request**](Model92a06ea019f5560b5c9e76e02fe38e31Request.md) |  |  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **202** | Reindex queued |  -  |
| **422** | Unknown entity |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

