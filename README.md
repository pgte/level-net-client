# level-net-client

> Node.js client for [level-net-server](https://npmjs.org/package/level-net-server)

## Install

```bash
$ npm i level-net-client --save
```

## Require and create

```javascript
var Client = require('level-net-client');

var db = Client();
```

## Connect to a Level Net Server

```javascript
db.connect(port, host, cb);
```

## Use

Now you can use the client with the same API as the [`levelup` db](https://npmjs.org/package/levelup#api).

## License

MIT