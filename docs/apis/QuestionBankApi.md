# GatewayApiSdk.Api.QuestionBankApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**A3f9ce42420fdef136cfc7b0de8e2683**](QuestionBankApi.md#a3f9ce42420fdef136cfc7b0de8e2683) | **GET** /api/v1/questions/version/{id} | QuestionBank@showVersion |
| [**Call04e09f4aada3406dbc08715865880f4f**](QuestionBankApi.md#call04e09f4aada3406dbc08715865880f4f) | **GET** /api/v1/teams/{teamId}/questions/section/{sectionId} | TeamQuestionBank@indexBySection |
| [**Call17336ba551813e00975d3c2da09211c0**](QuestionBankApi.md#call17336ba551813e00975d3c2da09211c0) | **GET** /api/v1/questions/{id} | QuestionBank@show |
| [**Call35856fcdf6980ae4da3303ec5a8d90b7**](QuestionBankApi.md#call35856fcdf6980ae4da3303ec5a8d90b7) | **GET** /api/v1/questions | QuestionBank@index |
| [**Call35b36a3a067579d62500b09623dbffb6**](QuestionBankApi.md#call35b36a3a067579d62500b09623dbffb6) | **GET** /api/v1/questions/{id}/files/{fileId} | QuestionBank@destroyFile |
| [**Call38b0b31c2029a219013fa640588a4a69**](QuestionBankApi.md#call38b0b31c2029a219013fa640588a4a69) | **POST** /api/v1/questions | QuestionBank@store |
| [**Call64d6f1d6c88cbcfccd3e511b29c394d6**](QuestionBankApi.md#call64d6f1d6c88cbcfccd3e511b29c394d6) | **PUT** /api/v1/questions/{id} | QuestionBank@update |
| [**D38b27b30f91d05932ca855e021c8ffd**](QuestionBankApi.md#d38b27b30f91d05932ca855e021c8ffd) | **PATCH** /api/v1/questions/{id} | QuestionBank@update |
| [**Da82f7ce4870bd37af28a192877b22a7**](QuestionBankApi.md#da82f7ce4870bd37af28a192877b22a7) | **PATCH** /api/v1/questions/{id}/{status} | QuestionBank@updateStatus |
| [**Dbaa6922ceaa314314605cba51dbb9df**](QuestionBankApi.md#dbaa6922ceaa314314605cba51dbb9df) | **GET** /api/v1/questions/archived | QuestionBank@indexArchived |
| [**E7408526aeb9ed9cc633d4a9f25cfa14**](QuestionBankApi.md#e7408526aeb9ed9cc633d4a9f25cfa14) | **DELETE** /api/v1/questions/{id} | QuestionBank@destroy |
| [**Ea6f671b0436fa57891fe098994556a1**](QuestionBankApi.md#ea6f671b0436fa57891fe098994556a1) | **GET** /api/v1/questions/standard | QuestionBank@indexStandard |
| [**Fa7079be66c6e1f5a236ecac24b63e2b**](QuestionBankApi.md#fa7079be66c6e1f5a236ecac24b63e2b) | **GET** /api/v1/questions/custom | QuestionBank@indexCustom |

<a id="a3f9ce42420fdef136cfc7b0de8e2683"></a>
# **A3f9ce42420fdef136cfc7b0de8e2683**
> A3f9ce42420fdef136cfc7b0de8e2683200Response A3f9ce42420fdef136cfc7b0de8e2683 (int id)

QuestionBank@showVersion

Return a single system question bank question version


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question version id |  |

### Return type

[**A3f9ce42420fdef136cfc7b0de8e2683200Response**](A3f9ce42420fdef136cfc7b0de8e2683200Response.md)

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

<a id="call04e09f4aada3406dbc08715865880f4f"></a>
# **Call04e09f4aada3406dbc08715865880f4f**
> Model04e09f4aada3406dbc08715865880f4f200Response Call04e09f4aada3406dbc08715865880f4f (int teamId, int sectionId, int isChild = null)

TeamQuestionBank@indexBySection

List of question bank questions by section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team ID |  |
| **sectionId** | **int** | section id |  |
| **isChild** | **int** | filter on is_child field | [optional]  |

### Return type

[**Model04e09f4aada3406dbc08715865880f4f200Response**](Model04e09f4aada3406dbc08715865880f4f200Response.md)

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

<a id="call17336ba551813e00975d3c2da09211c0"></a>
# **Call17336ba551813e00975d3c2da09211c0**
> Model17336ba551813e00975d3c2da09211c0200Response Call17336ba551813e00975d3c2da09211c0 (int id)

QuestionBank@show

Return the latest question bank question version for the supplied question id, in an FE-friendly format


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question id |  |

### Return type

[**Model17336ba551813e00975d3c2da09211c0200Response**](Model17336ba551813e00975d3c2da09211c0200Response.md)

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

<a id="call35856fcdf6980ae4da3303ec5a8d90b7"></a>
# **Call35856fcdf6980ae4da3303ec5a8d90b7**
> Model35856fcdf6980ae4da3303ec5a8d90b7200Response Call35856fcdf6980ae4da3303ec5a8d90b7 (int sectionId = null, int isChild = null, int perPage = null, int page = null)

QuestionBank@index

List of question bank questions


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **sectionId** | **int** | section id | [optional]  |
| **isChild** | **int** | filter on is_child field | [optional]  |
| **perPage** | **int** | per page | [optional]  |
| **page** | **int** | page | [optional]  |

### Return type

[**Model35856fcdf6980ae4da3303ec5a8d90b7200Response**](Model35856fcdf6980ae4da3303ec5a8d90b7200Response.md)

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

<a id="call35b36a3a067579d62500b09623dbffb6"></a>
# **Call35b36a3a067579d62500b09623dbffb6**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call35b36a3a067579d62500b09623dbffb6 (int id, int fileId)

QuestionBank@destroyFile

Download a system question bank question


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question id |  |
| **fileId** | **int** | file uuid |  |

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

<a id="call38b0b31c2029a219013fa640588a4a69"></a>
# **Call38b0b31c2029a219013fa640588a4a69**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response Call38b0b31c2029a219013fa640588a4a69 (Model38b0b31c2029a219013fa640588a4a69Request model38b0b31c2029a219013fa640588a4a69Request)

QuestionBank@store

Create a new system question bank question with FE-helpful input format


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model38b0b31c2029a219013fa640588a4a69Request** | [**Model38b0b31c2029a219013fa640588a4a69Request**](Model38b0b31c2029a219013fa640588a4a69Request.md) | QuestionBank definition |  |

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

<a id="call64d6f1d6c88cbcfccd3e511b29c394d6"></a>
# **Call64d6f1d6c88cbcfccd3e511b29c394d6**
> Model64d6f1d6c88cbcfccd3e511b29c394d6200Response Call64d6f1d6c88cbcfccd3e511b29c394d6 (int id, Model64d6f1d6c88cbcfccd3e511b29c394d6Request model64d6f1d6c88cbcfccd3e511b29c394d6Request)

QuestionBank@update

Update a system question bank question - children and their versions are updated through parents


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question id |  |
| **model64d6f1d6c88cbcfccd3e511b29c394d6Request** | [**Model64d6f1d6c88cbcfccd3e511b29c394d6Request**](Model64d6f1d6c88cbcfccd3e511b29c394d6Request.md) | QuestionBank definition |  |

### Return type

[**Model64d6f1d6c88cbcfccd3e511b29c394d6200Response**](Model64d6f1d6c88cbcfccd3e511b29c394d6200Response.md)

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

<a id="d38b27b30f91d05932ca855e021c8ffd"></a>
# **D38b27b30f91d05932ca855e021c8ffd**
> Model64d6f1d6c88cbcfccd3e511b29c394d6200Response D38b27b30f91d05932ca855e021c8ffd (int id, D38b27b30f91d05932ca855e021c8ffdRequest d38b27b30f91d05932ca855e021c8ffdRequest)

QuestionBank@update

Edit a system question bank question - use this for parents and children separately


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question id |  |
| **d38b27b30f91d05932ca855e021c8ffdRequest** | [**D38b27b30f91d05932ca855e021c8ffdRequest**](D38b27b30f91d05932ca855e021c8ffdRequest.md) | QuestionBank definition |  |

### Return type

[**Model64d6f1d6c88cbcfccd3e511b29c394d6200Response**](Model64d6f1d6c88cbcfccd3e511b29c394d6200Response.md)

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

<a id="da82f7ce4870bd37af28a192877b22a7"></a>
# **Da82f7ce4870bd37af28a192877b22a7**
> Da82f7ce4870bd37af28a192877b22a7200Response Da82f7ce4870bd37af28a192877b22a7 (int id, string status)

QuestionBank@updateStatus

Lock, unlock, archive or unarchive a question bank question


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question id |  |
| **status** | **string** | lock or unlock |  |

### Return type

[**Da82f7ce4870bd37af28a192877b22a7200Response**](Da82f7ce4870bd37af28a192877b22a7200Response.md)

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

<a id="dbaa6922ceaa314314605cba51dbb9df"></a>
# **Dbaa6922ceaa314314605cba51dbb9df**
> Model35856fcdf6980ae4da3303ec5a8d90b7200Response Dbaa6922ceaa314314605cba51dbb9df (int sectionId = null, int isChild = null, int perPage = null, int page = null)

QuestionBank@indexArchived

List of archived question bank questions


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **sectionId** | **int** | section id | [optional]  |
| **isChild** | **int** | filter on is_child field | [optional]  |
| **perPage** | **int** | per page | [optional]  |
| **page** | **int** | page | [optional]  |

### Return type

[**Model35856fcdf6980ae4da3303ec5a8d90b7200Response**](Model35856fcdf6980ae4da3303ec5a8d90b7200Response.md)

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

<a id="e7408526aeb9ed9cc633d4a9f25cfa14"></a>
# **E7408526aeb9ed9cc633d4a9f25cfa14**
> C29b5b3424f7317b69b4bda048ccfafb200Response E7408526aeb9ed9cc633d4a9f25cfa14 (int id)

QuestionBank@destroy

Delete a system question bank question


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question id |  |

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

<a id="ea6f671b0436fa57891fe098994556a1"></a>
# **Ea6f671b0436fa57891fe098994556a1**
> Ea6f671b0436fa57891fe098994556a1200Response Ea6f671b0436fa57891fe098994556a1 (int sectionId = null, int isChild = null, int perPage = null, int page = null)

QuestionBank@indexStandard

List of standard question bank questions


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **sectionId** | **int** | section id | [optional]  |
| **isChild** | **int** | filter on is_child field | [optional]  |
| **perPage** | **int** | per page | [optional]  |
| **page** | **int** | page | [optional]  |

### Return type

[**Ea6f671b0436fa57891fe098994556a1200Response**](Ea6f671b0436fa57891fe098994556a1200Response.md)

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

<a id="fa7079be66c6e1f5a236ecac24b63e2b"></a>
# **Fa7079be66c6e1f5a236ecac24b63e2b**
> Fa7079be66c6e1f5a236ecac24b63e2b200Response Fa7079be66c6e1f5a236ecac24b63e2b (int sectionId = null, int isChild = null, int perPage = null, int page = null)

QuestionBank@indexCustom

List of custom question bank questions


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **sectionId** | **int** | section id | [optional]  |
| **isChild** | **int** | filter on is_child field | [optional]  |
| **perPage** | **int** | per page | [optional]  |
| **page** | **int** | page | [optional]  |

### Return type

[**Fa7079be66c6e1f5a236ecac24b63e2b200Response**](Fa7079be66c6e1f5a236ecac24b63e2b200Response.md)

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

