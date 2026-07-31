# GatewayApiSdk.Api.DataAccessApplicationReviewApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateTeamDarApplicationQuestionReview**](DataAccessApplicationReviewApi.md#createteamdarapplicationquestionreview) | **POST** /api/v1/teams/{team_id}/dar/applications/{id}/questions/{questionId}/reviews | DataAccessApplicationReview@store |
| [**CreateTeamDarApplicationReview**](DataAccessApplicationReviewApi.md#createteamdarapplicationreview) | **POST** /api/v1/teams/{team_id}/dar/applications/{id}/reviews | DataAccessApplicationReview@storeGlobal |
| [**DeleteTeamDarApplicationQuestionReview**](DataAccessApplicationReviewApi.md#deleteteamdarapplicationquestionreview) | **DELETE** /api/v1/teams/{team_id}/dar/applications/{id}/questions/{questionId}/reviews/{reviewId} | DataAccessApplicationReview@destroy |
| [**DeleteTeamDarApplicationReview**](DataAccessApplicationReviewApi.md#deleteteamdarapplicationreview) | **DELETE** /api/v1/teams/{team_id}/dar/applications/{id}/reviews/{reviewId} | DataAccessApplicationReview@destroyGlobal |
| [**DeleteTeamDarApplicationReviewFile**](DataAccessApplicationReviewApi.md#deleteteamdarapplicationreviewfile) | **DELETE** /api/v1/teams/{teamId}/dar/applications/{id}/reviews/{reviewId}/files/{fileId} | DataAccessApplicationReview@destroyFile |
| [**FetchTeamDarApplicationReviewFile**](DataAccessApplicationReviewApi.md#fetchteamdarapplicationreviewfile) | **GET** /ap1/v1/teams/{teamId}/dar/applications/{id}/reviews/{reviewId}/download/{fileId} | DataAccessApplicationReview@downloadFile |
| [**FetchTeamDarApplicationReviews**](DataAccessApplicationReviewApi.md#fetchteamdarapplicationreviews) | **GET** /api/v1/teams/{team_id}/dar/applications/{id}/reviews | DataAccessApplicationReview@index |
| [**FetchUserDarApplicationReviewFile**](DataAccessApplicationReviewApi.md#fetchuserdarapplicationreviewfile) | **GET** /ap1/v1/users/{userId}/dar/applications/{id}/reviews/{reviewId}/download/{fileId} | DataAccessApplicationReview@downloadUserFile |
| [**FetchUserDarApplicationReviews**](DataAccessApplicationReviewApi.md#fetchuserdarapplicationreviews) | **GET** /api/v1/users/{userId}/dar/applications/{id}/reviews | DataAccessApplicationReview@index |
| [**UpdateTeamDarApplicationQuestionReview**](DataAccessApplicationReviewApi.md#updateteamdarapplicationquestionreview) | **PUT** /api/v1/teams/{team_id}/dar/applications/{id}/questions/{questionId}/reviews/{reviewId} | DataAccessApplicationReview@update |
| [**UpdateTeamDarApplicationReview**](DataAccessApplicationReviewApi.md#updateteamdarapplicationreview) | **PUT** /api/v1/teams/{team_id}/dar/applications/{id}/reviews/{reviewId} | DataAccessApplicationReview@updateGlobal |
| [**UpdateUserDarApplicationQuestionReview**](DataAccessApplicationReviewApi.md#updateuserdarapplicationquestionreview) | **PUT** /api/v1/users/{userId}/dar/applications/{id}/questions/{questionId}/reviews/{reviewId} | DataAccessApplicationReview@userUpdate |
| [**UpdateUserDarApplicationReview**](DataAccessApplicationReviewApi.md#updateuserdarapplicationreview) | **PUT** /api/v1/users/{userId}/dar/applications/{id}/reviews/{reviewId} | DataAccessApplicationReview@userUpdateGlobal |

<a id="createteamdarapplicationquestionreview"></a>
# **CreateTeamDarApplicationQuestionReview**
> CreateCategories200Response CreateTeamDarApplicationQuestionReview (int teamId, int id, int questionId, CreateTeamDarApplicationReviewRequest createTeamDarApplicationReviewRequest)

DataAccessApplicationReview@store

Create a new review comment on a question in a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **questionId** | **int** | DAR application question id |  |
| **createTeamDarApplicationReviewRequest** | [**CreateTeamDarApplicationReviewRequest**](CreateTeamDarApplicationReviewRequest.md) | DataAccessApplicationReview definition |  |

### Return type

[**CreateCategories200Response**](CreateCategories200Response.md)

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

<a id="createteamdarapplicationreview"></a>
# **CreateTeamDarApplicationReview**
> CreateCategories200Response CreateTeamDarApplicationReview (int teamId, int id, CreateTeamDarApplicationReviewRequest createTeamDarApplicationReviewRequest)

DataAccessApplicationReview@storeGlobal

Create a new review comment on a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **createTeamDarApplicationReviewRequest** | [**CreateTeamDarApplicationReviewRequest**](CreateTeamDarApplicationReviewRequest.md) | DataAccessApplicationReview definition |  |

### Return type

[**CreateCategories200Response**](CreateCategories200Response.md)

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

<a id="deleteteamdarapplicationquestionreview"></a>
# **DeleteTeamDarApplicationQuestionReview**
> DeleteAliases200Response DeleteTeamDarApplicationQuestionReview (int teamId, int id, int questionId, int reviewId)

DataAccessApplicationReview@destroy

Delete a review from a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **questionId** | **int** | DAR application question id |  |
| **reviewId** | **int** | DAR application review id |  |

### Return type

[**DeleteAliases200Response**](DeleteAliases200Response.md)

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

<a id="deleteteamdarapplicationreview"></a>
# **DeleteTeamDarApplicationReview**
> DeleteAliases200Response DeleteTeamDarApplicationReview (int teamId, int id, int reviewId)

DataAccessApplicationReview@destroyGlobal

Delete a review from a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **reviewId** | **int** | DAR application review id |  |

### Return type

[**DeleteAliases200Response**](DeleteAliases200Response.md)

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

<a id="deleteteamdarapplicationreviewfile"></a>
# **DeleteTeamDarApplicationReviewFile**
> DeleteAliases200Response DeleteTeamDarApplicationReviewFile (int teamId, int id, int reviewId, string fileId)

DataAccessApplicationReview@destroyFile

Delete a file associated with a DAR review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | Dar application id |  |
| **reviewId** | **int** | Review id |  |
| **fileId** | **string** | File uuid |  |

### Return type

[**DeleteAliases200Response**](DeleteAliases200Response.md)

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

<a id="fetchteamdarapplicationreviewfile"></a>
# **FetchTeamDarApplicationReviewFile**
> void FetchTeamDarApplicationReviewFile (int teamId, int id, int reviewId, string fileId)

DataAccessApplicationReview@downloadFile

Download a file associated with a DAR application review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **reviewId** | **int** | DAR application review id |  |
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

<a id="fetchteamdarapplicationreviews"></a>
# **FetchTeamDarApplicationReviews**
> FetchTeamDarApplicationReviews200Response FetchTeamDarApplicationReviews (int teamId, int id)

DataAccessApplicationReview@index

Return all reviews on a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**FetchTeamDarApplicationReviews200Response**](FetchTeamDarApplicationReviews200Response.md)

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

<a id="fetchuserdarapplicationreviewfile"></a>
# **FetchUserDarApplicationReviewFile**
> void FetchUserDarApplicationReviewFile (int userId, int id, int reviewId, string fileId)

DataAccessApplicationReview@downloadUserFile

Download a file associated with a DAR application review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |
| **reviewId** | **int** | DAR application review id |  |
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

<a id="fetchuserdarapplicationreviews"></a>
# **FetchUserDarApplicationReviews**
> FetchTeamDarApplicationReviews200Response FetchUserDarApplicationReviews (int userId, int id)

DataAccessApplicationReview@index

Return all reviews on a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |

### Return type

[**FetchTeamDarApplicationReviews200Response**](FetchTeamDarApplicationReviews200Response.md)

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

<a id="updateteamdarapplicationquestionreview"></a>
# **UpdateTeamDarApplicationQuestionReview**
> UpdateTeamDarApplicationQuestionReview200Response UpdateTeamDarApplicationQuestionReview (int teamId, int id, int questionId, int reviewId, CreateTeamDarApplicationReviewRequest createTeamDarApplicationReviewRequest)

DataAccessApplicationReview@update

Update a review comment on a question in a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **questionId** | **int** | DAR application question id |  |
| **reviewId** | **int** | DAR application review id |  |
| **createTeamDarApplicationReviewRequest** | [**CreateTeamDarApplicationReviewRequest**](CreateTeamDarApplicationReviewRequest.md) | DataAccessApplicationReview definition |  |

### Return type

[**UpdateTeamDarApplicationQuestionReview200Response**](UpdateTeamDarApplicationQuestionReview200Response.md)

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

<a id="updateteamdarapplicationreview"></a>
# **UpdateTeamDarApplicationReview**
> UpdateTeamDarApplicationQuestionReview200Response UpdateTeamDarApplicationReview (int teamId, int id, int reviewId, CreateTeamDarApplicationReviewRequest createTeamDarApplicationReviewRequest)

DataAccessApplicationReview@updateGlobal

Update a review comment on a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **teamId** | **int** | Team id |  |
| **id** | **int** | DAR application id |  |
| **reviewId** | **int** | DAR application review id |  |
| **createTeamDarApplicationReviewRequest** | [**CreateTeamDarApplicationReviewRequest**](CreateTeamDarApplicationReviewRequest.md) | DataAccessApplicationReview definition |  |

### Return type

[**UpdateTeamDarApplicationQuestionReview200Response**](UpdateTeamDarApplicationQuestionReview200Response.md)

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

<a id="updateuserdarapplicationquestionreview"></a>
# **UpdateUserDarApplicationQuestionReview**
> UpdateTeamDarApplicationQuestionReview200Response UpdateUserDarApplicationQuestionReview (int userId, int id, int questionId, int reviewId, CreateTeamDarApplicationReviewRequest createTeamDarApplicationReviewRequest)

DataAccessApplicationReview@userUpdate

User endpoint to update a review comment on a question in a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |
| **questionId** | **int** | DAR application question id |  |
| **reviewId** | **int** | DAR application review id |  |
| **createTeamDarApplicationReviewRequest** | [**CreateTeamDarApplicationReviewRequest**](CreateTeamDarApplicationReviewRequest.md) | DataAccessApplicationReview definition |  |

### Return type

[**UpdateTeamDarApplicationQuestionReview200Response**](UpdateTeamDarApplicationQuestionReview200Response.md)

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

<a id="updateuserdarapplicationreview"></a>
# **UpdateUserDarApplicationReview**
> UpdateTeamDarApplicationQuestionReview200Response UpdateUserDarApplicationReview (int userId, int id, int reviewId, CreateTeamDarApplicationReviewRequest createTeamDarApplicationReviewRequest)

DataAccessApplicationReview@userUpdateGlobal

User endpoint to update a review comment on a DAR application


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | User id |  |
| **id** | **int** | DAR application id |  |
| **reviewId** | **int** | DAR application review id |  |
| **createTeamDarApplicationReviewRequest** | [**CreateTeamDarApplicationReviewRequest**](CreateTeamDarApplicationReviewRequest.md) | DataAccessApplicationReview definition |  |

### Return type

[**UpdateTeamDarApplicationQuestionReview200Response**](UpdateTeamDarApplicationQuestionReview200Response.md)

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

