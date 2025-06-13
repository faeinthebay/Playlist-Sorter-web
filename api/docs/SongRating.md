# SongRating

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RatingCategory** | Pointer to [**RatingCategory**](RatingCategory.md) |  | [optional] 
**Value** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewSongRating

`func NewSongRating() *SongRating`

NewSongRating instantiates a new SongRating object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSongRatingWithDefaults

`func NewSongRatingWithDefaults() *SongRating`

NewSongRatingWithDefaults instantiates a new SongRating object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRatingCategory

`func (o *SongRating) GetRatingCategory() RatingCategory`

GetRatingCategory returns the RatingCategory field if non-nil, zero value otherwise.

### GetRatingCategoryOk

`func (o *SongRating) GetRatingCategoryOk() (*RatingCategory, bool)`

GetRatingCategoryOk returns a tuple with the RatingCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRatingCategory

`func (o *SongRating) SetRatingCategory(v RatingCategory)`

SetRatingCategory sets RatingCategory field to given value.

### HasRatingCategory

`func (o *SongRating) HasRatingCategory() bool`

HasRatingCategory returns a boolean if a field has been set.

### GetValue

`func (o *SongRating) GetValue() int32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *SongRating) GetValueOk() (*int32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *SongRating) SetValue(v int32)`

SetValue sets Value field to given value.

### HasValue

`func (o *SongRating) HasValue() bool`

HasValue returns a boolean if a field has been set.

### SetValueNil

`func (o *SongRating) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *SongRating) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


