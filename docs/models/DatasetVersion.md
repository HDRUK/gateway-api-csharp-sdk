# GatewayApiSdk.Model.DatasetVersion
A versioned snapshot of dataset metadata in GWDM format

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int** |  | [optional] 
**DatasetId** | **int** |  | [optional] 
**VarVersion** | **int** |  | [optional] 
**Title** | **string** |  | [optional] 
**ShortTitle** | **string** |  | [optional] 
**Metadata** | **Object** | Full GWDM-format metadata document for this version | [optional] 
**Patch** | **List&lt;Object&gt;** | RFC 6902 JSON Patch array used to reconstruct this version from the previous snapshot. Null for full snapshots (v1 and every 10th version). | [optional] 
**CreatedAt** | **DateTime** |  | [optional] 
**UpdatedAt** | **DateTime** |  | [optional] 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

