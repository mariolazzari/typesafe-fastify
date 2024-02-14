# Typesafe Fastify

## Install

```sh 
npm init -y
npm i -D typescript fastify-tsconfig @types/node @sinclair/typebox
npm i fastify @fastify/autoload @fastify/type-provider-typebox @fastify/swagger @fastify/swagger-ui
```

## Configuration

### tsconfig.json

```json
{
  "extends": "fastify-tsconfig",
  "compilerOptions":{
    "outDir": "build",
    "lib": ["ES2018"],
    "target": "ES2018"
  }
}
 ```

## Run
```sh
npm run build -- --watch
```
