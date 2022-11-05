# typescript setup

`touch tsconfig.json`

copy paste the following
```json
{
  "compilerOptions": {
      "module": "commonjs",
      "esModuleInterop": true,
      "target": "es6",
      "noImplicitAny": true,
      "moduleResolution": "node",
      "sourceMap": true,
      "baseUrl": ".",
      "paths": {
          "*": [
              "node_modules/*"
          ]
      }
  },
  "include": [
    "**/*"
  ]
}
```

# require statements need `npm i -D @types/node`

run `npm i -D @types/node`

# compile a .ts file

run `ts-node index.ts` to compile a ts file without generating a new .js file

both `tsc index.ts` and `npx tsc index.ts` will create a new file.

# globals

`npm i -g typescript`

`npm i -g ts-node`
