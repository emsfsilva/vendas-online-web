# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list



-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

PASSOS PARA A CRIAÇÃO DO PROJETO

COMANDOS PARA CRIR O PROJETO REACT ANTES DO VS CODE
 - digitar no cmd, ja dentro da pasta do projeto clonada pelo GIT
	**npm create vite@latest**


- Colocar o nome do projeto
- Escolher REACT
- Escolher typeScript

JA NO VSCODE
- Abrir a pasta do projeto no vsCode
- Mover todos os arquivos para a pasta principal e apagar a pasta que ficou
- Digitar o comando:
	**npm install**

INSTALAR AS BIBLIOTECAS PARA ORGANIZAÇÃO DO CODIGO

**npm i -D @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-prettier eslint-plugin-import eslint-plugin-prettier eslint-plugin-react eslint-plugin-simple-import-sort prettier**

CRIAR OS ARQUIVOS
.prettierrc.js E O .eslintrc.js SE NÃO CRIAR AUTOMATICAMENTE

APAGAR ESSAS DUAS LINHAS DO PACKAGE.JSON PARA OS ARQUIVOS FUNCIONAREM
"private": true,
"type": "module",

INSTALAÇÃO DO ARQUIVO QUE AUXILIA NA CRAÇÃO DE ARUQIVOS DE LAYOUT

**npm install antd**

INSTALAÇÃO DO ARQUIVO QUE CONTEM OS COMPONENTES

**npm install --save styled-components**
**npm install --save-dev @types/styled-components**

PASSOS DE ORGANIZAÇÃO DO PROJETO

 - criar a pasta modules no src
 - criar a pasta shared

 RODAR O PROJETO FRONT
  **npm run dev**

