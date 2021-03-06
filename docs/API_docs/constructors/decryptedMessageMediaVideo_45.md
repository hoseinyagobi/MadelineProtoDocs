---
title: decryptedMessageMediaVideo
description: Video attached to an encrypted message.
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: decryptedMessageMediaVideo\_45  
[Back to constructors index](index.md)



Video attached to an encrypted message.

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|thumb|[bytes](../types/bytes.md) | Yes|Content of thumbnail file (JPEG file, quality 55, set in a square 90x90)|
|thumb\_w|[int](../types/int.md) | Yes|Thumbnail width|
|thumb\_h|[int](../types/int.md) | Yes|Thumbnail height|
|duration|[int](../types/int.md) | Yes|Duration of video in seconds|
|mime\_type|[string](../types/string.md) | Yes|MIME-type of the video file<br>Parameter added in [Layer 17](https://core.telegram.org/api/layers#layer-17).|
|w|[int](../types/int.md) | Yes|Image width|
|h|[int](../types/int.md) | Yes|Image height|
|size|[int](../types/int.md) | Yes|File size|
|caption|[string](../types/string.md) | Yes|Caption|



### Type: [DecryptedMessageMedia](../types/DecryptedMessageMedia.md)


### Example:

```php
$decryptedMessageMediaVideo_45 = ['_' => 'decryptedMessageMediaVideo', 'thumb' => 'bytes', 'thumb_w' => int, 'thumb_h' => int, 'duration' => int, 'mime_type' => 'string', 'w' => int, 'h' => int, 'size' => int, 'caption' => 'string'];
```  


Or, if you're into Lua:

```lua
decryptedMessageMediaVideo_45={_='decryptedMessageMediaVideo', thumb='bytes', thumb_w=int, thumb_h=int, duration=int, mime_type='string', w=int, h=int, size=int, caption='string'}

```


