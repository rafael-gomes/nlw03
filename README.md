<h1 align="center">
    <img src="web/src/images/logo.svg" alt="Logo">
</h1>


<p align="center">
  <img alt="Happy" src="web/src/images/happy.png" width="100%">
</p>

# Indíce
- [Sobre](#-sobre)
- [Projeto](#-o-projeto)
- [Tecnologias utilizadas](#-tecnologias-utilizadas)
- [Divisão do projeto](#-divisão-do-projeto)
- [Como baixar o projeto](#-como-baixar-o-projeto)
- [Executando a aplicação Web](#-executando-a-aplicação-web)
- [Executando a aplicação Mobile](#-executando-a-aplicação-mobile)

## Sobre

 O projeto **Happy** é um sistema criado durante a **3ª NLW (Next Level Week)** da [**Rocketseat**](https://rocketseat.com.br/), na trilha Omnistack.

---

## O Projeto
O Happy é uma aplicação que conecta pessoas à casas de acolhimento institucional, com um mapa e as localizações das casas de acolhimento próximas.

---

## Tecnologias utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- [Node.js](https://nodejs.org/)
- [React](https://reactjs.org/)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)
- [TypeScript](https://www.typescriptlang.org/)

---

## Divisão do projeto ##

O projeto está dividido em três partes: Web, Backend e Mobile.

A aplicação Web foi desenvolvida para que fosse possível executar em qualquer navegador e possui integração completa com o Backend.

O Backend possui toda a lógica da aplicação, como configuração de rotas das páginas Web e o banco de dados (SQLite) da aplicação.

A aplicação Mobile foi desenvolvida utilizando React Native e também possui a comunicação com os dados do Backend.

---

## Como baixar o projeto

``` bash
    # Clonar o repositório
    $ git clone https://github.com/rafael-gomes/nlw03.git
    
```
## Executando a aplicação Web ##

Para que a aplicação execute corretamente, será necessário inserir o IP do computador em que a aplicação irá rodar no seguinte arquivo do backend:
- backend/src/views/images_view.ts

Execute os comandos a seguir:

``` bash
  # Entrar no diretório do backend
  $ cd nlw03/backend

  # Instalar as dependências
  $ yarn install

  # Executando o backend
  $ yarn dev

  # Entrar no diretório web
  $ cd ../web

  # Executar a aplicação web
  $ yarn start
```

## Executando a aplicação Mobile ##

Para que a aplicação execute corretamente, será necessário inserir o IP do computador em que a aplicação irá rodar no seguinte arquivo do mobile:
- mobile/src/services/api.ts

Execute os comandos a seguir:

``` bash
  # Entrar no diretório do mobile
  $ cd nlw03/mobile

  # Instalar as dependências
  $ yarn install

  # Executando o mobile
  $ npm start
```

Na janela do navegador que será exibida, é necessário escanear o QRCode no dispositivo móvel ou, caso possua emulador (Android/IOS), clicar em rodar no referido emulador.

---

Desenvolvido por Rafael Gomes de Oliveira.
