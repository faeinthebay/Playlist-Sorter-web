# Song

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | Pointer to **string** |  | [optional] 
**Artist** | Pointer to **string** |  | [optional] 
**LengthSeconds** | Pointer to **int32** | Length of song in seconds (rounded when provided in milliseconds) | [optional] 
**SpotSongIDs** | Pointer to **[]string** |  | [optional] 
**ApplSongIDs** | Pointer to **[]int32** |  | [optional] 
**YTMSongIDs** | Pointer to **[]string** |  | [optional] 

## Methods

### NewSong

`func NewSong() *Song`

NewSong instantiates a new Song object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSongWithDefaults

`func NewSongWithDefaults() *Song`

NewSongWithDefaults instantiates a new Song object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *Song) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Song) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Song) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *Song) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetArtist

`func (o *Song) GetArtist() string`

GetArtist returns the Artist field if non-nil, zero value otherwise.

### GetArtistOk

`func (o *Song) GetArtistOk() (*string, bool)`

GetArtistOk returns a tuple with the Artist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtist

`func (o *Song) SetArtist(v string)`

SetArtist sets Artist field to given value.

### HasArtist

`func (o *Song) HasArtist() bool`

HasArtist returns a boolean if a field has been set.

### GetLengthSeconds

`func (o *Song) GetLengthSeconds() int32`

GetLengthSeconds returns the LengthSeconds field if non-nil, zero value otherwise.

### GetLengthSecondsOk

`func (o *Song) GetLengthSecondsOk() (*int32, bool)`

GetLengthSecondsOk returns a tuple with the LengthSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLengthSeconds

`func (o *Song) SetLengthSeconds(v int32)`

SetLengthSeconds sets LengthSeconds field to given value.

### HasLengthSeconds

`func (o *Song) HasLengthSeconds() bool`

HasLengthSeconds returns a boolean if a field has been set.

### GetSpotSongIDs

`func (o *Song) GetSpotSongIDs() []string`

GetSpotSongIDs returns the SpotSongIDs field if non-nil, zero value otherwise.

### GetSpotSongIDsOk

`func (o *Song) GetSpotSongIDsOk() (*[]string, bool)`

GetSpotSongIDsOk returns a tuple with the SpotSongIDs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpotSongIDs

`func (o *Song) SetSpotSongIDs(v []string)`

SetSpotSongIDs sets SpotSongIDs field to given value.

### HasSpotSongIDs

`func (o *Song) HasSpotSongIDs() bool`

HasSpotSongIDs returns a boolean if a field has been set.

### GetApplSongIDs

`func (o *Song) GetApplSongIDs() []int32`

GetApplSongIDs returns the ApplSongIDs field if non-nil, zero value otherwise.

### GetApplSongIDsOk

`func (o *Song) GetApplSongIDsOk() (*[]int32, bool)`

GetApplSongIDsOk returns a tuple with the ApplSongIDs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplSongIDs

`func (o *Song) SetApplSongIDs(v []int32)`

SetApplSongIDs sets ApplSongIDs field to given value.

### HasApplSongIDs

`func (o *Song) HasApplSongIDs() bool`

HasApplSongIDs returns a boolean if a field has been set.

### GetYTMSongIDs

`func (o *Song) GetYTMSongIDs() []string`

GetYTMSongIDs returns the YTMSongIDs field if non-nil, zero value otherwise.

### GetYTMSongIDsOk

`func (o *Song) GetYTMSongIDsOk() (*[]string, bool)`

GetYTMSongIDsOk returns a tuple with the YTMSongIDs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYTMSongIDs

`func (o *Song) SetYTMSongIDs(v []string)`

SetYTMSongIDs sets YTMSongIDs field to given value.

### HasYTMSongIDs

`func (o *Song) HasYTMSongIDs() bool`

HasYTMSongIDs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


