![nodejs-and-typescript](https://i.snipboard.io/93yCRK.jpg)

# NodeJS + Typescript

> Different of [basic kit](https://github.com/tiagoboeing/node-typescript-template), this repository is more complete, includes Sucrase compiler, ESLint and Prettier.

## What is

Clean and initial template to use NodeJS with Typescript, Sucrase compiler + ESLint + Prettier

## How use

- Clone this repository and run `npm install` or `yarn install` in project folder
- Write your code in `src/server.ts`
- Run `npm run dev` or `yarn dev` to start Sucrase compiler and Nodemon
  - nodemon will be started after compile success

> The entry file is `server.js`

> Typescript compiler send compiled sources to `dist` folder: `dist/server.js`

Feel free to to customize and collaborate sending a pull request! 😁

### Build command

- Run `yarn build` or `npm run build`

### Configure VSCode

In User Settings (`settings.json`) add:

```
  "eslint.autoFixOnSave": true,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    {
      "language": "typescript",
      "autoFix": true
    },
    {
      "language": "typescriptreact",
      "autoFix": true
    }
  ]
```