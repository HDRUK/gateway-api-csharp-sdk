# GatewayApiSdk.Api.DatasetsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call1c45c3c6908e92d680ce50910d6d4061**](DatasetsApi.md#call1c45c3c6908e92d680ce50910d6d4061) | **POST** /api/v1/datasets/admin_ctrl/trigger/term_extraction | Trigger Term Extraction for Datasets |
| [**Call7f39b24417648f048a9457326619439c**](DatasetsApi.md#call7f39b24417648f048a9457326619439c) | **POST** /api/v1/datasets/admin_ctrl/trigger/linkage_extraction | Trigger Term Extraction for Datasets |
| [**CountTeamUniqueFieldsDatasetsV2**](DatasetsApi.md#countteamuniquefieldsdatasetsv2) | **GET** /api/v2/teams/{teamId}/datasets/count/{field} | TeamDatasetController@count |
| [**CountUniqueFields**](DatasetsApi.md#countuniquefields) | **GET** /api/v1/datasets/count/{field} | DatasetController@count |
| [**CreateDatasets**](DatasetsApi.md#createdatasets) | **POST** /api/v1/datasets | DatasetController@store |
| [**CreateDatasetsIntegrations**](DatasetsApi.md#createdatasetsintegrations) | **POST** /api/v1/integrations/datasets | IntegrationDatasetController@store |
| [**CreateDatasetsV2**](DatasetsApi.md#createdatasetsv2) | **POST** /api/v2/datasets | DatasetController@store |
| [**CreateTeamDatasetsV2**](DatasetsApi.md#createteamdatasetsv2) | **POST** /api/v2/teams/{teamId}/datasets | TeamDatasetController@store |
| [**DeleteDatasets**](DatasetsApi.md#deletedatasets) | **DELETE** /api/v1/datasets/{id} | DatasetController@destroy |
| [**DeleteDatasetsIntegrations**](DatasetsApi.md#deletedatasetsintegrations) | **DELETE** /api/v1/integrations/datasets/{id} | IntegrationDatasetController@destroy |
| [**DeleteDatasetsV2**](DatasetsApi.md#deletedatasetsv2) | **DELETE** /api/v2/datasets/{id} | Delete a dataset |
| [**DeleteTeamDatasetsV2**](DatasetsApi.md#deleteteamdatasetsv2) | **DELETE** /api/v2/teams/{teamId}/datasets/{id} | TeamDatasetController@destroy |
| [**ExportDatasetMetadata**](DatasetsApi.md#exportdatasetmetadata) | **GET** /api/v1/datasets/export_metadata/{id} | DatasetController@exportMetadata |
| [**ExportDatasets**](DatasetsApi.md#exportdatasets) | **GET** /api/v1/datasets/export | DatasetController@export |
| [**ExportDur**](DatasetsApi.md#exportdur) | **GET** /api/v1/dur/export | DurController@export |
| [**ExportMockDataset**](DatasetsApi.md#exportmockdataset) | **GET** /api/v1/datasets/export/mock | DatasetController@exportMock |
| [**ExportMockDatasetV2**](DatasetsApi.md#exportmockdatasetv2) | **GET** /api/v2/datasets/export/mock | DatasetController@exportMock |
| [**FetchAllDatasets**](DatasetsApi.md#fetchalldatasets) | **GET** /api/v1/datasets | DatasetController@index |
| [**FetchAllDatasetsIntegrations**](DatasetsApi.md#fetchalldatasetsintegrations) | **GET** /api/v1/integrations/datasets | IntegrationDatasetController@index |
| [**FetchAllDatasetsV2**](DatasetsApi.md#fetchalldatasetsv2) | **GET** /api/v2/datasets | DatasetController@index |
| [**FetchDatasets**](DatasetsApi.md#fetchdatasets) | **GET** /api/v1/datasets/{id} | DatasetController@show |
| [**FetchDatasetsIntegrations**](DatasetsApi.md#fetchdatasetsintegrations) | **GET** /api/v1/integrations/datasets/{id} | IntegrationDatasetController@show |
| [**FetchDatasetsV2**](DatasetsApi.md#fetchdatasetsv2) | **GET** /api/v2/datasets/{id} | DatasetController@showActive |
| [**FetchTeamDatasetsStatus**](DatasetsApi.md#fetchteamdatasetsstatus) | **GET** /api/v2/teams/{teamId}/datasets/status/{status} | TeamDatasetController@indexStatus |
| [**FetchTeamDatasetsV2**](DatasetsApi.md#fetchteamdatasetsv2) | **GET** /api/v2/teams/{teamId}/datasets/{id} | TeamDatasetController@show |
| [**PatchDatasets**](DatasetsApi.md#patchdatasets) | **PATCH** /api/v1/datasets/{id} | DatasetController@edit |
| [**PatchDatasetsIntegrations**](DatasetsApi.md#patchdatasetsintegrations) | **PATCH** /api/v1/integrations/datasets/{id} | IntegrationDatasetController@edit |
| [**PatchDatasetsV2**](DatasetsApi.md#patchdatasetsv2) | **PATCH** /api/v2/datasets/{id} | DatasetController@edit |
| [**PatchTeamDatasetsV2**](DatasetsApi.md#patchteamdatasetsv2) | **PATCH** /api/v2/teams/{teamId}/datasets/{id} | TeamDatasetController@edit |
| [**UpdateDatasets**](DatasetsApi.md#updatedatasets) | **PUT** /api/v1/datasets/{id} | DatasetController@update |
| [**UpdateDatasetsIntegrations**](DatasetsApi.md#updatedatasetsintegrations) | **PUT** /api/v1/integrations/datasets/{id} | IntegrationDatasetController@update |
| [**UpdateDatasetsV2**](DatasetsApi.md#updatedatasetsv2) | **PUT** /api/v2/datasets/{id} | DatasetController@update |
| [**UpdateTeamDatasetsV2**](DatasetsApi.md#updateteamdatasetsv2) | **PUT** /api/v2/teams/{teamId}/datasets/{id} | TeamDatasetController@update |

<a id="call1c45c3c6908e92d680ce50910d6d4061"></a>
# **Call1c45c3c6908e92d680ce50910d6d4061**
> Model1c45c3c6908e92d680ce50910d6d4061200Response Call1c45c3c6908e92d680ce50910d6d4061 (string authorization, string role, Model1c45c3c6908e92d680ce50910d6d4061Request model1c45c3c6908e92d680ce50910d6d4061Request)

Trigger Term Extraction for Datasets

Triggers the term extraction job for datasets within a specified range and controls whether data is partially indexed in Elasticsearch.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **authorization** | **string** | JWT token for authorization in the format &#39;Bearer {token}&#39; |  |
| **role** | **string** | Role required to access this endpoint, e.g., &#39;hdruk.superadmin&#39; |  |
| **model1c45c3c6908e92d680ce50910d6d4061Request** | [**Model1c45c3c6908e92d680ce50910d6d4061Request**](Model1c45c3c6908e92d680ce50910d6d4061Request.md) |  |  |

### Return type

[**Model1c45c3c6908e92d680ce50910d6d4061200Response**](Model1c45c3c6908e92d680ce50910d6d4061200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Term extraction triggered successfully |  -  |
| **500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call7f39b24417648f048a9457326619439c"></a>
# **Call7f39b24417648f048a9457326619439c**
> Model7f39b24417648f048a9457326619439c200Response Call7f39b24417648f048a9457326619439c (string authorization, Model7f39b24417648f048a9457326619439cRequest model7f39b24417648f048a9457326619439cRequest)

Trigger Term Extraction for Datasets

Triggers the term extraction job for datasets within a specified range and controls whether data is partially indexed in Elasticsearch.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **authorization** | **string** | JWT token for authorization in the format &#39;Bearer {token}&#39; |  |
| **model7f39b24417648f048a9457326619439cRequest** | [**Model7f39b24417648f048a9457326619439cRequest**](Model7f39b24417648f048a9457326619439cRequest.md) |  |  |

### Return type

[**Model7f39b24417648f048a9457326619439c200Response**](Model7f39b24417648f048a9457326619439c200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Linkage extraction triggered successfully |  -  |
| **500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="countteamuniquefieldsdatasetsv2"></a>
# **CountTeamUniqueFieldsDatasetsV2**
> CountUniqueFieldsCollections200Response CountTeamUniqueFieldsDatasetsV2 (int teamId, string field)

TeamDatasetController@count

Get team counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **field** | **string** | name of the field to perform a count on |  |

### Return type

[**CountUniqueFieldsCollections200Response**](CountUniqueFieldsCollections200Response.md)

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

<a id="countuniquefields"></a>
# **CountUniqueFields**
> CountUniqueFieldsCollections200Response CountUniqueFields (string field, int teamId)

DatasetController@count

Get Counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **field** | **string** | name of the field to perform a count on |  |
| **teamId** | **int** | team id |  |

### Return type

[**CountUniqueFieldsCollections200Response**](CountUniqueFieldsCollections200Response.md)

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

<a id="createdatasets"></a>
# **CreateDatasets**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateDatasets (CreateDatasetsRequest createDatasetsRequest)

DatasetController@store

Create a new dataset


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createDatasetsRequest** | [**CreateDatasetsRequest**](CreateDatasetsRequest.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="createdatasetsintegrations"></a>
# **CreateDatasetsIntegrations**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateDatasetsIntegrations (DatasetsTestRequest datasetsTestRequest, string inputSchema = null, string inputVersion = null)

IntegrationDatasetController@store

Create a new dataset


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **datasetsTestRequest** | [**DatasetsTestRequest**](DatasetsTestRequest.md) | Pass user credentials |  |
| **inputSchema** | **string** | Input schema model. | [optional]  |
| **inputVersion** | **string** | Input schema version. | [optional]  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="createdatasetsv2"></a>
# **CreateDatasetsV2**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateDatasetsV2 (CreateDatasetsV2Request createDatasetsV2Request)

DatasetController@store

Create a new dataset


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createDatasetsV2Request** | [**CreateDatasetsV2Request**](CreateDatasetsV2Request.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="createteamdatasetsv2"></a>
# **CreateTeamDatasetsV2**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateTeamDatasetsV2 (int teamId, CreateTeamDatasetsV2Request createTeamDatasetsV2Request)

TeamDatasetController@store

Create a new dataset for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **createTeamDatasetsV2Request** | [**CreateTeamDatasetsV2Request**](CreateTeamDatasetsV2Request.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletedatasets"></a>
# **DeleteDatasets**
> C29b5b3424f7317b69b4bda048ccfafb200Response DeleteDatasets (int id)

DatasetController@destroy

Delete a dataset


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dataset id |  |

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

<a id="deletedatasetsintegrations"></a>
# **DeleteDatasetsIntegrations**
> C29b5b3424f7317b69b4bda048ccfafb200Response DeleteDatasetsIntegrations (int id)

IntegrationDatasetController@destroy

Delete a dataset


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dataset id |  |

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

<a id="deletedatasetsv2"></a>
# **DeleteDatasetsV2**
> C29b5b3424f7317b69b4bda048ccfafb200Response DeleteDatasetsV2 (int id)

Delete a dataset

Delete a dataset


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dataset id |  |

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

<a id="deleteteamdatasetsv2"></a>
# **DeleteTeamDatasetsV2**
> C29b5b3424f7317b69b4bda048ccfafb200Response DeleteTeamDatasetsV2 (int teamId, int id)

TeamDatasetController@destroy

Delete a team's dataset


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | dataset id |  |

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

<a id="exportdatasetmetadata"></a>
# **ExportDatasetMetadata**
> string ExportDatasetMetadata (int id, string downloadType)

DatasetController@exportMetadata

Export Structural Metadata CSV of a single dataset


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dataset id |  |
| **downloadType** | **string** | download type |  |

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/csv, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | CSV file |  -  |
| **400** | Bad request |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="exportdatasets"></a>
# **ExportDatasets**
> string ExportDatasets (int teamId, int datasetId = null)

DatasetController@export

Export CSV Of All Datasets


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **datasetId** | **int** | dataset id | [optional]  |

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/csv, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | CSV file |  -  |
| **401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="exportdur"></a>
# **ExportDur**
> string ExportDur (int teamId, int durId = null)

DurController@export

Export CSV Of All Dur's


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **durId** | **int** | dur id | [optional]  |

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/csv, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | CSV file |  -  |
| **401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="exportmockdataset"></a>
# **ExportMockDataset**
> string ExportMockDataset (string type)

DatasetController@exportMock

Export Mock


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **type** | **string** | type export |  |

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/csv, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | CSV file |  -  |
| **401** | Unauthorized |  -  |
| **404** | File Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="exportmockdatasetv2"></a>
# **ExportMockDatasetV2**
> string ExportMockDatasetV2 (string type)

DatasetController@exportMock

Export Mock


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **type** | **string** |  |  |

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/csv, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | CSV file |  -  |
| **401** | Unauthorized |  -  |
| **404** | File Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchalldatasets"></a>
# **FetchAllDatasets**
> FetchAllDatasets200Response FetchAllDatasets (int teamId, string pid = null, string sort = null, string title = null, string status = null)

DatasetController@index

Get All Datasets


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **pid** | **string** | get based on a pid | [optional]  |
| **sort** | **string** | Field and direction (colon separated) to sort by (default: &#39;created:desc&#39;) ... &lt;br/&gt; &lt;br/&gt;         - ?sort&#x3D;\\&lt;field\\&gt;:\\&lt;direction\\&gt; &lt;br/&gt;         - \\&lt;direction\\&gt; can only be &#39;asc&#39; or &#39;desc&#39;  &lt;br/&gt;         - \\&lt;field\\&gt; can only be a valid field for the dataset table that can be ordered on  &lt;br/&gt;         - \\&lt;field\\&gt; can start with the prefix &#39;metadata.&#39; so that nested values within the field &#39;metadata&#39;  &lt;br/&gt;             (represented by the GWDM JSON structure) can be used to order on.  &lt;br/&gt;  &lt;br/&gt; | [optional]  |
| **title** | **string** | Three or more characters to filter dataset titles by | [optional]  |
| **status** | **string** | Dataset status to filter by (&#39;ACTIVE&#39;, &#39;DRAFT&#39;, &#39;ARCHIVED&#39;) | [optional]  |

### Return type

[**FetchAllDatasets200Response**](FetchAllDatasets200Response.md)

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

<a id="fetchalldatasetsintegrations"></a>
# **FetchAllDatasetsIntegrations**
> FetchAllDatasets200Response FetchAllDatasetsIntegrations (int teamId, string pid = null, string sort = null, string title = null, string status = null)

IntegrationDatasetController@index

Get All Datasets


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **pid** | **string** | get based on a pid | [optional]  |
| **sort** | **string** | Field and direction (colon separated) to sort by (default: &#39;created:desc&#39;) ... &lt;br/&gt; &lt;br/&gt;         - ?sort&#x3D;\\&lt;field\\&gt;:\\&lt;direction\\&gt; &lt;br/&gt;         - \\&lt;direction\\&gt; can only be &#39;asc&#39; or &#39;desc&#39;  &lt;br/&gt;         - \\&lt;field\\&gt; can only be a valid field for the dataset table that can be ordered on  &lt;br/&gt;         - \\&lt;field\\&gt; can start with the prefix &#39;metadata.&#39; so that nested values within the field &#39;metadata&#39;  &lt;br/&gt;             (represented by the GWDM JSON structure) can be used to order on.  &lt;br/&gt;  &lt;br/&gt; | [optional]  |
| **title** | **string** | Three or more characters to filter dataset titles by | [optional]  |
| **status** | **string** | Dataset status to filter by (&#39;ACTIVE&#39;, &#39;DRAFT&#39;, &#39;ARCHIVED&#39;) | [optional]  |

### Return type

[**FetchAllDatasets200Response**](FetchAllDatasets200Response.md)

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

<a id="fetchalldatasetsv2"></a>
# **FetchAllDatasetsV2**
> FetchAllDatasets200Response FetchAllDatasetsV2 (string sort = null, string title = null, string status = null, string withMetadata = null)

DatasetController@index

Returns a list of all datasets


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **sort** | **string** | Field and direction (colon separated) to sort by (default: &#39;created:desc&#39;) ... &lt;br/&gt; &lt;br/&gt;         - ?sort&#x3D;\\&lt;field\\&gt;:\\&lt;direction\\&gt; &lt;br/&gt;         - \\&lt;direction\\&gt; can only be &#39;asc&#39; or &#39;desc&#39;  &lt;br/&gt;         - \\&lt;field\\&gt; can only be a valid field for the dataset table that can be ordered on  &lt;br/&gt;         - \\&lt;field\\&gt; can start with the prefix &#39;metadata.&#39; so that nested values within the field &#39;metadata&#39;  &lt;br/&gt;             (represented by the GWDM JSON structure) can be used to order on.  &lt;br/&gt;  &lt;br/&gt; | [optional]  |
| **title** | **string** | Three or more characters to filter dataset titles by | [optional]  |
| **status** | **string** | Dataset status to filter by (&#39;ACTIVE&#39;, &#39;DRAFT&#39;, &#39;ARCHIVED&#39;) | [optional]  |
| **withMetadata** | **string** | Boolean whether to return dataset metadata | [optional]  |

### Return type

[**FetchAllDatasets200Response**](FetchAllDatasets200Response.md)

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

<a id="fetchdatasets"></a>
# **FetchDatasets**
> FetchDatasets200Response FetchDatasets (int id, string export = null, string schemaModel = null, string schemaVersion = null)

DatasetController@show

Get dataset by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dataset id |  |
| **export** | **string** | Alternative output schema model. | [optional]  |
| **schemaModel** | **string** | Alternative output schema model. | [optional]  |
| **schemaVersion** | **string** | Alternative output schema version. | [optional]  |

### Return type

[**FetchDatasets200Response**](FetchDatasets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdatasetsintegrations"></a>
# **FetchDatasetsIntegrations**
> FetchDatasets200Response FetchDatasetsIntegrations (int id, string schemaModel = null, string schemaVersion = null)

IntegrationDatasetController@show

Get dataset by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dataset id |  |
| **schemaModel** | **string** | Alternative output schema model. | [optional]  |
| **schemaVersion** | **string** | Alternative output schema version. | [optional]  |

### Return type

[**FetchDatasets200Response**](FetchDatasets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdatasetsv2"></a>
# **FetchDatasetsV2**
> FetchDatasets200Response FetchDatasetsV2 (int id, string export = null, string schemaModel = null, string schemaVersion = null)

DatasetController@showActive

Get publicly visible dataset by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dataset id |  |
| **export** | **string** | Set to &#39;structuralMetadata&#39; to download as CSV. | [optional]  |
| **schemaModel** | **string** | Alternative output schema model. | [optional]  |
| **schemaVersion** | **string** | Alternative output schema version. | [optional]  |

### Return type

[**FetchDatasets200Response**](FetchDatasets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchteamdatasetsstatus"></a>
# **FetchTeamDatasetsStatus**
> FetchAllDatasets200Response FetchTeamDatasetsStatus (int teamId, string status, string sort = null, string withMetadata = null)

TeamDatasetController@indexStatus

Returns a list of a team's datasets with the given status


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | ID of the team to filter by |  |
| **status** | **string** | Status of the dataset (active, draft, or archived). Defaults to active if not provided. | [default to active] |
| **sort** | **string** | Field and direction (colon separated) to sort by (default: &#39;created:desc&#39;) ... &lt;br/&gt; &lt;br/&gt;         - ?sort&#x3D;\\&lt;field\\&gt;:\\&lt;direction\\&gt; &lt;br/&gt;         - \\&lt;direction\\&gt; can only be &#39;asc&#39; or &#39;desc&#39;  &lt;br/&gt;         - \\&lt;field\\&gt; can only be a valid field for the dataset table that can be ordered on  &lt;br/&gt;         - \\&lt;field\\&gt; can start with the prefix &#39;metadata.&#39; so that nested values within the field &#39;metadata&#39;  &lt;br/&gt;             (represented by the GWDM JSON structure) can be used to order on.  &lt;br/&gt;  &lt;br/&gt; | [optional]  |
| **withMetadata** | **string** | Boolean whether to return dataset metadata | [optional]  |

### Return type

[**FetchAllDatasets200Response**](FetchAllDatasets200Response.md)

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

<a id="fetchteamdatasetsv2"></a>
# **FetchTeamDatasetsV2**
> FetchDatasets200Response FetchTeamDatasetsV2 (int teamId, int id, string export = null, string schemaModel = null, string schemaVersion = null)

TeamDatasetController@show

Get dataset by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | dataset id |  |
| **export** | **string** | Alternative output schema model. | [optional]  |
| **schemaModel** | **string** | Alternative output schema model. | [optional]  |
| **schemaVersion** | **string** | Alternative output schema version. | [optional]  |

### Return type

[**FetchDatasets200Response**](FetchDatasets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **401** | Unauthorized |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="patchdatasets"></a>
# **PatchDatasets**
> C29b5b3424f7317b69b4bda048ccfafb200Response PatchDatasets (int id, string unarchive = null)

DatasetController@edit

Patch dataset by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dataset id |  |
| **unarchive** | **string** | Unarchive a dataset | [optional]  |

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
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="patchdatasetsintegrations"></a>
# **PatchDatasetsIntegrations**
> C29b5b3424f7317b69b4bda048ccfafb200Response PatchDatasetsIntegrations (int id, string unarchive = null)

IntegrationDatasetController@edit

Patch dataset by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dataset id |  |
| **unarchive** | **string** | Unarchive a dataset | [optional]  |

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
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="patchdatasetsv2"></a>
# **PatchDatasetsV2**
> C29b5b3424f7317b69b4bda048ccfafb200Response PatchDatasetsV2 (int id, PatchDatasetsV2Request patchDatasetsV2Request)

DatasetController@edit

Patch dataset by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dataset id |  |
| **patchDatasetsV2Request** | [**PatchDatasetsV2Request**](PatchDatasetsV2Request.md) |  |  |

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
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="patchteamdatasetsv2"></a>
# **PatchTeamDatasetsV2**
> C29b5b3424f7317b69b4bda048ccfafb200Response PatchTeamDatasetsV2 (int teamId, int id, PatchDatasetsV2Request patchDatasetsV2Request)

TeamDatasetController@edit

Edit a dataset owned by a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | dataset id |  |
| **patchDatasetsV2Request** | [**PatchDatasetsV2Request**](PatchDatasetsV2Request.md) | Pass user credentials |  |

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
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updatedatasets"></a>
# **UpdateDatasets**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response UpdateDatasets (int id, UpdateDatasetsRequest updateDatasetsRequest)

DatasetController@update

Update a dataset with a new dataset version


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dataset id |  |
| **updateDatasetsRequest** | [**UpdateDatasetsRequest**](UpdateDatasetsRequest.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updatedatasetsintegrations"></a>
# **UpdateDatasetsIntegrations**
> FetchDatasets200Response UpdateDatasetsIntegrations (int id, UpdateDatasetsRequest updateDatasetsRequest, string inputSchema = null, string inputVersion = null)

IntegrationDatasetController@update

Update a dataset with a new dataset version


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dataset id |  |
| **updateDatasetsRequest** | [**UpdateDatasetsRequest**](UpdateDatasetsRequest.md) | Pass user credentials |  |
| **inputSchema** | **string** | Input schema model. | [optional]  |
| **inputVersion** | **string** | Input schema version. | [optional]  |

### Return type

[**FetchDatasets200Response**](FetchDatasets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

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

<a id="updatedatasetsv2"></a>
# **UpdateDatasetsV2**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response UpdateDatasetsV2 (int id, UpdateDatasetsRequest updateDatasetsRequest)

DatasetController@update

Update a dataset with a new dataset version


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | dataset id |  |
| **updateDatasetsRequest** | [**UpdateDatasetsRequest**](UpdateDatasetsRequest.md) |  |  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updateteamdatasetsv2"></a>
# **UpdateTeamDatasetsV2**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response UpdateTeamDatasetsV2 (int teamId, int id, PatchDatasetsV2Request patchDatasetsV2Request)

TeamDatasetController@update

Update a team dataset with a new dataset version


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | team id |  |
| **id** | **int** | dataset id |  |
| **patchDatasetsV2Request** | [**PatchDatasetsV2Request**](PatchDatasetsV2Request.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

