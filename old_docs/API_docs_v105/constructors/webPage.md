---
title: webPage
description: Webpage preview
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: webPage  
[Back to constructors index](index.md)



Webpage preview

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|id|[long](../types/long.md) | Yes|Preview ID|
|url|[string](../types/string.md) | Yes|URL of previewed webpage|
|display\_url|[string](../types/string.md) | Yes|Webpage URL to be displayed to the user|
|hash|[int](../types/int.md) | Yes|[Hash for pagination, for more info click here](https://core.telegram.org/api/offsets#hash-generation)|
|type|[string](../types/string.md) | Optional|Type of the web page. Can be: article, photo, audio, video, document, profile, app, or something else|
|site\_name|[string](../types/string.md) | Optional|Short name of the site (e.g., Google Docs, App Store)|
|title|[string](../types/string.md) | Optional|Title of the content|
|description|[string](../types/string.md) | Optional|Content description|
|photo|[Photo](../types/Photo.md) | Optional|Image representing the content|
|embed\_url|[string](../types/string.md) | Optional|URL to show in the embedded preview|
|embed\_type|[string](../types/string.md) | Optional|MIME type of the embedded preview, (e.g., text/html or video/mp4)|
|embed\_width|[int](../types/int.md) | Optional|Width of the embedded preview|
|embed\_height|[int](../types/int.md) | Optional|Height of the embedded preview|
|duration|[int](../types/int.md) | Optional|Duration of the content, in seconds|
|author|[string](../types/string.md) | Optional|Author of the content|
|document|[Document](../types/Document.md) | Optional|Preview of the content as a media file|
|documents|Array of [Document](../types/Document.md) | Optional|Documents|
|cached\_page|[Page](../types/Page.md) | Optional|Page contents in [instant view](https://instantview.telegram.org) format|



### Type: [WebPage](../types/WebPage.md)


### Example:

```php
$webPage = ['_' => 'webPage', 'id' => long, 'url' => 'string', 'display_url' => 'string', 'hash' => int, 'type' => 'string', 'site_name' => 'string', 'title' => 'string', 'description' => 'string', 'photo' => Photo, 'embed_url' => 'string', 'embed_type' => 'string', 'embed_width' => int, 'embed_height' => int, 'duration' => int, 'author' => 'string', 'document' => Document, 'documents' => [Document, Document], 'cached_page' => Page];
```  


Or, if you're into Lua:

```lua
webPage={_='webPage', id=long, url='string', display_url='string', hash=int, type='string', site_name='string', title='string', description='string', photo=Photo, embed_url='string', embed_type='string', embed_width=int, embed_height=int, duration=int, author='string', document=Document, documents={Document}, cached_page=Page}

```


