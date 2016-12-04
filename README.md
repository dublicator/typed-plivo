# Typed Plivo Node

The type definition for [`plivo`](https://github.com/plivo/plivo-node)

How to install for usage.
```bash
typings install plivo=github:dublicator/typed-plivo/index.d.ts --global --save
```

## LICENSE

MIT

## Contributing

```sh
# Fork this repo
npm install

npm run watch

# add tests, make changes, pass tests ... then [ctrl+c]
npm run publish
```

## Updating

Update `typings.json/version` to match the source version you are typing against.
e.g. if you are creating typings for `chai@3.5.0`, then:
```js
// typings.json
{
  "version": "3.5.0"
  // ...
}
```
