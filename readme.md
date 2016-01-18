# google-proto-files
> Get a copy of the [googleapis](https://github.com/google/google-api-nodejs-client) proto files into your project

```sh
$ npm install --save google-proto-files
```
```js
var protoFiles = require('google-proto-files')
```

### Get a directory path by executing as a function
```js
protoFiles('logging', 'v2')
// node_modules/google-proto-files/google/logging/v2
```

### Get a path to the entry proto file for a specific API version
```js
protoFiles.pubsub.v1
// node_modules/google-proto-files/google/pubsub/v1/pubsub.proto
```
