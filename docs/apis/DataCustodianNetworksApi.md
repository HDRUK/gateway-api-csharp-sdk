# GatewayApiSdk.Api.DataCustodianNetworksApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateDataCustodianNetwork**](DataCustodianNetworksApi.md#createdatacustodiannetwork) | **POST** /api/v2/data_custodian_networks | DataCustodianNetworks@store |
| [**DeleteDataCustodianNetwork**](DataCustodianNetworksApi.md#deletedatacustodiannetwork) | **DELETE** /api/v2/data_custodian_networks/{id} | DataCustodianNetworks@destroy |
| [**EditDataCustodianNetwork**](DataCustodianNetworksApi.md#editdatacustodiannetwork) | **PATCH** /api/v2/data_custodian_networks/{id} | DataCustodianNetworks@edit |
| [**FetchDataCustodianNetwork**](DataCustodianNetworksApi.md#fetchdatacustodiannetwork) | **GET** /api/v2/data_custodian_networks/{id} | DataCustodianNetworks@show |
| [**FetchDataCustodianNetworkCustodiansSummary**](DataCustodianNetworksApi.md#fetchdatacustodiannetworkcustodianssummary) | **GET** /api/v2/data_custodian_networks/{id}/custodians_summary | DataCustodianNetworks@showCustodiansSummary |
| [**FetchDataCustodianNetworkDatasetsSummary**](DataCustodianNetworksApi.md#fetchdatacustodiannetworkdatasetssummary) | **GET** /api/v2/data_custodian_networks/{id}/datasets_summary | DataCustodianNetworks@showDatasetsSummary |
| [**FetchDataCustodianNetworkEntitiesSummary**](DataCustodianNetworksApi.md#fetchdatacustodiannetworkentitiessummary) | **GET** /api/v2/data_custodian_networks/{id}/entities_summary | DataCustodianNetworks@showSummary |
| [**FetchDataCustodianNetworkInfo**](DataCustodianNetworksApi.md#fetchdatacustodiannetworkinfo) | **GET** /api/v2/data_custodian_networks/{id}/info | DataCustodianNetworks@showInfoSummary |
| [**FetchDataCustodianNetworks**](DataCustodianNetworksApi.md#fetchdatacustodiannetworks) | **GET** /api/v2/data_custodian_networks | DataCustodianNetworks@index |
| [**UpdateDataCustodianNetwork**](DataCustodianNetworksApi.md#updatedatacustodiannetwork) | **PUT** /api/v2/data_custodian_networks/{id} | DataCustodianNetworks@update |

<a id="createdatacustodiannetwork"></a>
# **CreateDataCustodianNetwork**
> CreateDarIntegration201Response CreateDataCustodianNetwork (CreateDataProviderCollRequest createDataProviderCollRequest)

DataCustodianNetworks@store

Creates a new DataCustodianNetwork


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createDataProviderCollRequest** | [**CreateDataProviderCollRequest**](CreateDataProviderCollRequest.md) | DataCustodianNetwork definition |  |

### Return type

[**CreateDarIntegration201Response**](CreateDarIntegration201Response.md)

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

<a id="deletedatacustodiannetwork"></a>
# **DeleteDataCustodianNetwork**
> DeleteApplications200Response DeleteDataCustodianNetwork (int id)

DataCustodianNetworks@destroy

Delete a DataCustodianNetwork


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID |  |

### Return type

[**DeleteApplications200Response**](DeleteApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **404** | Not found response |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="editdatacustodiannetwork"></a>
# **EditDataCustodianNetwork**
> UpdateDataCustodianNetwork200Response EditDataCustodianNetwork (int id, EditDataProviderCollRequest editDataProviderCollRequest)

DataCustodianNetworks@edit

Edit a DataCustodianNetwork


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID |  |
| **editDataProviderCollRequest** | [**EditDataProviderCollRequest**](EditDataProviderCollRequest.md) | DataCustodianNetwork definition |  |

### Return type

[**UpdateDataCustodianNetwork200Response**](UpdateDataCustodianNetwork200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **404** | Not found response |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

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

<a id="updatedatacustodiannetwork"></a>
# **UpdateDataCustodianNetwork**
> UpdateDataCustodianNetwork200Response UpdateDataCustodianNetwork (int id, UpdateDataProviderCollRequest updateDataProviderCollRequest)

DataCustodianNetworks@update

Update a DataCustodianNetwork


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetworks ID |  |
| **updateDataProviderCollRequest** | [**UpdateDataProviderCollRequest**](UpdateDataProviderCollRequest.md) | DataCustodianNetwork definition |  |

### Return type

[**UpdateDataCustodianNetwork200Response**](UpdateDataCustodianNetwork200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **404** | Not found response |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

