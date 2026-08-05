# GatewayApiSdk.Api.LicenseApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**FetchAllLicenses**](LicenseApi.md#fetchalllicenses) | **GET** /api/v1/licenses | License@index |
| [**FetchLicenses**](LicenseApi.md#fetchlicenses) | **GET** /api/v1/licenses/{id} | License@show |

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

