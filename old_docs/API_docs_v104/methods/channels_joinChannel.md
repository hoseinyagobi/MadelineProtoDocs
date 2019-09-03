---
title: channels.joinChannel
description: Join a channel/supergroup
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: channels.joinChannel  
[Back to methods index](index.md)


Join a channel/supergroup

### Parameters:

| Name     |    Type       | Description | Required |
|----------|---------------|-------------|----------|
|channel|[Username, chat ID, Update, Message or InputChannel](../types/InputChannel.md) | The channel/supergroup to join | Optional|


### Return type: [Updates](../types/Updates.md)

### Can bots use this method: **NO**


### MadelineProto Example ([now async for huge speed and parallelism!](https://docs.madelineproto.xyz/docs/ASYNC.html)):


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$Updates = $MadelineProto->channels->joinChannel(['channel' => InputChannel, ]);
```

Or, if you're into Lua:

```lua
Updates = channels.joinChannel({channel=InputChannel, })
```

### Errors

| Code | Type     | Description   |
|------|----------|---------------|
|400|CHANNEL_INVALID|The provided channel is invalid|
|400|CHANNEL_PRIVATE|You haven't joined this channel/supergroup|
|400|CHANNELS_TOO_MUCH|You have joined too many channels/supergroups|
|400|INVITE_HASH_EXPIRED|The invite link has expired|
|400|INVITE_HASH_INVALID|The invite hash is invalid|
|400|USER_ALREADY_PARTICIPANT|The user is already in the group|

