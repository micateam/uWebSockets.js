<div align="center">
<img src="https://raw.githubusercontent.com/uNetworking/uWebSockets/master/misc/logo.svg" height="180" /><br>
<br>
</div>

We aren't in the NPM registry but you can easily install it with the NPM client:
* `npm install uNetworking/uWebSockets.js#v20.48.0`


### :dart: The right approach

```
// npm install uNetworking/uWebSockets.js#latest package.json->type:module
import uWS from 'uWebSockets.js';
const port = 9001;

const redis = require('redis');
import { createClient } from 'redis';
const useRedis = createClient();
useRedis.connect();
```
