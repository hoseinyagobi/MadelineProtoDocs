---
title: geoPoint
description: GeoPoint.
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: geoPoint  
[Back to constructors index](index.md)



GeoPoint.

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|long|[double](../types/double.md) | Yes|Longtitude|
|lat|[double](../types/double.md) | Yes|Latitude|
|access\_hash|[long](../types/long.md) | Yes|Access hash|



### Type: [GeoPoint](../types/GeoPoint.md)


### Example:

```php
$geoPoint = ['_' => 'geoPoint', 'long' => double, 'lat' => double, 'access_hash' => long];
```  


Or, if you're into Lua:

```lua
geoPoint={_='geoPoint', long=double, lat=double, access_hash=long}

```


