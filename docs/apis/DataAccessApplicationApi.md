# GatewayApiSdk.Api.DataAccessApplicationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**A3e2f5885d871929e4b5d81f58ddf867**](DataAccessApplicationApi.md#a3e2f5885d871929e4b5d81f58ddf867) | **GET** /api/v1/users/{userId}/dar/applications/{id}/files | DataAccessApplication@showFiles |
| [**A6ad90e00b65d8dbf974c30b43586052**](DataAccessApplicationApi.md#a6ad90e00b65d8dbf974c30b43586052) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/files/{fileId}/download | DataAccessApplication@downloadFile |
| [**Bcfd40c79f3f5e7e33e2efd241a9b1a5**](DataAccessApplicationApi.md#bcfd40c79f3f5e7e33e2efd241a9b1a5) | **PUT** /api/v1/users/{userId}/dar/applications/{id} | DataAccessApplication@update |
| [**Call2692176ac531294e07a905f5735d15ac**](DataAccessApplicationApi.md#call2692176ac531294e07a905f5735d15ac) | **POST** /api/v1/dar/applications | DataAccessApplication@store |
| [**Call27b8f8d036cdb3330072da6d0aaf7344**](DataAccessApplicationApi.md#call27b8f8d036cdb3330072da6d0aaf7344) | **DELETE** /api/v1/users/{userId}/dar/applications/{id} | DataAccessApplication@destroy |
| [**Call2e4f31039d1a014480ec9444231e5f23**](DataAccessApplicationApi.md#call2e4f31039d1a014480ec9444231e5f23) | **DELETE** /api/v1/dar/applications/{id}/files/{fileId} | DataAccessApplication@destroyFile |
| [**Call3da503b7dd0562e285ce75c4c026ce76**](DataAccessApplicationApi.md#call3da503b7dd0562e285ce75c4c026ce76) | **DELETE** /api/v1/dar/applications/{id} | DataAccessApplication@destroy |
| [**Call473ee45c3962ae2a02abbac5015dce6a**](DataAccessApplicationApi.md#call473ee45c3962ae2a02abbac5015dce6a) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/answers | DataAccessApplication@showAnswers |
| [**Call5cd6e8b93c6db11618e96a968b037db9**](DataAccessApplicationApi.md#call5cd6e8b93c6db11618e96a968b037db9) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/download | DataAccessApplication@download |
| [**Call74f3b5729b08a4be0d17e4b1c7fa2aa9**](DataAccessApplicationApi.md#call74f3b5729b08a4be0d17e4b1c7fa2aa9) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/status | DataAccessApplication@status |
| [**Call897ef426f5db99512aaed03854777419**](DataAccessApplicationApi.md#call897ef426f5db99512aaed03854777419) | **DELETE** /api/v1/users/{userId}/dar/applications/{id}/files/{fileId} | DataAccessApplication@destroyFile |
| [**Call928c1c4e39f13593bdec88641ee83120**](DataAccessApplicationApi.md#call928c1c4e39f13593bdec88641ee83120) | **GET** /api/v1/teams/{teamId}/dar/applications/{id}/files | DataAccessApplication@showFiles |
| [**F07acaef191991ba38aa72f6d40d988f**](DataAccessApplicationApi.md#f07acaef191991ba38aa72f6d40d988f) | **GET** /api/v1/users/{userId}/dar/applications/{id}/files/{fileId}/download | DataAccessApplication@downloadFile |
| [**F5e83ee26e8a390328a3bf23e750b153**](DataAccessApplicationApi.md#f5e83ee26e8a390328a3bf23e750b153) | **PATCH** /api/v1/users/{userId}/dar/applications/{id} | DataAccessApplication@update |
| [**Fe59a4a568b5a79e886e86951f29518a**](DataAccessApplicationApi.md#fe59a4a568b5a79e886e86951f29518a) | **PATCH** /api/v1/teams/{teamId}/dar/applications/{id} | DataAccessApplication@update |
| [**Ff8efbb0c9dffd80c3eb2ea675a94c99**](DataAccessApplicationApi.md#ff8efbb0c9dffd80c3eb2ea675a94c99) | **DELETE** /api/v1/teams/{teamId}/dar/applications/{id}/files/{fileId} | DataAccessApplication@destroyFile |

<a id="a3e2f5885d871929e4b5d81f58ddf867"></a>
# **A3e2f5885d871929e4b5d81f58ddf867**
> Model928c1c4e39f13593bdec88641ee83120200Response A3e2f5885d871929e4b5d81f58ddf867 (int id, int userId)

DataAccessApplication@showFiles

Return a list of files associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR application id |  |
| **userId** | **int** | User id |  |

### Return type

[**Model928c1c4e39f13593bdec88641ee83120200Response**](Model928c1c4e39f13593bdec88641ee83120200Response.md)

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

<a id="a6ad90e00b65d8dbf974c30b43586052"></a>
# **A6ad90e00b65d8dbf974c30b43586052**
> void A6ad90e00b65d8dbf974c30b43586052 (int teamId, int id, string fileId)

DataAccessApplication@downloadFile

Download a file associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **fileId** | **string** | File uuid |  |

### Return type

void (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: file, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="bcfd40c79f3f5e7e33e2efd241a9b1a5"></a>
# **Bcfd40c79f3f5e7e33e2efd241a9b1a5**
> Model4e4d590ec8943163168e4fc34bd166a1200Response Bcfd40c79f3f5e7e33e2efd241a9b1a5 (int userId, int id, Bcfd40c79f3f5e7e33e2efd241a9b1a5Request bcfd40c79f3f5e7e33e2efd241a9b1a5Request)

DataAccessApplication@update

Update a system DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |
| **bcfd40c79f3f5e7e33e2efd241a9b1a5Request** | [**Bcfd40c79f3f5e7e33e2efd241a9b1a5Request**](Bcfd40c79f3f5e7e33e2efd241a9b1a5Request.md) | DataAccessApplication definition |  |

### Return type

[**Model4e4d590ec8943163168e4fc34bd166a1200Response**](Model4e4d590ec8943163168e4fc34bd166a1200Response.md)

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

<a id="call2692176ac531294e07a905f5735d15ac"></a>
# **Call2692176ac531294e07a905f5735d15ac**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Call2692176ac531294e07a905f5735d15ac (Model2692176ac531294e07a905f5735d15acRequest model2692176ac531294e07a905f5735d15acRequest)

DataAccessApplication@store

Creates a new DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model2692176ac531294e07a905f5735d15acRequest** | [**Model2692176ac531294e07a905f5735d15acRequest**](Model2692176ac531294e07a905f5735d15acRequest.md) | DataAccessApplication definition |  |

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

<a id="call27b8f8d036cdb3330072da6d0aaf7344"></a>
# **Call27b8f8d036cdb3330072da6d0aaf7344**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call27b8f8d036cdb3330072da6d0aaf7344 (int userId, int id)

DataAccessApplication@destroy

Delete a users DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |

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
| **401** | Unauthorized |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call2e4f31039d1a014480ec9444231e5f23"></a>
# **Call2e4f31039d1a014480ec9444231e5f23**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call2e4f31039d1a014480ec9444231e5f23 (int id, string fileId)

DataAccessApplication@destroyFile

Delete a file associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR application id |  |
| **fileId** | **string** | File id |  |

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

<a id="call3da503b7dd0562e285ce75c4c026ce76"></a>
# **Call3da503b7dd0562e285ce75c4c026ce76**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call3da503b7dd0562e285ce75c4c026ce76 (int id)

DataAccessApplication@destroy

Delete a system DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR application id |  |

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

<a id="call473ee45c3962ae2a02abbac5015dce6a"></a>
# **Call473ee45c3962ae2a02abbac5015dce6a**
> Model473ee45c3962ae2a02abbac5015dce6a200Response Call473ee45c3962ae2a02abbac5015dce6a (int teamId, int id)

DataAccessApplication@showAnswers

Return answers from a single DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**Model473ee45c3962ae2a02abbac5015dce6a200Response**](Model473ee45c3962ae2a02abbac5015dce6a200Response.md)

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

<a id="call5cd6e8b93c6db11618e96a968b037db9"></a>
# **Call5cd6e8b93c6db11618e96a968b037db9**
> void Call5cd6e8b93c6db11618e96a968b037db9 (int teamId, int id)

DataAccessApplication@download

Returns a DAR form as a CSV with attached files as a zip


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |

### Return type

void (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: file, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="call74f3b5729b08a4be0d17e4b1c7fa2aa9"></a>
# **Call74f3b5729b08a4be0d17e4b1c7fa2aa9**
> Model74f3b5729b08a4be0d17e4b1c7fa2aa9200Response Call74f3b5729b08a4be0d17e4b1c7fa2aa9 (int teamId, int id)

DataAccessApplication@status

Return the status history of a single DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**Model74f3b5729b08a4be0d17e4b1c7fa2aa9200Response**](Model74f3b5729b08a4be0d17e4b1c7fa2aa9200Response.md)

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

<a id="call897ef426f5db99512aaed03854777419"></a>
# **Call897ef426f5db99512aaed03854777419**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call897ef426f5db99512aaed03854777419 (int id, int userId, string fileId)

DataAccessApplication@destroyFile

Delete a file associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR application id |  |
| **userId** | **int** | User id |  |
| **fileId** | **string** | File uuid |  |

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

<a id="call928c1c4e39f13593bdec88641ee83120"></a>
# **Call928c1c4e39f13593bdec88641ee83120**
> Model928c1c4e39f13593bdec88641ee83120200Response Call928c1c4e39f13593bdec88641ee83120 (int teamId, int id)

DataAccessApplication@showFiles

Return a list of files associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**Model928c1c4e39f13593bdec88641ee83120200Response**](Model928c1c4e39f13593bdec88641ee83120200Response.md)

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

<a id="f07acaef191991ba38aa72f6d40d988f"></a>
# **F07acaef191991ba38aa72f6d40d988f**
> void F07acaef191991ba38aa72f6d40d988f (int id, int userId, string fileId)

DataAccessApplication@downloadFile

Download a file associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR application id |  |
| **userId** | **int** | User id |  |
| **fileId** | **string** | File id |  |

### Return type

void (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: file, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="f5e83ee26e8a390328a3bf23e750b153"></a>
# **F5e83ee26e8a390328a3bf23e750b153**
> Model4e4d590ec8943163168e4fc34bd166a1200Response F5e83ee26e8a390328a3bf23e750b153 (int userId, int id, F5e83ee26e8a390328a3bf23e750b153Request f5e83ee26e8a390328a3bf23e750b153Request)

DataAccessApplication@update

Edit a system DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |
| **f5e83ee26e8a390328a3bf23e750b153Request** | [**F5e83ee26e8a390328a3bf23e750b153Request**](F5e83ee26e8a390328a3bf23e750b153Request.md) | DataAccessApplication definition |  |

### Return type

[**Model4e4d590ec8943163168e4fc34bd166a1200Response**](Model4e4d590ec8943163168e4fc34bd166a1200Response.md)

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

<a id="fe59a4a568b5a79e886e86951f29518a"></a>
# **Fe59a4a568b5a79e886e86951f29518a**
> Model4e4d590ec8943163168e4fc34bd166a1200Response Fe59a4a568b5a79e886e86951f29518a (int teamId, int id, Fe59a4a568b5a79e886e86951f29518aRequest fe59a4a568b5a79e886e86951f29518aRequest)

DataAccessApplication@update

Edit a system DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **fe59a4a568b5a79e886e86951f29518aRequest** | [**Fe59a4a568b5a79e886e86951f29518aRequest**](Fe59a4a568b5a79e886e86951f29518aRequest.md) | DataAccessApplication definition |  |

### Return type

[**Model4e4d590ec8943163168e4fc34bd166a1200Response**](Model4e4d590ec8943163168e4fc34bd166a1200Response.md)

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

<a id="ff8efbb0c9dffd80c3eb2ea675a94c99"></a>
# **Ff8efbb0c9dffd80c3eb2ea675a94c99**
> C29b5b3424f7317b69b4bda048ccfafb200Response Ff8efbb0c9dffd80c3eb2ea675a94c99 (int teamId, int id, int fileId)

DataAccessApplication@destroyFile

Delete a file associated with a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **fileId** | **int** | File id |  |

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

