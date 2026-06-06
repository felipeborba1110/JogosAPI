# 🎮 API de Jogos

API REST desenvolvida com **Node.js**, **Express**, **Firebase** e **JWT** para gerenciamento de usuários, catálogo de jogos e biblioteca pessoal.

## Tecnologias

* Node.js
* Express.js
* Firebase Authentication
* Firebase Firestore
* JWT (JOSE)

## Funcionalidades

### Usuários

* Cadastro de usuários
* Login com autenticação JWT
* Consulta de usuário autenticado
* Listagem de usuários (administradores)
* Gerenciamento da biblioteca de jogos

### Jogos

* Listagem de jogos
* Cadastro de jogos (administradores)
* Atualização de jogos (administradores)
* Remoção de jogos (administradores)

## Controle de Acesso

A API utiliza JWT para autenticação e possui dois níveis de acesso:

| Nível | Permissões                              |
| ----- | --------------------------------------- |
| User  | Gerenciar sua própria biblioteca        |
| Admin | Gerenciar usuários, jogos e bibliotecas |

## Objetivo

Fornecer uma API simples para gerenciamento de uma plataforma de jogos, permitindo autenticação de usuários, manutenção de catálogo e controle de bibliotecas pessoais utilizando Firebase como banco de dados.
