# GatewayApiSdk.Api.DataAccessTemplateApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**B1fa0f3b5f03176ce6b96d1d4ee27aa8**](DataAccessTemplateApi.md#b1fa0f3b5f03176ce6b96d1d4ee27aa8) | **GET** /ap1/v1/dar/templates/{id}/download | DataAccessTemplate@downloadFile |
| [**C0e9ad253ec08e6e03a40ed8759e744d**](DataAccessTemplateApi.md#c0e9ad253ec08e6e03a40ed8759e744d) | **DELETE** /api/v1/dar/templates/{id} | DataAccessTemplate@destroy |
| [**Call234386e06c6b29d5aaca2ed8f89cb9aa**](DataAccessTemplateApi.md#call234386e06c6b29d5aaca2ed8f89cb9aa) | **GET** /api/v1/dar/templates | DataAccessTemplate@index |
| [**Call3f2b4dcc3b5e548e62f79a32aa8f0052**](DataAccessTemplateApi.md#call3f2b4dcc3b5e548e62f79a32aa8f0052) | **GET** /api/v1/dar/templates/{id} | DataAccessTemplate@show |
| [**Call6196987e50c600396a439939cea635a3**](DataAccessTemplateApi.md#call6196987e50c600396a439939cea635a3) | **PATCH** /api/v1/dar/templates/{id} | DataAccessTemplate@update |
| [**Call6dae0c2af6ca442f90a65e7c65a13252**](DataAccessTemplateApi.md#call6dae0c2af6ca442f90a65e7c65a13252) | **PUT** /api/v1/dar/templates/{id} | DataAccessTemplate@update |
| [**Call70d4b0fcc281e6491f510f58028762c9**](DataAccessTemplateApi.md#call70d4b0fcc281e6491f510f58028762c9) | **POST** /api/v1/dar/templates | DataAccessTemplate@store |

<a id="b1fa0f3b5f03176ce6b96d1d4ee27aa8"></a>
# **B1fa0f3b5f03176ce6b96d1d4ee27aa8**
> void B1fa0f3b5f03176ce6b96d1d4ee27aa8 (int id)

DataAccessTemplate@downloadFile

Download the template for a file based DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR template id |  |

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

<a id="c0e9ad253ec08e6e03a40ed8759e744d"></a>
# **C0e9ad253ec08e6e03a40ed8759e744d**
> C29b5b3424f7317b69b4bda048ccfafb200Response C0e9ad253ec08e6e03a40ed8759e744d (int id)

DataAccessTemplate@destroy

Delete a system DAR template


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR template id |  |

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

<a id="call234386e06c6b29d5aaca2ed8f89cb9aa"></a>
# **Call234386e06c6b29d5aaca2ed8f89cb9aa**
> Model234386e06c6b29d5aaca2ed8f89cb9aa200Response Call234386e06c6b29d5aaca2ed8f89cb9aa (int withQuestions = null, string published = null)

DataAccessTemplate@index

List of DAR templates


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **withQuestions** | **int** | Include questions in response | [optional]  |
| **published** | **string** | Template publication status to filter by (true, false) | [optional]  |

### Return type

[**Model234386e06c6b29d5aaca2ed8f89cb9aa200Response**](Model234386e06c6b29d5aaca2ed8f89cb9aa200Response.md)

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

<a id="call3f2b4dcc3b5e548e62f79a32aa8f0052"></a>
# **Call3f2b4dcc3b5e548e62f79a32aa8f0052**
> Model3f2b4dcc3b5e548e62f79a32aa8f0052200Response Call3f2b4dcc3b5e548e62f79a32aa8f0052 (int id)

DataAccessTemplate@show

Return a single DAR template


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR template id |  |

### Return type

[**Model3f2b4dcc3b5e548e62f79a32aa8f0052200Response**](Model3f2b4dcc3b5e548e62f79a32aa8f0052200Response.md)

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

<a id="call6196987e50c600396a439939cea635a3"></a>
# **Call6196987e50c600396a439939cea635a3**
> Model6196987e50c600396a439939cea635a3200Response Call6196987e50c600396a439939cea635a3 (int id, Model6196987e50c600396a439939cea635a3Request model6196987e50c600396a439939cea635a3Request, int sectionId = null)

DataAccessTemplate@update

Edit a system DAR template


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR template id |  |
| **model6196987e50c600396a439939cea635a3Request** | [**Model6196987e50c600396a439939cea635a3Request**](Model6196987e50c600396a439939cea635a3Request.md) | DataAccessTemplate definition |  |
| **sectionId** | **int** | Section id | [optional]  |

### Return type

[**Model6196987e50c600396a439939cea635a3200Response**](Model6196987e50c600396a439939cea635a3200Response.md)

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

<a id="call6dae0c2af6ca442f90a65e7c65a13252"></a>
# **Call6dae0c2af6ca442f90a65e7c65a13252**
> Model3f2b4dcc3b5e548e62f79a32aa8f0052200Response Call6dae0c2af6ca442f90a65e7c65a13252 (int id, Model6dae0c2af6ca442f90a65e7c65a13252Request model6dae0c2af6ca442f90a65e7c65a13252Request)

DataAccessTemplate@update

Update a system DAR template


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | DAR template id |  |
| **model6dae0c2af6ca442f90a65e7c65a13252Request** | [**Model6dae0c2af6ca442f90a65e7c65a13252Request**](Model6dae0c2af6ca442f90a65e7c65a13252Request.md) | DataAccessTemplate definition |  |

### Return type

[**Model3f2b4dcc3b5e548e62f79a32aa8f0052200Response**](Model3f2b4dcc3b5e548e62f79a32aa8f0052200Response.md)

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

<a id="call70d4b0fcc281e6491f510f58028762c9"></a>
# **Call70d4b0fcc281e6491f510f58028762c9**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Call70d4b0fcc281e6491f510f58028762c9 (Model70d4b0fcc281e6491f510f58028762c9Request model70d4b0fcc281e6491f510f58028762c9Request)

DataAccessTemplate@store

Creates a new DAR template


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model70d4b0fcc281e6491f510f58028762c9Request** | [**Model70d4b0fcc281e6491f510f58028762c9Request**](Model70d4b0fcc281e6491f510f58028762c9Request.md) | DataAccessTemplate definition |  |

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

