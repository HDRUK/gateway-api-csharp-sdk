# GatewayApiSdk.Api.AliasApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**AliasControllerindex**](AliasApi.md#aliascontrollerindex) | **GET** /api/v1/aliases | List of aliases |
| [**AliasControllershow**](AliasApi.md#aliascontrollershow) | **GET** /api/v1/aliases/{id} | Return a single alias |
| [**B801ec1af9f360216286166894719a1e**](AliasApi.md#b801ec1af9f360216286166894719a1e) | **PUT** /api/v1/aliases/{id} | AliasController@update |
| [**C29b5b3424f7317b69b4bda048ccfafb**](AliasApi.md#c29b5b3424f7317b69b4bda048ccfafb) | **DELETE** /api/v1/aliases/{id} | AliasController@destroy |
| [**Call079b2d545c7f4705016912f5de1bf444**](AliasApi.md#call079b2d545c7f4705016912f5de1bf444) | **POST** /api/v1/aliases | AliasController@store |
| [**E93f53867884432d9a6b592066431af3**](AliasApi.md#e93f53867884432d9a6b592066431af3) | **PATCH** /api/v1/aliases/{id} | AliasController@edit |

<a id="aliascontrollerindex"></a>
# **AliasControllerindex**
> AliasControllerIndex200Response AliasControllerindex ()

List of aliases

Returns a list of aliases


### Parameters
This endpoint does not need any parameter.
### Return type

[**AliasControllerIndex200Response**](AliasControllerIndex200Response.md)

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

<a id="aliascontrollershow"></a>
# **AliasControllershow**
> AliasControllerShow200Response AliasControllershow (int id)

Return a single alias

Return a single alias


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | alias id |  |

### Return type

[**AliasControllerShow200Response**](AliasControllerShow200Response.md)

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

<a id="b801ec1af9f360216286166894719a1e"></a>
# **B801ec1af9f360216286166894719a1e**
> B801ec1af9f360216286166894719a1e200Response B801ec1af9f360216286166894719a1e (int id, Model079b2d545c7f4705016912f5de1bf444Request model079b2d545c7f4705016912f5de1bf444Request)

AliasController@update

Update a alias


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | alias id |  |
| **model079b2d545c7f4705016912f5de1bf444Request** | [**Model079b2d545c7f4705016912f5de1bf444Request**](Model079b2d545c7f4705016912f5de1bf444Request.md) | Alias definition |  |

### Return type

[**B801ec1af9f360216286166894719a1e200Response**](B801ec1af9f360216286166894719a1e200Response.md)

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

<a id="c29b5b3424f7317b69b4bda048ccfafb"></a>
# **C29b5b3424f7317b69b4bda048ccfafb**
> C29b5b3424f7317b69b4bda048ccfafb200Response C29b5b3424f7317b69b4bda048ccfafb (int id)

AliasController@destroy

Delete an alias


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | alias id |  |

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

<a id="call079b2d545c7f4705016912f5de1bf444"></a>
# **Call079b2d545c7f4705016912f5de1bf444**
> Model079b2d545c7f4705016912f5de1bf444200Response Call079b2d545c7f4705016912f5de1bf444 (Model079b2d545c7f4705016912f5de1bf444Request model079b2d545c7f4705016912f5de1bf444Request)

AliasController@store

Creates a new alias


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model079b2d545c7f4705016912f5de1bf444Request** | [**Model079b2d545c7f4705016912f5de1bf444Request**](Model079b2d545c7f4705016912f5de1bf444Request.md) | Alias definition |  |

### Return type

[**Model079b2d545c7f4705016912f5de1bf444200Response**](Model079b2d545c7f4705016912f5de1bf444200Response.md)

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

<a id="e93f53867884432d9a6b592066431af3"></a>
# **E93f53867884432d9a6b592066431af3**
> B801ec1af9f360216286166894719a1e200Response E93f53867884432d9a6b592066431af3 (int id, E93f53867884432d9a6b592066431af3Request e93f53867884432d9a6b592066431af3Request)

AliasController@edit

Edit a alias


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | alias id |  |
| **e93f53867884432d9a6b592066431af3Request** | [**E93f53867884432d9a6b592066431af3Request**](E93f53867884432d9a6b592066431af3Request.md) | Alias definition |  |

### Return type

[**B801ec1af9f360216286166894719a1e200Response**](B801ec1af9f360216286166894719a1e200Response.md)

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

