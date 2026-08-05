# GatewayApiSdk.Api.LicenseApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CreateLicenses**](LicenseApi.md#createlicenses) | **POST** /api/v1/licenses | License@store |
| [**DeleteLicenses**](LicenseApi.md#deletelicenses) | **DELETE** /api/v1/licenses/{id} | License@destroy |
| [**EditLicenses**](LicenseApi.md#editlicenses) | **PATCH** /api/v1/licenses/{id} | License@edit |
| [**FetchAllLicenses**](LicenseApi.md#fetchalllicenses) | **GET** /api/v1/licenses | License@index |
| [**FetchLicenses**](LicenseApi.md#fetchlicenses) | **GET** /api/v1/licenses/{id} | License@show |
| [**UpdateLicenses**](LicenseApi.md#updatelicenses) | **PUT** /api/v1/licenses/{id} | License@update |

<a id="createlicenses"></a>
# **CreateLicenses**
> CreateDarIntegration201Response CreateLicenses (CreateLicensesRequest createLicensesRequest)

License@store

Creates a new license


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **createLicensesRequest** | [**CreateLicensesRequest**](CreateLicensesRequest.md) | License definition |  |

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

<a id="deletelicenses"></a>
# **DeleteLicenses**
> DeleteApplications200Response DeleteLicenses (int id)

License@destroy

Delete a License


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | License id |  |

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

<a id="editlicenses"></a>
# **EditLicenses**
> UpdateLicenses200Response EditLicenses (int id, CreateLicensesRequest createLicensesRequest)

License@edit

Edit a tool license


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | license id |  |
| **createLicensesRequest** | [**CreateLicensesRequest**](CreateLicensesRequest.md) | Category definition |  |

### Return type

[**UpdateLicenses200Response**](UpdateLicenses200Response.md)

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

<a id="fetchalllicenses"></a>
# **FetchAllLicenses**
> FetchAllLicenses200Response FetchAllLicenses ()

License@index

Returns a list of licenses available


### Parameters
This endpoint does not need any parameter.
### Return type

[**FetchAllLicenses200Response**](FetchAllLicenses200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="fetchlicenses"></a>
# **FetchLicenses**
> FetchLicenses200Response FetchLicenses (int id)

License@show

Return a single license


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | License ID |  |

### Return type

[**FetchLicenses200Response**](FetchLicenses200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="updatelicenses"></a>
# **UpdateLicenses**
> UpdateLicenses200Response UpdateLicenses (int id, CreateLicensesRequest createLicensesRequest)

License@update

Update a tool license


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | license id |  |
| **createLicensesRequest** | [**CreateLicensesRequest**](CreateLicensesRequest.md) | Category definition |  |

### Return type

[**UpdateLicenses200Response**](UpdateLicenses200Response.md)

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

