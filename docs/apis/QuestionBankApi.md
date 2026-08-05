# GatewayApiSdk.Api.QuestionBankApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateQuestionBankQuestion**](QuestionBankApi.md#createquestionbankquestion) | **POST** /api/v1/questions | QuestionBank@store |
| [**DeleteQuestionBankQuestion**](QuestionBankApi.md#deletequestionbankquestion) | **DELETE** /api/v1/questions/{id} | QuestionBank@destroy |
| [**DownloadQuestionBankQuestionFile**](QuestionBankApi.md#downloadquestionbankquestionfile) | **GET** /api/v1/questions/{id}/files/{fileId} | QuestionBank@destroyFile |
| [**EditQuestionBankQuestion**](QuestionBankApi.md#editquestionbankquestion) | **PATCH** /api/v1/questions/{id} | QuestionBank@update |
| [**FetchArchivedQuestionBankQuestions**](QuestionBankApi.md#fetcharchivedquestionbankquestions) | **GET** /api/v1/questions/archived | QuestionBank@indexArchived |
| [**FetchCustomQuestionBankQuestions**](QuestionBankApi.md#fetchcustomquestionbankquestions) | **GET** /api/v1/questions/custom | QuestionBank@indexCustom |
| [**FetchQuestionBankQuestion**](QuestionBankApi.md#fetchquestionbankquestion) | **GET** /api/v1/questions/{id} | QuestionBank@show |
| [**FetchQuestionBankQuestionVersion**](QuestionBankApi.md#fetchquestionbankquestionversion) | **GET** /api/v1/questions/version/{id} | QuestionBank@showVersion |
| [**FetchQuestionBankQuestions**](QuestionBankApi.md#fetchquestionbankquestions) | **GET** /api/v1/questions | QuestionBank@index |
| [**FetchStandardQuestionBankQuestions**](QuestionBankApi.md#fetchstandardquestionbankquestions) | **GET** /api/v1/questions/standard | QuestionBank@indexStandard |
| [**FetchTeamQuestionBankQuestionsBySection**](QuestionBankApi.md#fetchteamquestionbankquestionsbysection) | **GET** /api/v1/teams/{teamId}/questions/section/{sectionId} | TeamQuestionBank@indexBySection |
| [**UpdateQuestionBankQuestion**](QuestionBankApi.md#updatequestionbankquestion) | **PUT** /api/v1/questions/{id} | QuestionBank@update |
| [**UpdateQuestionBankQuestionStatus**](QuestionBankApi.md#updatequestionbankquestionstatus) | **PATCH** /api/v1/questions/{id}/{status} | QuestionBank@updateStatus |

<a id="createquestionbankquestion"></a>
# **CreateQuestionBankQuestion**
> CreateDarIntegration201Response CreateQuestionBankQuestion (CreateQuestionBankQuestionRequest createQuestionBankQuestionRequest)

QuestionBank@store

Create a new system question bank question with FE-helpful input format


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createQuestionBankQuestionRequest** | [**CreateQuestionBankQuestionRequest**](CreateQuestionBankQuestionRequest.md) | QuestionBank definition |  |

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

<a id="deletequestionbankquestion"></a>
# **DeleteQuestionBankQuestion**
> DeleteApplications200Response DeleteQuestionBankQuestion (int id)

QuestionBank@destroy

Delete a system question bank question


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question id |  |

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

<a id="downloadquestionbankquestionfile"></a>
# **DownloadQuestionBankQuestionFile**
> DeleteApplications200Response DownloadQuestionBankQuestionFile (int id, int fileId)

QuestionBank@destroyFile

Download a system question bank question


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question id |  |
| **fileId** | **int** | file uuid |  |

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

<a id="editquestionbankquestion"></a>
# **EditQuestionBankQuestion**
> UpdateQuestionBankQuestion200Response EditQuestionBankQuestion (int id, EditQuestionBankQuestionRequest editQuestionBankQuestionRequest)

QuestionBank@update

Edit a system question bank question - use this for parents and children separately


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question id |  |
| **editQuestionBankQuestionRequest** | [**EditQuestionBankQuestionRequest**](EditQuestionBankQuestionRequest.md) | QuestionBank definition |  |

### Return type

[**UpdateQuestionBankQuestion200Response**](UpdateQuestionBankQuestion200Response.md)

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

<a id="fetcharchivedquestionbankquestions"></a>
# **FetchArchivedQuestionBankQuestions**
> FetchQuestionBankQuestions200Response FetchArchivedQuestionBankQuestions (int sectionId = null, int isChild = null, int perPage = null, int page = null)

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

[**FetchQuestionBankQuestions200Response**](FetchQuestionBankQuestions200Response.md)

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

<a id="fetchcustomquestionbankquestions"></a>
# **FetchCustomQuestionBankQuestions**
> FetchCustomQuestionBankQuestions200Response FetchCustomQuestionBankQuestions (int sectionId = null, int isChild = null, int perPage = null, int page = null)

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

[**FetchCustomQuestionBankQuestions200Response**](FetchCustomQuestionBankQuestions200Response.md)

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

<a id="fetchquestionbankquestion"></a>
# **FetchQuestionBankQuestion**
> FetchQuestionBankQuestion200Response FetchQuestionBankQuestion (int id)

QuestionBank@show

Return the latest question bank question version for the supplied question id, in an FE-friendly format


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question id |  |

### Return type

[**FetchQuestionBankQuestion200Response**](FetchQuestionBankQuestion200Response.md)

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

<a id="fetchquestionbankquestionversion"></a>
# **FetchQuestionBankQuestionVersion**
> FetchQuestionBankQuestionVersion200Response FetchQuestionBankQuestionVersion (int id)

QuestionBank@showVersion

Return a single system question bank question version


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question version id |  |

### Return type

[**FetchQuestionBankQuestionVersion200Response**](FetchQuestionBankQuestionVersion200Response.md)

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

<a id="fetchquestionbankquestions"></a>
# **FetchQuestionBankQuestions**
> FetchQuestionBankQuestions200Response FetchQuestionBankQuestions (int sectionId = null, int isChild = null, int perPage = null, int page = null)

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

[**FetchQuestionBankQuestions200Response**](FetchQuestionBankQuestions200Response.md)

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

<a id="fetchstandardquestionbankquestions"></a>
# **FetchStandardQuestionBankQuestions**
> FetchStandardQuestionBankQuestions200Response FetchStandardQuestionBankQuestions (int sectionId = null, int isChild = null, int perPage = null, int page = null)

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

[**FetchStandardQuestionBankQuestions200Response**](FetchStandardQuestionBankQuestions200Response.md)

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

<a id="fetchteamquestionbankquestionsbysection"></a>
# **FetchTeamQuestionBankQuestionsBySection**
> FetchTeamQuestionBankQuestionsBySection200Response FetchTeamQuestionBankQuestionsBySection (int teamId, int sectionId, int isChild = null)

TeamQuestionBank@indexBySection

List of question bank questions by section


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team ID |  |
| **sectionId** | **int** | section id |  |
| **isChild** | **int** | filter on is_child field | [optional]  |

### Return type

[**FetchTeamQuestionBankQuestionsBySection200Response**](FetchTeamQuestionBankQuestionsBySection200Response.md)

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

<a id="updatequestionbankquestion"></a>
# **UpdateQuestionBankQuestion**
> UpdateQuestionBankQuestion200Response UpdateQuestionBankQuestion (int id, UpdateQuestionBankQuestionRequest updateQuestionBankQuestionRequest)

QuestionBank@update

Update a system question bank question - children and their versions are updated through parents


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question id |  |
| **updateQuestionBankQuestionRequest** | [**UpdateQuestionBankQuestionRequest**](UpdateQuestionBankQuestionRequest.md) | QuestionBank definition |  |

### Return type

[**UpdateQuestionBankQuestion200Response**](UpdateQuestionBankQuestion200Response.md)

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

<a id="updatequestionbankquestionstatus"></a>
# **UpdateQuestionBankQuestionStatus**
> UpdateQuestionBankQuestionStatus200Response UpdateQuestionBankQuestionStatus (int id, string status)

QuestionBank@updateStatus

Lock, unlock, archive or unarchive a question bank question


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | question bank question id |  |
| **status** | **string** | lock or unlock |  |

### Return type

[**UpdateQuestionBankQuestionStatus200Response**](UpdateQuestionBankQuestionStatus200Response.md)

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

