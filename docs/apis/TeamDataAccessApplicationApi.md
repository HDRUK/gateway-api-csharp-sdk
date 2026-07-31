# GatewayApiSdk.Api.TeamDataAccessApplicationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call0dabe0dfdf4eebd0c76560fd691c6472**](TeamDataAccessApplicationApi.md#call0dabe0dfdf4eebd0c76560fd691c6472) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/showHeader | TeamDataAccessApplicationController@showHeader |
| [**Call0ff8ad69b213abf8d671b3695d0b69b5**](TeamDataAccessApplicationApi.md#call0ff8ad69b213abf8d671b3695d0b69b5) | **GET** /api/v1/teams/{teamId}/dar/applications | TeamDataAccessApplicationController@index |
| [**Call3f8472e47cdd8aaabb42e1065a7a0afb**](TeamDataAccessApplicationApi.md#call3f8472e47cdd8aaabb42e1065a7a0afb) | **GET** /api/v1/teams/{teamId}/dar/applications/count | TeamDataAccessApplicationController@allCounts |
| [**Call4e4d590ec8943163168e4fc34bd166a1**](TeamDataAccessApplicationApi.md#call4e4d590ec8943163168e4fc34bd166a1) | **GET** /api/v1/teams/{teamId}/dar/applications/{id} | TeamDataAccessApplicationController@show |
| [**CountUniqueFieldsDarApplications**](TeamDataAccessApplicationApi.md#countuniquefieldsdarapplications) | **GET** /api/v1/teams/{teamId}/dar/applications/count/{field} | TeamDataAccessApplicationController@count |

<a id="call0dabe0dfdf4eebd0c76560fd691c6472"></a>
# **Call0dabe0dfdf4eebd0c76560fd691c6472**
> Model0dabe0dfdf4eebd0c76560fd691c6472200Response Call0dabe0dfdf4eebd0c76560fd691c6472 (int teamId, int id)

TeamDataAccessApplicationController@showHeader

Get header information about a specific DAR


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**Model0dabe0dfdf4eebd0c76560fd691c6472200Response**](Model0dabe0dfdf4eebd0c76560fd691c6472200Response.md)

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

<a id="call0ff8ad69b213abf8d671b3695d0b69b5"></a>
# **Call0ff8ad69b213abf8d671b3695d0b69b5**
> Model0ff8ad69b213abf8d671b3695d0b69b5200Response Call0ff8ad69b213abf8d671b3695d0b69b5 (int teamId)

TeamDataAccessApplicationController@index

List of dar applications belonging to a team


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |

### Return type

[**Model0ff8ad69b213abf8d671b3695d0b69b5200Response**](Model0ff8ad69b213abf8d671b3695d0b69b5200Response.md)

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

<a id="call3f8472e47cdd8aaabb42e1065a7a0afb"></a>
# **Call3f8472e47cdd8aaabb42e1065a7a0afb**
> CountUniqueFieldsCollections200Response Call3f8472e47cdd8aaabb42e1065a7a0afb (int teamId)

TeamDataAccessApplicationController@allCounts

Get Counts for all status fields in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |

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

<a id="call4e4d590ec8943163168e4fc34bd166a1"></a>
# **Call4e4d590ec8943163168e4fc34bd166a1**
> Model4e4d590ec8943163168e4fc34bd166a1200Response Call4e4d590ec8943163168e4fc34bd166a1 (int teamId, int id)

TeamDataAccessApplicationController@show

Return a single DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**Model4e4d590ec8943163168e4fc34bd166a1200Response**](Model4e4d590ec8943163168e4fc34bd166a1200Response.md)

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

<a id="countuniquefieldsdarapplications"></a>
# **CountUniqueFieldsDarApplications**
> CountUniqueFieldsCollections200Response CountUniqueFieldsDarApplications (int teamId, string field)

TeamDataAccessApplicationController@count

Get Counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
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

