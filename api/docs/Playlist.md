# Playlist

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**InternalID** | Pointer to **string** |  | [optional] 
**SpotPlaylistID** | Pointer to **NullableString** |  | [optional] 
**YTMPlaylistID** | Pointer to **NullableString** |  | [optional] 
**ApplPlaylistID** | Pointer to **NullableInt32** |  | [optional] 
**SourceOfTruth** | Pointer to [**PrimaryService**](PrimaryService.md) | Decides which service is the \&quot;source of truth\&quot;, whose changes are propogated to playlists in other services.  The services that are not sources of truth will have their changes ignored then overwritten. | [optional] 
**ImportDate** | Pointer to **time.Time** |  | [optional] 
**LastUpdated** | Pointer to **time.Time** |  | [optional] 
**IsLoading** | Pointer to **bool** | Whether playlist and song metadata are still being imported | [optional] 
**Songs** | Pointer to **[][]interface{}** |  | [optional] 

## Methods

### NewPlaylist

`func NewPlaylist() *Playlist`

NewPlaylist instantiates a new Playlist object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlaylistWithDefaults

`func NewPlaylistWithDefaults() *Playlist`

NewPlaylistWithDefaults instantiates a new Playlist object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *Playlist) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Playlist) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Playlist) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Playlist) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *Playlist) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Playlist) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Playlist) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Playlist) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *Playlist) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *Playlist) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetInternalID

`func (o *Playlist) GetInternalID() string`

GetInternalID returns the InternalID field if non-nil, zero value otherwise.

### GetInternalIDOk

`func (o *Playlist) GetInternalIDOk() (*string, bool)`

GetInternalIDOk returns a tuple with the InternalID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternalID

`func (o *Playlist) SetInternalID(v string)`

SetInternalID sets InternalID field to given value.

### HasInternalID

`func (o *Playlist) HasInternalID() bool`

HasInternalID returns a boolean if a field has been set.

### GetSpotPlaylistID

`func (o *Playlist) GetSpotPlaylistID() string`

GetSpotPlaylistID returns the SpotPlaylistID field if non-nil, zero value otherwise.

### GetSpotPlaylistIDOk

`func (o *Playlist) GetSpotPlaylistIDOk() (*string, bool)`

GetSpotPlaylistIDOk returns a tuple with the SpotPlaylistID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpotPlaylistID

`func (o *Playlist) SetSpotPlaylistID(v string)`

SetSpotPlaylistID sets SpotPlaylistID field to given value.

### HasSpotPlaylistID

`func (o *Playlist) HasSpotPlaylistID() bool`

HasSpotPlaylistID returns a boolean if a field has been set.

### SetSpotPlaylistIDNil

`func (o *Playlist) SetSpotPlaylistIDNil(b bool)`

 SetSpotPlaylistIDNil sets the value for SpotPlaylistID to be an explicit nil

### UnsetSpotPlaylistID
`func (o *Playlist) UnsetSpotPlaylistID()`

UnsetSpotPlaylistID ensures that no value is present for SpotPlaylistID, not even an explicit nil
### GetYTMPlaylistID

`func (o *Playlist) GetYTMPlaylistID() string`

GetYTMPlaylistID returns the YTMPlaylistID field if non-nil, zero value otherwise.

### GetYTMPlaylistIDOk

`func (o *Playlist) GetYTMPlaylistIDOk() (*string, bool)`

GetYTMPlaylistIDOk returns a tuple with the YTMPlaylistID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYTMPlaylistID

`func (o *Playlist) SetYTMPlaylistID(v string)`

SetYTMPlaylistID sets YTMPlaylistID field to given value.

### HasYTMPlaylistID

`func (o *Playlist) HasYTMPlaylistID() bool`

HasYTMPlaylistID returns a boolean if a field has been set.

### SetYTMPlaylistIDNil

`func (o *Playlist) SetYTMPlaylistIDNil(b bool)`

 SetYTMPlaylistIDNil sets the value for YTMPlaylistID to be an explicit nil

### UnsetYTMPlaylistID
`func (o *Playlist) UnsetYTMPlaylistID()`

