# SearchRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**queries** | [**List**](Query.md) | This is a list containing the same number of queries as the number of flights for the trip. For one-way trip there should be one query, whereas for round trip there should be two queries. | [default to null]
**type** | [**TripType**](TripType.md) |  | [optional] [default to null]
**adultAmount** | [**Integer**](integer.md) | This is the number of adult passengers | [default to null]
**childAmount** | [**Integer**](integer.md) | This is the number of child passengers | [optional] [default to null]
**infantAmount** | [**Integer**](integer.md) | This is the number of infant passengers | [optional] [default to null]
**fareClass** | [**FareClass**](FareClass.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

