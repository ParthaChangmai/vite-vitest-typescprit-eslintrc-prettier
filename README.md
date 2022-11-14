<h1  align="center">Welcome to vite-react-eslint-template 👋</h1>

<p>

<img  alt="Version"  src="https://img.shields.io/badge/version-0.0.1-blue.svg?cacheSeconds=2592000"  />

</p>

> A react vite template to kick start your development

## **State Management**

_[rematch](https://rematchjs.org/)_ + _[react query](https://tanstack.com/query/v3/)_

## **Pre Commit**

_[Husky](https://www.npmjs.com/package/husky)_

## **Code Formatter**

_[prettier](https://prettier.io/)_

## **Linter**

_[eslint](https://eslint.org/)_

## Recommended VS-code extensions

- **Code Spell Checker**

Id: streetsidesoftware.code-spell-checker
Description: Spelling checker for source code
Version: 2.11.0
Publisher: Street Side Software
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker

- **ESLint**

Id: dbaeumer.vscode-eslint
Description: Integrates ESLint JavaScript into VS Code.
Version: 2.2.6
Publisher: Microsoft
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint

- **Prettier - Code formatter**

Id: esbenp.prettier-vscode
Description: Code formatter using prettier
Version: 9.9.0
Publisher: Prettier
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

- **Prettier ESLint** (_optional_)

Id: rvest.vs-code-prettier-eslint
Description: A Visual Studio Extension to format JavaScript and Typescript code using prettier-eslint package
Version: 5.0.4
Publisher: Rebecca Vest
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=rvest.vs-code-prettier-eslint

## eslint Rules

**Functions**

- PascalCase _(JSX)_
- strictCamelCase _(Class Methods)_

**Variable**

- strictCamelCase
- UPPER*CASE *(constant values)\_

**TypeLike**

- PascalCase
- Prefix `I`

**parameter**

- strictCamelCase

## Huskey pre-commit config

    npx vitest --coverage --watch false

    eslint . --ext .ts,.tsx

## Test

    npx vitest

## Install

```sh

npm install

```

## Author

👤 **souvik dutta**

- Website: https://souvikdutta.netlify.app/

- Github: [@souvik666](https://github.com/souvik666)

## Show your support

Give a ⭐️ if this project helped you!

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
