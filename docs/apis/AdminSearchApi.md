# GatewayApiSdk.Api.AdminSearchApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateAdminSearchReindex**](AdminSearchApi.md#createadminsearchreindex) | **POST** /api/v1/admin/search/reindex | Queue a drop+recreate+import of a search entity&#39;s Typesense collection |
| [**FetchAdminSearchStatus**](AdminSearchApi.md#fetchadminsearchstatus) | **GET** /api/v1/admin/search/status | Get Typesense collection status for every onboarded search entity |
| [**UpdateAdminSearchFeature**](AdminSearchApi.md#updateadminsearchfeature) | **POST** /api/v1/admin/search/feature | Activate or deactivate a search-related Pennant feature flag |

<a id="createadminsearchreindex"></a>
# **CreateAdminSearchReindex**
> void CreateAdminSearchReindex (CreateAdminSearchReindexRequest createAdminSearchReindexRequest)

Queue a drop+recreate+import of a search entity's Typesense collection


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createAdminSearchReindexRequest** | [**CreateAdminSearchReindexRequest**](CreateAdminSearchReindexRequest.md) |  |  |

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

<a id="fetchadminsearchstatus"></a>
# **FetchAdminSearchStatus**
> void FetchAdminSearchStatus ()

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

<a id="updateadminsearchfeature"></a>
# **UpdateAdminSearchFeature**
> void UpdateAdminSearchFeature (UpdateAdminSearchFeatureRequest updateAdminSearchFeatureRequest)

Activate or deactivate a search-related Pennant feature flag


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **updateAdminSearchFeatureRequest** | [**UpdateAdminSearchFeatureRequest**](UpdateAdminSearchFeatureRequest.md) |  |  |

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

