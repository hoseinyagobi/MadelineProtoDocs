---
title: userProfilePhoto
description: User profile photo.
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: userProfilePhoto  
[Back to constructors index](index.md)



User profile photo.

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|photo\_id|[long](../types/long.md) | Yes|Identifier of the respective photo<br>Parameter added in [Layer 2](https://core.telegram.org/api/layers#layer-2)|
|photo\_small|[FileLocation](../types/FileLocation.md) | Yes|Location of the file, corresponding to the small profile photo thumbnail|
|photo\_big|[FileLocation](../types/FileLocation.md) | Yes|Location of the file, corresponding to the big profile photo thumbnail|



### Type: [UserProfilePhoto](../types/UserProfilePhoto.md)


### Example:

```php
$userProfilePhoto = ['_' => 'userProfilePhoto', 'photo_id' => long, 'photo_small' => FileLocation, 'photo_big' => FileLocation];
```  


Or, if you're into Lua:

```lua
userProfilePhoto={_='userProfilePhoto', photo_id=long, photo_small=FileLocation, photo_big=FileLocation}

```


