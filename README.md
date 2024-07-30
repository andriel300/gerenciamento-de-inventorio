# Gerenciamento de Inventório

![Inventory Management](https://example.com/banner.png)

## Descrição

Este é um sistema de gerenciamento de inventário desenvolvido para ajudar a controlar e organizar produtos em estoque. O projeto foi desenvolvido utilizando **Node.js**, **Express**, **MongoDB**, e **React**.

## Funcionalidades

- **Cadastro de Produtos**: Adicionar, editar e excluir produtos no inventário.
- **Controle de Estoque**: Visualizar quantidade de produtos disponíveis.
- **Relatórios**: Gerar relatórios de produtos em estoque.
- **Autenticação**: Sistema de login para diferentes níveis de acesso (administrador e usuário).

## Tecnologias Utilizadas

- **Backend**: Node.js, Express, MongoDB
- **Frontend**: React, Redux
- **Autenticação**: JWT (JSON Web Token)
- **Estilização**: CSS, Bootstrap

## Estrutura do Projeto

```plaintext
gerenciamento-de-inventorio/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── App.js
│   │   ├── index.js
│   └── package.json
│
├── .gitignore
├── README.md
└── package.json
