# @whatasoda/tsconfig

## Enable `@whatasoda` namespace in your npm
If you did it before, you can skip it.
```sh
echo "@whatasoda:registry=https://npm.pkg.github.com/" >> ~/.npmrc
```

## Install package
```sh
npm i -D @whatasoda/tsconfig
```

## Usage
tsconfig.json
```json
{
  "extends": "@whatasoda/tsconfig",
  "compilerOptions": {
    "rootDir": "./"
  }
}
```
