# GatewayApiSdk.Api.ReviewsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call205dc23d44b18ca0b5c26a293cc69cf7**](ReviewsApi.md#call205dc23d44b18ca0b5c26a293cc69cf7) | **DELETE** /api/v1/reviews/{id} | Delete a review |
| [**Call31ad2467e98e52298b4e39e2741447f1**](ReviewsApi.md#call31ad2467e98e52298b4e39e2741447f1) | **PATCH** /api/v1/reviews/{id} | Edit a review |
| [**Call64b4b952592ebe8e0b00204e76bd991c**](ReviewsApi.md#call64b4b952592ebe8e0b00204e76bd991c) | **PUT** /api/v1/reviews/{id} | Update a review |
| [**CreateReviews**](ReviewsApi.md#createreviews) | **POST** /api/v1/reviews | ReviewController@store |
| [**FetchAllReviews**](ReviewsApi.md#fetchallreviews) | **GET** /api/v1/reviews | ReviewController@index |
| [**FetchReviews**](ReviewsApi.md#fetchreviews) | **GET** /api/v1/reviews/{id} | ReviewController@show |

<a id="call205dc23d44b18ca0b5c26a293cc69cf7"></a>
# **Call205dc23d44b18ca0b5c26a293cc69cf7**
> C29b5b3424f7317b69b4bda048ccfafb200Response Call205dc23d44b18ca0b5c26a293cc69cf7 (int id)

Delete a review

Delete a review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | review id |  |

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

<a id="call31ad2467e98e52298b4e39e2741447f1"></a>
# **Call31ad2467e98e52298b4e39e2741447f1**
> Model64b4b952592ebe8e0b00204e76bd991c200Response Call31ad2467e98e52298b4e39e2741447f1 (int id, CreateReviewsRequest createReviewsRequest)

Edit a review

Edit a review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | review id |  |
| **createReviewsRequest** | [**CreateReviewsRequest**](CreateReviewsRequest.md) | Pass user credentials |  |

### Return type

[**Model64b4b952592ebe8e0b00204e76bd991c200Response**](Model64b4b952592ebe8e0b00204e76bd991c200Response.md)

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

<a id="call64b4b952592ebe8e0b00204e76bd991c"></a>
# **Call64b4b952592ebe8e0b00204e76bd991c**
> Model64b4b952592ebe8e0b00204e76bd991c200Response Call64b4b952592ebe8e0b00204e76bd991c (int id, CreateReviewsRequest createReviewsRequest)

Update a review

Update a review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | review id |  |
| **createReviewsRequest** | [**CreateReviewsRequest**](CreateReviewsRequest.md) | Pass user credentials |  |

### Return type

[**Model64b4b952592ebe8e0b00204e76bd991c200Response**](Model64b4b952592ebe8e0b00204e76bd991c200Response.md)

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

<a id="createreviews"></a>
# **CreateReviews**
> Dd76b8d73b7ea8b4951f03d7c0904c92200Response CreateReviews (CreateReviewsRequest createReviewsRequest)

ReviewController@store

Create a new review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createReviewsRequest** | [**CreateReviewsRequest**](CreateReviewsRequest.md) | Pass user credentials |  |

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

