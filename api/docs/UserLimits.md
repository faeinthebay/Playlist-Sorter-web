# UserLimits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tier** | Pointer to **string** | The user&#39;s allowance tier. | [optional] 
**TierExpiration** | Pointer to **NullableTime** | The date and time when a user&#39;s account will be downgraded if payment is not made. | [optional] 
**AutoRenewEnabled** | Pointer to **bool** |  | [optional] 
**IsRestricted** | Pointer to **bool** | Whether an account is being restricted (by exceeding a quota after an allowance changes). | [optional] 
**LoadedSongs** | Pointer to **int32** |  | [optional] 
**MaximumSongs** | Pointer to **int32** | Maximum number of unique songs linked to playlists in a user&#39;s account.  One unique song can be linked to multiple song entires per streaming service.  0 indicates unlimited. | [optional] 
**LoadedPlaylists** | Pointer to **int32** |  | [optional] 
**MaximumPlaylists** | Pointer to **int32** | Maximum number of playlists loaded to a user&#39;s account.  One playlist can be linked to multiple services.  0 indicates unlimited. | [optional] 
**MaximumPlaylistLength** | Pointer to **int32** |  | [optional] 

## Methods

### NewUserLimits

`func NewUserLimits() *UserLimits`

NewUserLimits instantiates a new UserLimits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserLimitsWithDefaults

`func NewUserLimitsWithDefaults() *UserLimits`

NewUserLimitsWithDefaults instantiates a new UserLimits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTier

`func (o *UserLimits) GetTier() string`

GetTier returns the Tier field if non-nil, zero value otherwise.

### GetTierOk

`func (o *UserLimits) GetTierOk() (*string, bool)`

GetTierOk returns a tuple with the Tier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTier

`func (o *UserLimits) SetTier(v string)`

SetTier sets Tier field to given value.

### HasTier

`func (o *UserLimits) HasTier() bool`

HasTier returns a boolean if a field has been set.

### GetTierExpiration

`func (o *UserLimits) GetTierExpiration() time.Time`

GetTierExpiration returns the TierExpiration field if non-nil, zero value otherwise.

### GetTierExpirationOk

`func (o *UserLimits) GetTierExpirationOk() (*time.Time, bool)`

GetTierExpirationOk returns a tuple with the TierExpiration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTierExpiration

`func (o *UserLimits) SetTierExpiration(v time.Time)`

SetTierExpiration sets TierExpiration field to given value.

### HasTierExpiration

`func (o *UserLimits) HasTierExpiration() bool`

HasTierExpiration returns a boolean if a field has been set.

### SetTierExpirationNil

`func (o *UserLimits) SetTierExpirationNil(b bool)`

 SetTierExpirationNil sets the value for TierExpiration to be an explicit nil

### UnsetTierExpiration
`func (o *UserLimits) UnsetTierExpiration()`

UnsetTierExpiration ensures that no value is present for TierExpiration, not even an explicit nil
### GetAutoRenewEnabled

`func (o *UserLimits) GetAutoRenewEnabled() bool`

GetAutoRenewEnabled returns the AutoRenewEnabled field if non-nil, zero value otherwise.

### GetAutoRenewEnabledOk

`func (o *UserLimits) GetAutoRenewEnabledOk() (*bool, bool)`

GetAutoRenewEnabledOk returns a tuple with the AutoRenewEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoRenewEnabled

`func (o *UserLimits) SetAutoRenewEnabled(v bool)`

SetAutoRenewEnabled sets AutoRenewEnabled field to given value.

### HasAutoRenewEnabled

`func (o *UserLimits) HasAutoRenewEnabled() bool`

HasAutoRenewEnabled returns a boolean if a field has been set.

### GetIsRestricted

`func (o *UserLimits) GetIsRestricted() bool`

GetIsRestricted returns the IsRestricted field if non-nil, zero value otherwise.

### GetIsRestrictedOk

`func (o *UserLimits) GetIsRestrictedOk() (*bool, bool)`

