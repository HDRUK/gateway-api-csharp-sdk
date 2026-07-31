# GatewayApiSdk.Api.DataCustodianNetworksApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Abbd5469b6946b3822b4d156b522b03b**](DataCustodianNetworksApi.md#abbd5469b6946b3822b4d156b522b03b) | **POST** /api/v2/data_custodian_networks | DataCustodianNetworks@store |
| [**B42015102cb75735f63c91ed0c89aadc**](DataCustodianNetworksApi.md#b42015102cb75735f63c91ed0c89aadc) | **GET** /api/v2/data_custodian_networks/{id}/entities_summary | DataCustodianNetworks@showSummary |
| [**C7827b344f35440af530383c74573c6f**](DataCustodianNetworksApi.md#c7827b344f35440af530383c74573c6f) | **GET** /api/v2/data_custodian_networks/{id} | DataCustodianNetworks@show |
| [**Call0a51cc2388e3015851122c32c548b07e**](DataCustodianNetworksApi.md#call0a51cc2388e3015851122c32c548b07e) | **PATCH** /api/v2/data_custodian_networks/{id} | DataCustodianNetworks@edit |
| [**Call3b69b09a466561df872e104a19a2ad65**](DataCustodianNetworksApi.md#call3b69b09a466561df872e104a19a2ad65) | **GET** /api/v2/data_custodian_networks/{id}/datasets_summary | DataCustodianNetworks@showDatasetsSummary |
| [**Call5e9eca031c07d46c2fa4007e916bc5e1**](DataCustodianNetworksApi.md#call5e9eca031c07d46c2fa4007e916bc5e1) | **DELETE** /api/v2/data_custodian_networks/{id} | DataCustodianNetworks@destroy |
| [**Call71e5fbca2b5aa8a0160d621feb662ecb**](DataCustodianNetworksApi.md#call71e5fbca2b5aa8a0160d621feb662ecb) | **GET** /api/v2/data_custodian_networks | DataCustodianNetworks@index |
| [**Call9ce0c491d34067e8cf15eb9e9b5ec147**](DataCustodianNetworksApi.md#call9ce0c491d34067e8cf15eb9e9b5ec147) | **GET** /api/v2/data_custodian_networks/{id}/info | DataCustodianNetworks@showInfoSummary |
| [**Ced8add57941554cde6a5fc53f6555e5**](DataCustodianNetworksApi.md#ced8add57941554cde6a5fc53f6555e5) | **GET** /api/v2/data_custodian_networks/{id}/custodians_summary | DataCustodianNetworks@showCustodiansSummary |
| [**Ddc2f5ebf51037175006c6017e20d358**](DataCustodianNetworksApi.md#ddc2f5ebf51037175006c6017e20d358) | **PUT** /api/v2/data_custodian_networks/{id} | DataCustodianNetworks@update |

<a id="abbd5469b6946b3822b4d156b522b03b"></a>
# **Abbd5469b6946b3822b4d156b522b03b**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Abbd5469b6946b3822b4d156b522b03b (Model02ada355a680c816624e98ae028dc8b6Request model02ada355a680c816624e98ae028dc8b6Request)

DataCustodianNetworks@store

Creates a new DataCustodianNetwork


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model02ada355a680c816624e98ae028dc8b6Request** | [**Model02ada355a680c816624e98ae028dc8b6Request**](Model02ada355a680c816624e98ae028dc8b6Request.md) | DataCustodianNetwork definition |  |

### Return type

[**Dd76b8d73b7ea8b4951f03d7c0904c92200Response**](Dd76b8d73b7ea8b4951f03d7c0904c92200Response.md)

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

<a id="b42015102cb75735f63c91ed0c89aadc"></a>
# **B42015102cb75735f63c91ed0c89aadc**
> B42015102cb75735f63c91ed0c89aadc200Response B42015102cb75735f63c91ed0c89aadc (int id)

DataCustodianNetworks@showSummary

Return a single DataCustodianNetwork - summary of entities


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID - summary |  |

### Return type

[**B42015102cb75735f63c91ed0c89aadc200Response**](B42015102cb75735f63c91ed0c89aadc200Response.md)

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

<a id="c7827b344f35440af530383c74573c6f"></a>
# **C7827b344f35440af530383c74573c6f**
> C7827b344f35440af530383c74573c6f200Response C7827b344f35440af530383c74573c6f (int id)

DataCustodianNetworks@show

Return a single DataCustodianNetwork


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID |  |

### Return type

[**C7827b344f35440af530383c74573c6f200Response**](C7827b344f35440af530383c74573c6f200Response.md)

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

<a id="call0a51cc2388e3015851122c32c548b07e"></a>
# **Call0a51cc2388e3015851122c32c548b07e**
> Ddc2f5ebf51037175006c6017e20d358200Response Call0a51cc2388e3015851122c32c548b07e (int id, Model81b552b8803870790579d840279ce8a3Request model81b552b8803870790579d840279ce8a3Request)

DataCustodianNetworks@edit

Edit a DataCustodianNetwork


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID |  |
| **model81b552b8803870790579d840279ce8a3Request** | [**Model81b552b8803870790579d840279ce8a3Request**](Model81b552b8803870790579d840279ce8a3Request.md) | DataCustodianNetwork definition |  |

### Return type

[**Ddc2f5ebf51037175006c6017e20d358200Response**](Ddc2f5ebf51037175006c6017e20d358200Response.md)

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

<a id="call3b69b09a466561df872e104a19a2ad65"></a>
# **Call3b69b09a466561df872e104a19a2ad65**
> Model3b69b09a466561df872e104a19a2ad65200Response Call3b69b09a466561df872e104a19a2ad65 (int id)

DataCustodianNetworks@showDatasetsSummary

Return a single DataCustodianNetwork - summary of datasets


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID - summary |  |

### Return type

[**Model3b69b09a466561df872e104a19a2ad65200Response**](Model3b69b09a466561df872e104a19a2ad65200Response.md)

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

<a id="call5e9eca031c07d46c2fa4007e916bc5e1"></a>
# **Call5e9eca031c07d46c2fa4007e916bc5e1**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call5e9eca031c07d46c2fa4007e916bc5e1 (int id)

DataCustodianNetworks@destroy

Delete a DataCustodianNetwork


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID |  |

### Return type

[**C29b5b3424f7317b69b4bda048ccfafb200Response**](C29b5b3424f7317b69b4bda048ccfafb200Response.md)

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

<a id="call71e5fbca2b5aa8a0160d621feb662ecb"></a>
# **Call71e5fbca2b5aa8a0160d621feb662ecb**
> Model71e5fbca2b5aa8a0160d621feb662ecb200Response Call71e5fbca2b5aa8a0160d621feb662ecb (int perPage = null)

DataCustodianNetworks@index

Returns a list of DataCustodianNetworks enabled on the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **perPage** | **int** | per page | [optional]  |

### Return type

[**Model71e5fbca2b5aa8a0160d621feb662ecb200Response**](Model71e5fbca2b5aa8a0160d621feb662ecb200Response.md)

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

<a id="call9ce0c491d34067e8cf15eb9e9b5ec147"></a>
# **Call9ce0c491d34067e8cf15eb9e9b5ec147**
> Model9ce0c491d34067e8cf15eb9e9b5ec147200Response Call9ce0c491d34067e8cf15eb9e9b5ec147 (int id)

DataCustodianNetworks@showInfoSummary

Return a single DataCustodianNetwork - basic information


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID - summary |  |

### Return type

[**Model9ce0c491d34067e8cf15eb9e9b5ec147200Response**](Model9ce0c491d34067e8cf15eb9e9b5ec147200Response.md)

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

<a id="ced8add57941554cde6a5fc53f6555e5"></a>
# **Ced8add57941554cde6a5fc53f6555e5**
> Ced8add57941554cde6a5fc53f6555e5200Response Ced8add57941554cde6a5fc53f6555e5 (int id)

DataCustodianNetworks@showCustodiansSummary

Return a single DataCustodianNetwork - custodians summary


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetwork ID - summary |  |

### Return type

[**Ced8add57941554cde6a5fc53f6555e5200Response**](Ced8add57941554cde6a5fc53f6555e5200Response.md)

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

<a id="ddc2f5ebf51037175006c6017e20d358"></a>
# **Ddc2f5ebf51037175006c6017e20d358**
> Ddc2f5ebf51037175006c6017e20d358200Response Ddc2f5ebf51037175006c6017e20d358 (int id, C5bb5300d6a46cc5b1b6a3bb1c3fa869Request c5bb5300d6a46cc5b1b6a3bb1c3fa869Request)

DataCustodianNetworks@update

Update a DataCustodianNetwork


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DataCustodianNetworks ID |  |
| **c5bb5300d6a46cc5b1b6a3bb1c3fa869Request** | [**C5bb5300d6a46cc5b1b6a3bb1c3fa869Request**](C5bb5300d6a46cc5b1b6a3bb1c3fa869Request.md) | DataCustodianNetwork definition |  |

### Return type

[**Ddc2f5ebf51037175006c6017e20d358200Response**](Ddc2f5ebf51037175006c6017e20d358200Response.md)

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

