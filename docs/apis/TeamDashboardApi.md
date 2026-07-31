# GatewayApiSdk.Api.TeamDashboardApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**FetchCollectionsViewsV3**](TeamDashboardApi.md#fetchcollectionsviewsv3) | **GET** /api/v3/teams/{id}/dashboard/collections/views | TeamDashboardController@collectionViews |
| [**FetchDarApplicationsApplicationTimelineV3**](TeamDashboardApi.md#fetchdarapplicationsapplicationtimelinev3) | **GET** /api/v3/teams/{id}/dar/dashboard/timeline | DataAccessDashboardController@getApplicationTimeline |
| [**FetchDarApplicationsAverageTimeToApprovalV3**](TeamDashboardApi.md#fetchdarapplicationsaveragetimetoapprovalv3) | **GET** /api/v3/teams/{id}/dar/dashboard/average-time | DataAccessDashboardController@getAverageTimeToApproval |
| [**FetchDarApplicationsCurrentStatusV3**](TeamDashboardApi.md#fetchdarapplicationscurrentstatusv3) | **GET** /api/v3/teams/{id}/dar/dashboard/status | DataAccessDashboardController@getApplicationStatus |
| [**FetchDarApplicationsDashboardExportCsvV3**](TeamDashboardApi.md#fetchdarapplicationsdashboardexportcsvv3) | **GET** /api/v3/teams/{id}/dar/dashboard/export/csv | DataAccessDashboardController@exportDashboardCsv |
| [**FetchDarApplicationsDashboardRequiredActionsExportCsvV3**](TeamDashboardApi.md#fetchdarapplicationsdashboardrequiredactionsexportcsvv3) | **GET** /api/v3/teams/{id}/dar/dashboard/required-actions/export/csv | DataAccessDashboardController@exportRequiredActionsCsv |
| [**FetchDarApplicationsDashboardTimelineExportCsvV3**](TeamDashboardApi.md#fetchdarapplicationsdashboardtimelineexportcsvv3) | **GET** /api/v3/teams/{id}/dar/dashboard/timeline/export/csv | DataAccessDashboardController@exportDashboardTimelineCsv |
| [**FetchDarApplicationsRequiredActionsV3**](TeamDashboardApi.md#fetchdarapplicationsrequiredactionsv3) | **GET** /api/v3/teams/{id}/dar/dashboard/required-actions | DataAccessDashboardController@getRequiredActions |
| [**FetchDarMyApplicationsV3**](TeamDashboardApi.md#fetchdarmyapplicationsv3) | **GET** /api/v3/teams/{id}/dar/dashboard/count | DataAccessDashboardController@getMyApplications |
| [**FetchDashboardDownloadCsvV3**](TeamDashboardApi.md#fetchdashboarddownloadcsvv3) | **GET** /api/v3/teams/{id}/dashboard/download/csv | TeamDashboardController@downloadCsv |
| [**FetchDataCustodiansViewsV3**](TeamDashboardApi.md#fetchdatacustodiansviewsv3) | **GET** /api/v3/teams/{id}/dashboard/datacustodians/views | TeamDashboardController@datacustodianViews |
| [**FetchDatasetViews360V3**](TeamDashboardApi.md#fetchdatasetviews360v3) | **GET** /api/v3/teams/{id}/dashboard/datasets/views/360 | TeamDashboardController@datasetViews360 |
| [**FetchDatasetViewsTopV3**](TeamDashboardApi.md#fetchdatasetviewstopv3) | **GET** /api/v3/teams/{id}/dashboard/datasets/views/top | TeamDashboardController@datasetViewsTop |
| [**FetchEntitiesCountV3**](TeamDashboardApi.md#fetchentitiescountv3) | **GET** /api/v3/teams/{id}/dashboard/{entity}/count | TeamDashboardController@entityCount |

<a id="fetchcollectionsviewsv3"></a>
# **FetchCollectionsViewsV3**
> FetchCollectionsViewsV3200Response FetchCollectionsViewsV3 (int id, DateOnly startDate = null, DateOnly endDate = null)

TeamDashboardController@collectionViews

Get count of a collection views for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |
| **startDate** | **DateOnly** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | [optional]  |
| **endDate** | **DateOnly** | End date for the reporting interval (Y-m-d). Defaults to today. | [optional]  |

### Return type

[**FetchCollectionsViewsV3200Response**](FetchCollectionsViewsV3200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdarapplicationsapplicationtimelinev3"></a>
# **FetchDarApplicationsApplicationTimelineV3**
> CreateWidget201Response FetchDarApplicationsApplicationTimelineV3 (int id, DateOnly startDate = null, DateOnly endDate = null)

DataAccessDashboardController@getApplicationTimeline

Get Dar applications timeline for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |
| **startDate** | **DateOnly** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | [optional]  |
| **endDate** | **DateOnly** | End date for the reporting interval (Y-m-d). Defaults to today. | [optional]  |

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdarapplicationsaveragetimetoapprovalv3"></a>
# **FetchDarApplicationsAverageTimeToApprovalV3**
> CreateWidget201Response FetchDarApplicationsAverageTimeToApprovalV3 (int id, DateOnly startDate = null, DateOnly endDate = null)

DataAccessDashboardController@getAverageTimeToApproval

Get Dar applications average time to approval for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |
| **startDate** | **DateOnly** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | [optional]  |
| **endDate** | **DateOnly** | End date for the reporting interval (Y-m-d). Defaults to today. | [optional]  |

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdarapplicationscurrentstatusv3"></a>
# **FetchDarApplicationsCurrentStatusV3**
> CreateWidget201Response FetchDarApplicationsCurrentStatusV3 (int id, DateOnly startDate = null, DateOnly endDate = null)

DataAccessDashboardController@getApplicationStatus

Get Dar applications current status for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |
| **startDate** | **DateOnly** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | [optional]  |
| **endDate** | **DateOnly** | End date for the reporting interval (Y-m-d). Defaults to today. | [optional]  |

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdarapplicationsdashboardexportcsvv3"></a>
# **FetchDarApplicationsDashboardExportCsvV3**
> CreateWidget201Response FetchDarApplicationsDashboardExportCsvV3 (int id, DateOnly startDate = null, DateOnly endDate = null)

DataAccessDashboardController@exportDashboardCsv

Get Dar applications dashboard export csv for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |
| **startDate** | **DateOnly** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | [optional]  |
| **endDate** | **DateOnly** | End date for the reporting interval (Y-m-d). Defaults to today. | [optional]  |

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdarapplicationsdashboardrequiredactionsexportcsvv3"></a>
# **FetchDarApplicationsDashboardRequiredActionsExportCsvV3**
> CreateWidget201Response FetchDarApplicationsDashboardRequiredActionsExportCsvV3 (int id)

DataAccessDashboardController@exportRequiredActionsCsv

Get Dar applications dashboard timeline export csv for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdarapplicationsdashboardtimelineexportcsvv3"></a>
# **FetchDarApplicationsDashboardTimelineExportCsvV3**
> CreateWidget201Response FetchDarApplicationsDashboardTimelineExportCsvV3 (int id, DateOnly startDate = null, DateOnly endDate = null)

DataAccessDashboardController@exportDashboardTimelineCsv

Get Dar applications dashboard timeline export csv for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |
| **startDate** | **DateOnly** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | [optional]  |
| **endDate** | **DateOnly** | End date for the reporting interval (Y-m-d). Defaults to today. | [optional]  |

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdarapplicationsrequiredactionsv3"></a>
# **FetchDarApplicationsRequiredActionsV3**
> CreateWidget201Response FetchDarApplicationsRequiredActionsV3 (int id, DateOnly startDate = null, DateOnly endDate = null)

DataAccessDashboardController@getRequiredActions

Get Dar applications required actions for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |
| **startDate** | **DateOnly** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | [optional]  |
| **endDate** | **DateOnly** | End date for the reporting interval (Y-m-d). Defaults to today. | [optional]  |

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdarmyapplicationsv3"></a>
# **FetchDarMyApplicationsV3**
> CreateWidget201Response FetchDarMyApplicationsV3 (int id, DateOnly startDate = null, DateOnly endDate = null)

DataAccessDashboardController@getMyApplications

Get Dar applications for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |
| **startDate** | **DateOnly** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | [optional]  |
| **endDate** | **DateOnly** | End date for the reporting interval (Y-m-d). Defaults to today. | [optional]  |

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdashboarddownloadcsvv3"></a>
# **FetchDashboardDownloadCsvV3**
> System.IO.Stream FetchDashboardDownloadCsvV3 (int id, DateOnly startDate = null, DateOnly endDate = null)

TeamDashboardController@downloadCsv

Download dashboard data custodian in csv format


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |
| **startDate** | **DateOnly** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | [optional]  |
| **endDate** | **DateOnly** | End date for the reporting interval (Y-m-d). Defaults to today. | [optional]  |

### Return type

**System.IO.Stream**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/csv, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | CSV file download containing dashboard metrics for the team |  -  |
| **400** | Invalid team ID |  -  |
| **500** | Invalid date interval |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdatacustodiansviewsv3"></a>
# **FetchDataCustodiansViewsV3**
> FetchCollectionsViewsV3200Response FetchDataCustodiansViewsV3 (int id, DateOnly startDate = null, DateOnly endDate = null)

TeamDashboardController@datacustodianViews

Get count of a data custodian views for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |
| **startDate** | **DateOnly** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | [optional]  |
| **endDate** | **DateOnly** | End date for the reporting interval (Y-m-d). Defaults to today. | [optional]  |

### Return type

[**FetchCollectionsViewsV3200Response**](FetchCollectionsViewsV3200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdatasetviews360v3"></a>
# **FetchDatasetViews360V3**
> FetchDatasetViews360V3200Response FetchDatasetViews360V3 (int id, DateOnly startDate = null, DateOnly endDate = null)

TeamDashboardController@datasetViews360

Get count of a datasets views 360 for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |
| **startDate** | **DateOnly** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | [optional]  |
| **endDate** | **DateOnly** | End date for the reporting interval (Y-m-d). Defaults to today. | [optional]  |

### Return type

[**FetchDatasetViews360V3200Response**](FetchDatasetViews360V3200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchdatasetviewstopv3"></a>
# **FetchDatasetViewsTopV3**
> FetchDatasetViewsTopV3200Response FetchDatasetViewsTopV3 (int id, DateOnly startDate = null, DateOnly endDate = null)

TeamDashboardController@datasetViewsTop

Get count of a datasets views top for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |
| **startDate** | **DateOnly** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | [optional]  |
| **endDate** | **DateOnly** | End date for the reporting interval (Y-m-d). Defaults to today. | [optional]  |

### Return type

[**FetchDatasetViewsTopV3200Response**](FetchDatasetViewsTopV3200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchentitiescountv3"></a>
# **FetchEntitiesCountV3**
> FetchEntitiesCountV3200Response FetchEntitiesCountV3 (int id, string entity, DateOnly startDate = null, DateOnly endDate = null)

TeamDashboardController@entityCount

Get count of a specific entity for a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Team ID |  |
| **entity** | **string** | Entity type to count |  |
| **startDate** | **DateOnly** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | [optional]  |
| **endDate** | **DateOnly** | End date for the reporting interval (Y-m-d). Defaults to today. | [optional]  |

### Return type

[**FetchEntitiesCountV3200Response**](FetchEntitiesCountV3200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

