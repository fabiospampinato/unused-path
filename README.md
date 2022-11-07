# Unused Path

Reliably get an unused path and copy/move/write to it.

This is just a wrapper over the following libraries:

- [copy-unused-path](https://github.com/fabiospampinato/copy-unused-path)
- [get-unused-path](https://github.com/fabiospampinato/get-unused-path)
- [move-unused-path](https://github.com/fabiospampinato/move-unused-path)
- [write-unused-path](https://github.com/fabiospampinato/write-unused-path)

## Install

```sh
npm install --save unused-path
```

## Usage

```ts
import unusedPath from 'unused-path';

unusedPath.get // Exposes "get-unused-path"
unusedPath.copy // Exposes "copy-unused-path"
unusedPath.move // Exposes "move-unused-path"
unusedPath.write // Exposes "write-unused-path"
```

## License

MIT © Fabio Spampinato
