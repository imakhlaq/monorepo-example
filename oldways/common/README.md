# How to create and publish a npm package

## Keep in mind

1. You publish the js code not the ts code.
2. For types  "declaration": true, in tsconfig.json

## Steps

1. Name should be unique => "name": "@imakhlaq/common".
2. Main entry point should point the build folder => "main": "dist/index.js".
3. Configure tsconfig.json, build the project, login to the npm => `npm login`
4. Publish the package to npm `npm publish --access=public`.
5. Everytime you publish a new package u have to update the version.
6. `npm pack` creates a zip file that contains what will be sent to the npm.