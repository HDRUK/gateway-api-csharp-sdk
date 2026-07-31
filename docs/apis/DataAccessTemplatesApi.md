# GatewayApiSdk.Api.DataAccessTemplatesApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**DarTemplateCountUniqueFields**](DataAccessTemplatesApi.md#dartemplatecountuniquefields) | **GET** /api/v1/dar/templates/count/{field} | DataAccessTemplateController@count |

<a id="dartemplatecountuniquefields"></a>
# **DarTemplateCountUniqueFields**
> CountUniqueFieldsCollections200Response DarTemplateCountUniqueFields (string field)

DataAccessTemplateController@count

Get Counts for distinct entries of a field in the model


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **field** | **string** | name of the field to perform a count on |  |

### Return type

[**CountUniqueFieldsCollections200Response**](CountUniqueFieldsCollections200Response.md)

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