UnsetYTMPlaylistID ensures that no value is present for YTMPlaylistID, not even an explicit nil
### GetApplPlaylistID

`func (o *Playlist) GetApplPlaylistID() int32`

GetApplPlaylistID returns the ApplPlaylistID field if non-nil, zero value otherwise.

### GetApplPlaylistIDOk

`func (o *Playlist) GetApplPlaylistIDOk() (*int32, bool)`

GetApplPlaylistIDOk returns a tuple with the ApplPlaylistID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplPlaylistID

`func (o *Playlist) SetApplPlaylistID(v int32)`

SetApplPlaylistID sets ApplPlaylistID field to given value.

### HasApplPlaylistID

`func (o *Playlist) HasApplPlaylistID() bool`

HasApplPlaylistID returns a boolean if a field has been set.

### SetApplPlaylistIDNil

`func (o *Playlist) SetApplPlaylistIDNil(b bool)`

 SetApplPlaylistIDNil sets the value for ApplPlaylistID to be an explicit nil

### UnsetApplPlaylistID
`func (o *Playlist) UnsetApplPlaylistID()`

UnsetApplPlaylistID ensures that no value is present for ApplPlaylistID, not even an explicit nil
### GetSourceOfTruth

`func (o *Playlist) GetSourceOfTruth() PrimaryService`

GetSourceOfTruth returns the SourceOfTruth field if non-nil, zero value otherwise.

### GetSourceOfTruthOk

`func (o *Playlist) GetSourceOfTruthOk() (*PrimaryService, bool)`

GetSourceOfTruthOk returns a tuple with the SourceOfTruth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceOfTruth

`func (o *Playlist) SetSourceOfTruth(v PrimaryService)`

SetSourceOfTruth sets SourceOfTruth field to given value.

### HasSourceOfTruth

`func (o *Playlist) HasSourceOfTruth() bool`

HasSourceOfTruth returns a boolean if a field has been set.

### GetImportDate

`func (o *Playlist) GetImportDate() time.Time`

GetImportDate returns the ImportDate field if non-nil, zero value otherwise.

### GetImportDateOk

`func (o *Playlist) GetImportDateOk() (*time.Time, bool)`

GetImportDateOk returns a tuple with the ImportDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportDate

`func (o *Playlist) SetImportDate(v time.Time)`

SetImportDate sets ImportDate field to given value.

### HasImportDate

`func (o *Playlist) HasImportDate() bool`

HasImportDate returns a boolean if a field has been set.

### GetLastUpdated

`func (o *Playlist) GetLastUpdated() time.Time`

GetLastUpdated returns the LastUpdated field if non-nil, zero value otherwise.

### GetLastUpdatedOk

`func (o *Playlist) GetLastUpdatedOk() (*time.Time, bool)`

GetLastUpdatedOk returns a tuple with the LastUpdated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdated

`func (o *Playlist) SetLastUpdated(v time.Time)`

SetLastUpdated sets LastUpdated field to given value.

### HasLastUpdated

`func (o *Playlist) HasLastUpdated() bool`

HasLastUpdated returns a boolean if a field has been set.

### GetIsLoading

`func (o *Playlist) GetIsLoading() bool`

GetIsLoading returns the IsLoading field if non-nil, zero value otherwise.

### GetIsLoadingOk

`func (o *Playlist) GetIsLoadingOk() (*bool, bool)`

GetIsLoadingOk returns a tuple with the IsLoading field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsLoading

`func (o *Playlist) SetIsLoading(v bool)`

SetIsLoading sets IsLoading field to given value.

### HasIsLoading

`func (o *Playlist) HasIsLoading() bool`

HasIsLoading returns a boolean if a field has been set.

### GetSongs

`func (o *Playlist) GetSongs() [][]interface{}`

GetSongs returns the Songs field if non-nil, zero value otherwise.

### GetSongsOk

`func (o *Playlist) GetSongsOk() (*[][]interface{}, bool)`

GetSongsOk returns a tuple with the Songs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSongs

`func (o *Playlist) SetSongs(v [][]interface{})`

SetSongs sets Songs field to given value.

### HasSongs

`func (o *Playlist) HasSongs() bool`

HasSongs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


