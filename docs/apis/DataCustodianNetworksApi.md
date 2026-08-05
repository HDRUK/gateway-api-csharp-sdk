# GatewayApiSdk.Api.DataCustodianNetworksApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**FetchDataCustodianNetwork**](DataCustodianNetworksApi.md#fetchdatacustodiannetwork) | **GET** /api/v2/data_custodian_networks/{id} | DataCustodianNetworks@show |
| [**FetchDataCustodianNetworkCustodiansSummary**](DataCustodianNetworksApi.md#fetchdatacustodiannetworkcustodianssummary) | **GET** /api/v2/data_custodian_networks/{id}/custodians_summary | DataCustodianNetworks@showCustodiansSummary |
| [**FetchDataCustodianNetworkDatasetsSummary**](DataCustodianNetworksApi.md#fetchdatacustodiannetworkdatasetssummary) | **GET** /api/v2/data_custodian_networks/{id}/datasets_summary | DataCustodianNetworks@showDatasetsSummary |
| [**FetchDataCustodianNetworkEntitiesSummary**](DataCustodianNetworksApi.md#fetchdatacustodiannetworkentitiessummary) | **GET** /api/v2/data_custodian_networks/{id}/entities_summary | DataCustodianNetworks@showSummary |
| [**FetchDataCustodianNetworkInfo**](DataCustodianNetworksApi.md#fetchdatacustodiannetworkinfo) | **GET** /api/v2/data_custodian_networks/{id}/info | DataCustodianNetworks@showInfoSummary |
| [**FetchDataCustodianNetworks**](DataCustodianNetworksApi.md#fetchdatacustodiannetworks) | **GET** /api/v2/data_custodian_networks | DataCustodianNetworks@index |

<a id="fetchdatacustodiannetwork"></a>
# **FetchDataCustodianNetwork**
> FetchDataCustodianNetwork200Response FetchDataCustodianNetwork (int id)

DataCustodianNetworks@show

Return a single DataCustodianNetwork


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID |  |

### Return type

[**FetchDataCustodianNetwork200Response**](FetchDataCustodianNetwork200Response.md)

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

<a id="fetchdatacustodiannetworkcustodianssummary"></a>
# **FetchDataCustodianNetworkCustodiansSummary**
> FetchDataCustodianNetworkCustodiansSummary200Response FetchDataCustodianNetworkCustodiansSummary (int id)

DataCustodianNetworks@showCustodiansSummary

Return a single DataCustodianNetwork - custodians summary


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID - summary |  |

### Return type

[**FetchDataCustodianNetworkCustodiansSummary200Response**](FetchDataCustodianNetworkCustodiansSummary200Response.md)

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

<a id="fetchdatacustodiannetworkdatasetssummary"></a>
# **FetchDataCustodianNetworkDatasetsSummary**
> FetchDataCustodianNetworkDatasetsSummary200Response FetchDataCustodianNetworkDatasetsSummary (int id)

DataCustodianNetworks@showDatasetsSummary

Return a single DataCustodianNetwork - summary of datasets


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID - summary |  |

### Return type

[**FetchDataCustodianNetworkDatasetsSummary200Response**](FetchDataCustodianNetworkDatasetsSummary200Response.md)

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

<a id="fetchdatacustodiannetworkentitiessummary"></a>
# **FetchDataCustodianNetworkEntitiesSummary**
> FetchDataCustodianNetworkEntitiesSummary200Response FetchDataCustodianNetworkEntitiesSummary (int id)

DataCustodianNetworks@showSummary

Return a single DataCustodianNetwork - summary of entities


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID - summary |  |

### Return type

[**FetchDataCustodianNetworkEntitiesSummary200Response**](FetchDataCustodianNetworkEntitiesSummary200Response.md)

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

<a id="fetchdatacustodiannetworkinfo"></a>
# **FetchDataCustodianNetworkInfo**
> FetchDataCustodianNetworkInfo200Response FetchDataCustodianNetworkInfo (int id)

DataCustodianNetworks@showInfoSummary

Return a single DataCustodianNetwork - basic information


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID - summary |  |

### Return type

[**FetchDataCustodianNetworkInfo200Response**](FetchDataCustodianNetworkInfo200Response.md)

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

<a id="fetchdatacustodiannetworks"></a>
# **FetchDataCustodianNetworks**
> FetchDataCustodianNetworks200Response FetchDataCustodianNetworks (int perPage = null)

DataCustodianNetworks@index

Returns a list of DataCustodianNetworks enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | per page | [optional]  |

### Return type

[**FetchDataCustodianNetworks200Response**](FetchDataCustodianNetworks200Response.md)

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

