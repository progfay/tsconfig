# @progfay/tsconfig

## Installation

```sh
npm install --save-dev @tsconfig/node16
```

## Setup

```json
{
  "extends": "@progfay/tsconfig/tsconfig.json",

  /* Optional */
  "compilerOptions": {
    "declaration": true,
    "declarationMap": true,
    "sourceMap": true,
    "outDir": "./lib"
  },
  "include": ["src/**/*.ts"],
  "exclude": ["src/**/*.test.ts"],
}
```
