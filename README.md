# 🎮 Projeto Loja Games

![GitHub repo size](https://img.shields.io/github/repo-size/wallaceespy/projeto_loja_games)
![GitHub language count](https://img.shields.io/github/languages/count/wallaceespy/projeto_loja_games)
![GitHub last commit](https://img.shields.io/github/last-commit/wallaceespy/projeto_loja_games)
![GitHub](https://img.shields.io/github/license/wallaceespy/projeto_loja_games)

---

## 📌 Sobre o Projeto

O **Projeto Loja Games** é uma API REST desenvolvida para gerenciar uma loja de games, permitindo o controle completo de **produtos** e **categorias**.

A aplicação foi construída utilizando boas práticas de desenvolvimento backend, com foco em organização, escalabilidade e integração com banco de dados relacional.

---

## 🚀 Tecnologias Utilizadas

- ⚙️ NestJS  
- 🟦 TypeScript  
- 🗄️ MySQL  
- 🔗 TypeORM  
- 🧪 Insomnia  
 

---

## 📂 Estrutura do Projeto

src/
├── categoria/
│ ├── categoria.controller.ts
│ ├── categoria.service.ts
│ └── categoria.entity.ts
│
├── produto/
│ ├── produto.controller.ts
│ ├── produto.service.ts
│ └── produto.entity.ts
│
├── app.module.ts
└── main.ts



---

## ⚙️ Funcionalidades

✔️ CRUD completo de Produtos  
✔️ CRUD completo de Categorias  
✔️ Relacionamento entre Produtos e Categorias  
✔️ API REST estruturada  
✔️ Integração com banco de dados  

---

## 🔗 Endpoints

### 📦 Produtos

| Método | Rota              | Descrição              |
|--------|------------------|----------------------|
| GET    | /produtos        | Listar todos         |
| GET    | /produtos/:id    | Buscar por ID        |
| POST   | /produtos        | Criar produto        |
| PUT    | /produtos        | Atualizar produto    |
| DELETE | /produtos/:id    | Deletar produto      |

---

### 🗂️ Categorias

| Método | Rota              | Descrição              |
|--------|------------------|----------------------|
| GET    | /categorias      | Listar todas         |
| POST   | /categorias      | Criar categoria      |
| PUT    | /categorias      | Atualizar categoria  |
| DELETE | /categorias/:id  | Deletar categoria    |

---

## ▶️ Como Rodar o Projeto

### 🔧 Pré-requisitos

- Node.js instalado
- MySQL configurado

---

### 📥 Clone o repositório

```bash
git clone https://github.com/wallaceespy/projeto_loja_games.git
```

### 📦 Instale as dependências

```bash
npm install
```

### 🧪 Testes da API

Utilize o Insomnia.

---

### 📌 Melhorias Futuras

* 🔐 Autenticação com JWT
* 👤 Sistema de usuários
* 🛒 Carrinho de compras
* 💳 Integração com pagamentos
* 📊 Dashboard administrativo


👨‍💻 Autor

Desenvolvido por Wallace Espece 🚀
























<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg" alt="Donate us"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow" alt="Follow us on Twitter"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Project setup

```bash
$ npm install
```

## Compile and run the project

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Run tests

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Deployment

When you're ready to deploy your NestJS application to production, there are some key steps you can take to ensure it runs as efficiently as possible. Check out the [deployment documentation](https://docs.nestjs.com/deployment) for more information.

If you are looking for a cloud-based platform to deploy your NestJS application, check out [Mau](https://mau.nestjs.com), our official platform for deploying NestJS applications on AWS. Mau makes deployment straightforward and fast, requiring just a few simple steps:

```bash
$ npm install -g @nestjs/mau
$ mau deploy
```

With Mau, you can deploy your application in just a few clicks, allowing you to focus on building features rather than managing infrastructure.

## Resources

Check out a few resources that may come in handy when working with NestJS:

- Visit the [NestJS Documentation](https://docs.nestjs.com) to learn more about the framework.
- For questions and support, please visit our [Discord channel](https://discord.gg/G7Qnnhy).
- To dive deeper and get more hands-on experience, check out our official video [courses](https://courses.nestjs.com/).
- Deploy your application to AWS with the help of [NestJS Mau](https://mau.nestjs.com) in just a few clicks.
- Visualize your application graph and interact with the NestJS application in real-time using [NestJS Devtools](https://devtools.nestjs.com).
- Need help with your project (part-time to full-time)? Check out our official [enterprise support](https://enterprise.nestjs.com).
- To stay in the loop and get updates, follow us on [X](https://x.com/nestframework) and [LinkedIn](https://linkedin.com/company/nestjs).
- Looking for a job, or have a job to offer? Check out our official [Jobs board](https://jobs.nestjs.com).

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://twitter.com/kammysliwiec)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).
