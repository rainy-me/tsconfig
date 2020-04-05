# @kalafina/tsconfig

## Setup your `.npmrc`

If you did it before, you can skip it.

1. Create an access token with permmision `read:packages`.

   See: [How to create a persional access token for the command line](https://help.github.com/en/articles/creating-a-personal-access-token-for-the-command-line)

2. Apply token to your `.npmrc`. (replace `PERSONAL-ACCESS-TOKEN` with your access token)

   ```sh
   echo "//npm.pkg.github.com/:_authToken=PERSONAL-ACCESS-TOKEN" >> ~/.npmrc
   ```

3. Set `@kalafina` namespace to use GitHub registry.
   ```sh
   echo "@kalafina:registry=https://npm.pkg.github.com/" >> ~/.npmrc
   ```

## Install package

```sh
npm i -D @kalafina/tsconfig
```

## Usage

tsconfig.json

```json
{
  "extends": "@kalafina/tsconfig",
  "compilerOptions": {
    "rootDir": "./"
  }
}
```
