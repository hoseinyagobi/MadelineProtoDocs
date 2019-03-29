---
title: account.saveAutoDownloadSettings
description: Save autodownload settings
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: account.saveAutoDownloadSettings  
[Back to methods index](index.md)


Save autodownload settings

### Parameters:

| Name     |    Type       | Description | Required |
|----------|---------------|-------------|----------|
|low|[Bool](../types/Bool.md) | Low preset | Optional|
|high|[Bool](../types/Bool.md) | High preset | Optional|
|settings|[AutoDownloadSettings](../types/AutoDownloadSettings.md) | Autodownload settings | Yes|


### Return type: [Bool](../types/Bool.md)

### Can bots use this method: **YES**


### MadelineProto Example:


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
define('MADELINE_BRANCH', '');
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$Bool = $MadelineProto->account->saveAutoDownloadSettings(['low' => Bool, 'high' => Bool, 'settings' => AutoDownloadSettings, ]);
```

Or, if you're into Lua:

```lua
Bool = account.saveAutoDownloadSettings({low=Bool, high=Bool, settings=AutoDownloadSettings, })
```
