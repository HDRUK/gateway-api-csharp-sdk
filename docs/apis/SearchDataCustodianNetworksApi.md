# GatewayApiSdk.Api.SearchDataCustodianNetworksApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**Call9b95892cc29cee3ccd11e3f92223224c**](SearchDataCustodianNetworksApi.md#call9b95892cc29cee3ccd11e3f92223224c) | **POST** /api/v1/search/data_custodian_networks | Search@data_custodian_networks |

<a id="call9b95892cc29cee3ccd11e3f92223224c"></a>
# **Call9b95892cc29cee3ccd11e3f92223224c**
> Model9b95892cc29cee3ccd11e3f92223224c200Response Call9b95892cc29cee3ccd11e3f92223224c (Model9b95892cc29cee3ccd11e3f92223224cRequest model9b95892cc29cee3ccd11e3f92223224cRequest, string sort = null, string direction = null)

Search@data_custodian_networks

Returns gateway data custodian networks related to the provided query term(s)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **model9b95892cc29cee3ccd11e3f92223224cRequest** | [**Model9b95892cc29cee3ccd11e3f92223224cRequest**](Model9b95892cc29cee3ccd11e3f92223224cRequest.md) | Submit search query |  |
| **sort** | **string** | Field to sort by (default: &#39;score&#39;) | [optional]  |
| **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | [optional]  |

### Return type

[**Model9b95892cc29cee3ccd11e3f92223224c200Response**](Model9b95892cc29cee3ccd11e3f92223224c200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

