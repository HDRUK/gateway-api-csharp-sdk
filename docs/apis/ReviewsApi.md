# GatewayApiSdk.Api.ReviewsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**DeleteReviews**](ReviewsApi.md#deletereviews) | **DELETE** /api/v1/reviews/{id} | Delete a review |
| [**EditReviews**](ReviewsApi.md#editreviews) | **PATCH** /api/v1/reviews/{id} | Edit a review |
| [**UpdateReviews**](ReviewsApi.md#updatereviews) | **PUT** /api/v1/reviews/{id} | Update a review |

<a id="deletereviews"></a>
# **DeleteReviews**
> DeleteApplications200Response DeleteReviews (int id)

Delete a review

Delete a review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | review id |  |

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

<a id="editreviews"></a>
# **EditReviews**
> UpdateReviews200Response EditReviews (int id, UpdateReviewsRequest updateReviewsRequest)

Edit a review

Edit a review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | review id |  |
| **updateReviewsRequest** | [**UpdateReviewsRequest**](UpdateReviewsRequest.md) | Pass user credentials |  |

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

<a id="updatereviews"></a>
# **UpdateReviews**
> UpdateReviews200Response UpdateReviews (int id, UpdateReviewsRequest updateReviewsRequest)

Update a review

Update a review


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | review id |  |
| **updateReviewsRequest** | [**UpdateReviewsRequest**](UpdateReviewsRequest.md) | Pass user credentials |  |

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

