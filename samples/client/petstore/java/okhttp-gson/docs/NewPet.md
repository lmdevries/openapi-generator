

# NewPet


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**id** | **Long** |  |  [optional] |
|**categoryRefToInlineAllofString** | **String** | testing allOf with a ref to string |  [optional] |
|**categoryInlineAllofString** | **String** | testing allOf with a ref to string |  [optional] |
|**categoryInlineAllof** | [**NewPetCategoryInlineAllof**](NewPetCategoryInlineAllof.md) |  |  [optional] |
|**categoryAllOfRef** | [**Category**](Category.md) |  |  [optional] |
|**categoryAllOfRefDescription** | [**Category**](Category.md) | Adding description to property using allOf  |  [optional] |
|**categoryAllOfRefDescriptionReadonly** | [**Category**](Category.md) | Adding description to readonly property using allOf  |  [optional] [readonly] |
|**name** | **String** |  |  |
|**photoUrls** | **List&lt;String&gt;** |  |  |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) |  |  [optional] |
|**status** | [**StatusEnum**](#StatusEnum) | pet status in the store |  [optional] |



## Enum: StatusEnum

| Name | Value |
|---- | -----|
| AVAILABLE | &quot;available&quot; |
| PENDING | &quot;pending&quot; |
| SOLD | &quot;sold&quot; |



