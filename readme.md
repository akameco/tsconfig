# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects


## Install

```
$ yarn add --dev @akameco/tsconfig
```


## Usage

`tsconfig.json`

```json
{
  "extends": "@akameco/tsconfig",
    "compilerOptions": {
      "outDir": "dist",
      "lib": [
        "es2018"
      ]
    }
}
```


## License

MIT © [akameco](http://akameco.github.io)
