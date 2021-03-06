---
title: messages.getFullChat
description: You cannot use this method directly, use the getPwrChat, getInfo, getFullInfo methods instead (see https://docs.madelineproto.xyz for more info)
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
redirect_from: /API_docs/methods/messages_getFullChat.html
---
# Method: messages.getFullChat  
[Back to methods index](index.md)


You cannot use this method directly, use the getPwrChat, getInfo, getFullInfo methods instead (see https://docs.madelineproto.xyz for more info)

### Parameters:

| Name     |    Type       | Description | Required |
|----------|---------------|-------------|----------|
|chat\_id|[Username, chat ID, Update, Message or InputPeer](../types/InputPeer.md) | You cannot use this method directly, use the getPwrChat, getInfo, getFullInfo methods instead (see https://docs.madelineproto.xyz for more info) | Optional|


### Return type: [messages.ChatFull](../types/messages.ChatFull.md)

### Can bots use this method: **YES**


### MadelineProto Example ([now async for huge speed and parallelism!](https://docs.madelineproto.xyz/docs/ASYNC.html)):


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$messages.ChatFull = $MadelineProto->messages->getFullChat(['chat_id' => InputPeer, ]);
```

Or, if you're into Lua:

```lua
messages.ChatFull = messages.getFullChat({chat_id=InputPeer, })
```

### Errors

| Code | Type     | Description   |
|------|----------|---------------|
|400|CHAT_ID_INVALID|The provided chat id is invalid|
|400|PEER_ID_INVALID|The provided peer id is invalid|