GetIsRestrictedOk returns a tuple with the IsRestricted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRestricted

`func (o *UserLimits) SetIsRestricted(v bool)`

SetIsRestricted sets IsRestricted field to given value.

### HasIsRestricted

`func (o *UserLimits) HasIsRestricted() bool`

HasIsRestricted returns a boolean if a field has been set.

### GetLoadedSongs

`func (o *UserLimits) GetLoadedSongs() int32`

GetLoadedSongs returns the LoadedSongs field if non-nil, zero value otherwise.

### GetLoadedSongsOk

`func (o *UserLimits) GetLoadedSongsOk() (*int32, bool)`

GetLoadedSongsOk returns a tuple with the LoadedSongs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadedSongs

`func (o *UserLimits) SetLoadedSongs(v int32)`

SetLoadedSongs sets LoadedSongs field to given value.

### HasLoadedSongs

`func (o *UserLimits) HasLoadedSongs() bool`

HasLoadedSongs returns a boolean if a field has been set.

### GetMaximumSongs

`func (o *UserLimits) GetMaximumSongs() int32`

GetMaximumSongs returns the MaximumSongs field if non-nil, zero value otherwise.

### GetMaximumSongsOk

`func (o *UserLimits) GetMaximumSongsOk() (*int32, bool)`

GetMaximumSongsOk returns a tuple with the MaximumSongs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumSongs

`func (o *UserLimits) SetMaximumSongs(v int32)`

SetMaximumSongs sets MaximumSongs field to given value.

### HasMaximumSongs

`func (o *UserLimits) HasMaximumSongs() bool`

HasMaximumSongs returns a boolean if a field has been set.

### GetLoadedPlaylists

`func (o *UserLimits) GetLoadedPlaylists() int32`

GetLoadedPlaylists returns the LoadedPlaylists field if non-nil, zero value otherwise.

### GetLoadedPlaylistsOk

`func (o *UserLimits) GetLoadedPlaylistsOk() (*int32, bool)`

GetLoadedPlaylistsOk returns a tuple with the LoadedPlaylists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadedPlaylists

`func (o *UserLimits) SetLoadedPlaylists(v int32)`

SetLoadedPlaylists sets LoadedPlaylists field to given value.

### HasLoadedPlaylists

`func (o *UserLimits) HasLoadedPlaylists() bool`

HasLoadedPlaylists returns a boolean if a field has been set.

### GetMaximumPlaylists

`func (o *UserLimits) GetMaximumPlaylists() int32`

GetMaximumPlaylists returns the MaximumPlaylists field if non-nil, zero value otherwise.

### GetMaximumPlaylistsOk

`func (o *UserLimits) GetMaximumPlaylistsOk() (*int32, bool)`

GetMaximumPlaylistsOk returns a tuple with the MaximumPlaylists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumPlaylists

`func (o *UserLimits) SetMaximumPlaylists(v int32)`

SetMaximumPlaylists sets MaximumPlaylists field to given value.

### HasMaximumPlaylists

`func (o *UserLimits) HasMaximumPlaylists() bool`

HasMaximumPlaylists returns a boolean if a field has been set.

### GetMaximumPlaylistLength

`func (o *UserLimits) GetMaximumPlaylistLength() int32`

GetMaximumPlaylistLength returns the MaximumPlaylistLength field if non-nil, zero value otherwise.

### GetMaximumPlaylistLengthOk

`func (o *UserLimits) GetMaximumPlaylistLengthOk() (*int32, bool)`

GetMaximumPlaylistLengthOk returns a tuple with the MaximumPlaylistLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumPlaylistLength

`func (o *UserLimits) SetMaximumPlaylistLength(v int32)`

SetMaximumPlaylistLength sets MaximumPlaylistLength field to given value.

### HasMaximumPlaylistLength

`func (o *UserLimits) HasMaximumPlaylistLength() bool`

HasMaximumPlaylistLength returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


