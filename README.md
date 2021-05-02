# Hacker Chat
Criação de um app de chat com múltiplos usuários e múltiplas salas, rodando no terminal.

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/vhenckel/Hacker-Chat?label=javascript&style=for-the-badge">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/vhenckel/Hacker-Chat?style=for-the-badge">
  <img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/vhenckel/Hacker-Chat?style=for-the-badge">
</p>

<p align="center">
  <a href="#page_with_curl-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#hammer-iniciando-mobile">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#books-requisitos">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#rocket-começando">Começando</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#thought_balloon-inspiração">Inspiração</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :page_with_curl: Sobre
Este repositório contém duas aplicações do app de chat.

O diretório "client" contém uma aplicação para controle da interface do chat.

Já o diretório "server" contém uma pequena aplicação para gerenciar as salas, usuários e a troca de mensagens.

<h1 align="center">
  <img alt="Hacker-Chat" src="screen.jpeg" width="100%" />
</h1>

## :hammer: Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

- [Blessed](https://www.npmjs.com/package/blessed)
- [VS Code](https://code.visualstudio.com/) com [EditorConfig](https://editorconfig.org/), [ESLint](https://eslint.org/) e [Prettier](https://prettier.io/)

## :books: Requisitos
- Ter [**Git**](https://git-scm.com/) para clonar o projeto.
- Ter [**Node.js**](https://nodejs.org/en/) instalado.

## :rocket: Começando
``` bash
  # Clonar o projeto:
  $ https://github.com/vhenckel/Hacker-Chat.git

  # Entrar no diretório:
  $ cd Hacker-Chat
  
```
## :gear: Iniciando servidor
```bash
  # Entrar no diretório do servidor:
  $ cd server

  # Instalar as dependências:
  $ npm i

  # Iniciar a aplicação:
  $ npm run dev

  # Rodando a aplicação:
  $ http://localhost:9898
```

## :gear: Iniciando client
```bash
  # Entrar no diretório do servidor:
  $ cd client

  # Instalar as dependências:
  $ npm i

  # Iniciar a aplicação USER01:
  $ npm run user01

  # Iniciar a aplicação USER02:
  $ npm run user02

```

# :thought_balloon: Inspiração
Aplicação apenas para estudo de socket, eventEmitter, padrão Builder, etc.
- Esta aplicação faz parte da [Semana Javascript Expert 03](https://javascriptexpert.com.br/) criado por [Erick Wendel](https://cursos.erickwendel.com.br/).

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

Feito com :heart:&nbsp; & :brain:&nbsp; por Vitor Henckel :alien: 

[Get in touch!](https://github.com/vhenckel)