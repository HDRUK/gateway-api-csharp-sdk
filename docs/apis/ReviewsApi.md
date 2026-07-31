# GatewayApiSdk.Api.ReviewsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateReviews**](ReviewsApi.md#createreviews) | **POST** /api/v1/reviews | ReviewController@store |
| [**DeleteReviews**](ReviewsApi.md#deletereviews) | **DELETE** /api/v1/reviews/{id} | Delete a review |
| [**EditReviews**](ReviewsApi.md#editreviews) | **PATCH** /api/v1/reviews/{id} | Edit a review |
| [**FetchAllReviews**](ReviewsApi.md#fetchallreviews) | **GET** /api/v1/reviews | ReviewController@index |
| [**FetchReviews**](ReviewsApi.md#fetchreviews) | **GET** /api/v1/reviews/{id} | ReviewController@show |
| [**UpdateReviews**](ReviewsApi.md#updatereviews) | **PUT** /api/v1/reviews/{id} | Update a review |

<a id="createreviews"></a>
# **CreateReviews**
> CreateCategories200Response CreateReviews (CreateReviewsRequest createReviewsRequest)

ReviewController@store

Create a new review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createReviewsRequest** | [**CreateReviewsRequest**](CreateReviewsRequest.md) | Pass user credentials |  |

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
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="deletereviews"></a>
# **DeleteReviews**
> DeleteAliases200Response DeleteReviews (int id)

Delete a review

Delete a review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | review id |  |

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

<a id="editreviews"></a>
# **EditReviews**
> UpdateReviews200Response EditReviews (int id, CreateReviewsRequest createReviewsRequest)

Edit a review

Edit a review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | review id |  |
| **createReviewsRequest** | [**CreateReviewsRequest**](CreateReviewsRequest.md) | Pass user credentials |  |

### Return type

[**UpdateReviews200Response**](UpdateReviews200Response.md)

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

<a id="fetchallreviews"></a>
# **FetchAllReviews**
> FetchAllReviews200Response FetchAllReviews ()

ReviewController@index

Get All Reviews


### Parameters
This endpoint does not need any parameter.
### Return type

[**FetchAllReviews200Response**](FetchAllReviews200Response.md)

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

<a id="fetchreviews"></a>
# **FetchReviews**
> FetchAllReviews200Response FetchReviews (int id)

ReviewController@show

Get review by id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | review id |  |

### Return type

[**FetchAllReviews200Response**](FetchAllReviews200Response.md)

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

<a id="updatereviews"></a>
# **UpdateReviews**
> UpdateReviews200Response UpdateReviews (int id, CreateReviewsRequest createReviewsRequest)

Update a review

Update a review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | review id |  |
| **createReviewsRequest** | [**CreateReviewsRequest**](CreateReviewsRequest.md) | Pass user credentials |  |

### Return type

[**UpdateReviews200Response**](UpdateReviews200Response.md)

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

