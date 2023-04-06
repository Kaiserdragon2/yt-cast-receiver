[yt-cast-receiver-next](../README.md) / AutoplayLoader

# Interface: AutoplayLoader

Fetches and returns the autoplay (aka 'Up Next') video for a given video.

## Implemented by

- [`DefaultAutoplayLoader`](../classes/DefaultAutoplayLoader.md)

## Table of contents

### Methods

- [getAutoplayVideoId](AutoplayLoader.md#getautoplayvideoid)

## Methods

### getAutoplayVideoId

▸ **getAutoplayVideoId**(`videoId`, `context`, `logger`): `Promise`<``null`` \| `string`\>

Fetches the autoplay video for the specified video.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `videoId` | `string` | The Id of the target video. |
| `context` | [`AutoplayLoaderContext`](AutoplayLoaderContext.md) | Additional info that might be useful. |
| `logger` | [`Logger`](Logger.md) | `Logger` implementation for logging messages. |

#### Returns

`Promise`<``null`` \| `string`\>

Promise that resolves to the Id of the autoplay video, or `null` if none obtained.

#### Defined in

lib/app/AutoplayLoader.ts:28
