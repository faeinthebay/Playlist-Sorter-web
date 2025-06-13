# UserPrefs

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UseSingleSongRating** | Pointer to **bool** | Uses the same ratings for a song across all user playlists. | [optional] 
**CopySongRatingSource** | Pointer to **string** | If Single Song Ratings are disabled, should a new playlist copy ratings from the newest imported playlist, oldest imported playlist, or not copy ratings at all? | [optional] 

## Methods

### NewUserPrefs

`func NewUserPrefs() *UserPrefs`

NewUserPrefs instantiates a new UserPrefs object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserPrefsWithDefaults

`func NewUserPrefsWithDefaults() *UserPrefs`

NewUserPrefsWithDefaults instantiates a new UserPrefs object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUseSingleSongRating

`func (o *UserPrefs) GetUseSingleSongRating() bool`

GetUseSingleSongRating returns the UseSingleSongRating field if non-nil, zero value otherwise.

### GetUseSingleSongRatingOk

`func (o *UserPrefs) GetUseSingleSongRatingOk() (*bool, bool)`

GetUseSingleSongRatingOk returns a tuple with the UseSingleSongRating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseSingleSongRating

`func (o *UserPrefs) SetUseSingleSongRating(v bool)`

SetUseSingleSongRating sets UseSingleSongRating field to given value.

### HasUseSingleSongRating

`func (o *UserPrefs) HasUseSingleSongRating() bool`

HasUseSingleSongRating returns a boolean if a field has been set.

### GetCopySongRatingSource

`func (o *UserPrefs) GetCopySongRatingSource() string`

GetCopySongRatingSource returns the CopySongRatingSource field if non-nil, zero value otherwise.

### GetCopySongRatingSourceOk

`func (o *UserPrefs) GetCopySongRatingSourceOk() (*string, bool)`

GetCopySongRatingSourceOk returns a tuple with the CopySongRatingSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCopySongRatingSource

`func (o *UserPrefs) SetCopySongRatingSource(v string)`

SetCopySongRatingSource sets CopySongRatingSource field to given value.

### HasCopySongRatingSource

`func (o *UserPrefs) HasCopySongRatingSource() bool`

HasCopySongRatingSource returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


