# Support Tickets API

API REST para gerenciamento de tickets de suporte, desenvolvida durante os estudos de **Node.js** com base no projeto da **Rocketseat**.

O projeto tem como objetivo praticar a criação de uma API utilizando Node.js, trabalhando com rotas HTTP, manipulação de requisições e respostas, filtros, parâmetros de rota e organização de código.

## Tecnologias utilizadas

* Node.js
* JavaScript
* HTTP
* REST API
* ES Modules
* Git e GitHub

## Funcionalidades

A API permite realizar operações relacionadas a tickets de suporte, como:

* Criar novos tickets
* Listar tickets
* Consultar um ticket específico
* Atualizar informações de um ticket
* Excluir tickets
* Filtrar tickets através de parâmetros
* Manipular requisições HTTP

## Estrutura do projeto

```text
support-tickets/
├── src/
│   ├── middlewares/
│   ├── routes/
│   ├── utils/
│   └── server.js
│
├── package.json
└── README.md
```

> A estrutura pode ser atualizada conforme novas funcionalidades forem adicionadas ao projeto.

## Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/MiguelS-Dev/support-tickets.git
```

### 2. Acesse a pasta

```bash
cd support-tickets
```

### 3. Instale as dependências

```bash
npm install
```

### 4. Execute a API

```bash
npm run dev
```

Ou, caso esteja utilizando diretamente o Node.js:

```bash
node src/server.js
```

## API

Após iniciar o servidor, a API ficará disponível localmente.

```text
http://localhost:3333
```

### Tickets

Exemplo de rota para listar os tickets:

```http
GET /tickets
```

Exemplo para criar um novo ticket:

```http
POST /tickets
```

Exemplo de consulta de um ticket específico:

```http
GET /tickets/:id
```

Exemplo de atualização:

```http
PUT /tickets/:id
```

Exemplo de exclusão:

```http
DELETE /tickets/:id
```

## Objetivo do projeto

Este projeto foi desenvolvido com foco no aprendizado e prática de desenvolvimento de APIs utilizando **Node.js**.

Durante o desenvolvimento, foram praticados conceitos importantes como:

* Criação de servidores HTTP
* Métodos HTTP
* Rotas
* Route Params
* Query Params
* Request e Response
* Middlewares
* Manipulação de JSON
* Status HTTP
* Organização de projetos Node.js
* Módulos ES Modules
* Operações CRUD

## Aprendizados

O desenvolvimento desta API contribuiu para aprofundar os conhecimentos em **JavaScript e Node.js**, principalmente na construção de APIs REST e na comunicação entre cliente e servidor.

O projeto também faz parte da minha evolução como desenvolvedor, buscando ampliar meus conhecimentos em desenvolvimento **Back-End** e integração com aplicações web.

## Autor

**Miguel Santana**

* GitHub: [MiguelS-Dev](https://github.com/MiguelS-Dev)
* LinkedIn: [MiguelS-Dev](https://www.linkedin.com/in/miguels-dev)

## Projeto

Repositório disponível no GitHub:

[github.com/MiguelS-Dev/support-tickets](https://github.com/MiguelS-Dev/support-tickets)
