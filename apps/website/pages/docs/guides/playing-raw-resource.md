# Playing Raw Resource

Discord Player natively allows you to play custom audio resource.

```js
import { createAudioResource } from '@discordjs/voice';

const queue = player.nodes.create({...}); // create guild queue
const resource = createAudioResource(...); // create audio resource

await queue.node.playRaw(resource); // play that resource
```