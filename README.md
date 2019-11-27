# Sharing tslint rules across multiple projects via an npm package

This repo is an npm package which can be used to share tslint rules across multiple projects.
In microservice architectures built with TypeScript this is necessary to ensure a consistent code style and quality.


## How to use this package

1. Install this package via ```npm install -D shared-tslint-rules-example```
2. Create a tslint.json as shown below and optional specific rules for your use case
3. use tslint via command line/IDE/webpack

**Example tslint.json which uses the shared rules**
```
{
    "extends": "shared-tslint-rules-example/tslint.json"
}
```
