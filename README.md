<img src="https://upload.wikimedia.org/wikipedia/commons/4/4c/Typescript_logo_2020.svg" style="width: 200px; display: block; margin: auto;"/>

# <p style="text-align: center;">tsconfig</p>

This is the tsconfig file shared by any project created for @jeroenpeeters.

## Usage

In a `tsconfig.json` file, after installing `@jeroenpeeters/tsconfig` as a package, use the `extends` field to define this configuration:
```json
{
  "extends": "@jeroenpeeters/tsconfig",
  "compilerOptions": {
    "baseUrl": "./",
    "outDir": "dist"
  }
}
```
