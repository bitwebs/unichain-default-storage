# unichain-default-storage

Default storage provider used by Unichain

```
npm install @web4/unichain-default-storage
```

## Usage

``` js
const defaultStorage = require('@web4/unichain-default-storage')

const feed = unichain(name => defaultStorage(name, { directory: 'feed' }))
```

## API

#### `storage = defaultStorage(name, [options])`

Makes a new random-access-storage provider using the random-access-file module.

If making a bitfield file that file will be locked to avoid parallel writers.

## License

MIT
