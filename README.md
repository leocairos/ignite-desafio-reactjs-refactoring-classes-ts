<h1 align="center">
    <img alt="Ignite ReactJS" title="Ignite ReactJS" src="./.github/ignite.png" />
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/leocairos/ignite-desafio-reactjs-refactoring-classes-ts?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/leocairos/ignite-desafio-reactjs-refactoring-classes-ts">

  <a href="https://github.com//leocairos/ignite-desafio-reactjs-refactoring-classes-ts/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/leocairos/ignite-desafio-reactjs-refactoring-classes-ts">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/leocairos/ignite-desafio-reactjs-refactoring-classes-ts/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/leocairos/ignite-desafio-reactjs-refactoring-classes-ts?style=social">
  </a>

  <a href="https://www.linkedin.com/in/leonardo-sampaio-cairo-54a74756/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin&labelColor=blue">
  </a>
</p>

# 🚀 Sobre

O Ignite é um programa de aceleração para devs desenvolvido pela [Rocketseat](https://rocketseat.com.br/).


# 💻 Sobre o desafio

Nesse desafio, foi criada uma aplicação para treinar o que se aprendeu até agora no ReactJS

Essa será uma aplicação já funcional onde o seu principal objetivo é realizar dois processos de migração: de Javascript para Typescript e de Class Components para Function Components.


## Preparando ambiente Typescript

Como esse era um projeto CRA sem TypeScript, primeiro foi preciso instalar as dependências/tipagens e configurar o TS. Como sugestão foi criado um novo projeto CRA com Typescript e comparado a estrutura atual com a que precisaria ter. Realizando essa comparação, facilmente consegue-se ver que:

- É preciso instalar o `typescript`
- É preciso criar um arquivo de configuração `tsconfig.json`. Inclusive, pode-se utilizar a configuração gerada automaticamente no CRA template Typescript para criar o arquivo.
- É preciso criar um arquivo `react-app-env.d.ts` com o conteúdo:

  ```tsx
  /// <reference types="react-scripts" />
  ```

- É preciso instalar as tipagens das bibliotecas.

Configurando esse setup, foi possivel trabalhar normalmente com o Typescript no projeto.


## 📝 Licença

Este projeto esta sob a licença MIT.

Feito com ❤️ por [Leonardo Cairo](https://www.linkedin.com/in/leonardo-sampaio-cairo-54a74756/)!
