---
title: new_session_created
description: new_session_created attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: new\_session\_created  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|first\_msg\_id|[long](../types/long.md) | Yes|
|unique\_id|[long](../types/long.md) | Yes|
|server\_salt|[long](../types/long.md) | Yes|



### Type: [NewSession](../types/NewSession.md)


### Example:

```php
$new_session_created = ['_' => 'new_session_created', 'first_msg_id' => long, 'unique_id' => long, 'server_salt' => long];
```  


Or, if you're into Lua:

```lua
new_session_created={_='new_session_created', first_msg_id=long, unique_id=long, server_salt=long}

```


