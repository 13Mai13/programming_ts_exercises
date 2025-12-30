# Exercises of Programming Typescript book

## How to setup a Typescript 

```
1. Install NodeJS -> https://nodejs.org/en
2. npm init
3. npm install --save-dev typescript tslint @types/node
```

In your root folder: 

1. `tsconfig.json` -> What you'll change is include `src` and outupt directory `dist` -> `./node_modules/.bin/tsc --init` 
2. `tslint.json` -> Linter -> `./node_modules/.bin/tslint --init` 

What the folder structure will look like: 

```
chapter-2/
├──node_modules/
├──src/
│ └──index.ts
├──package.json
├──tsconfig.json
└──tslint.json
```