# Sharing tslint rules across multiple projects via a npm package

This repo is a npm package which can be used to share tslint rules across multiple projects.
In microservice architectures built with TypeScript this is necessary to ensure a consistent code style and quality.


## How to use this package

1. Install this package via ```npm install -D shared-tslint-rules-example```
1. Create a tslint.json with the following contents and optional specific rules for your use case
```
{
    "extends": "shared-tslint-rules-example/tslint.json"
}
```
1. use tslint via command line/IDE/webpack

