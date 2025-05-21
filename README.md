
# Projeto de Livraria em Node.js

Este projeto é uma aplicação de gerenciamento de livros e autores desenvolvida em Node.js. A aplicação utiliza o framework Express.js para criar rotas e lidar com requisições HTTP.

## Tecnologias Utilizadas

* Node.js (versão 18.16.0)
* Express.js
* Mongoose (para interagir com o banco de dados MongoDB)
* MongoDB (banco de dados NoSQL)

## Funcionalidades

A aplicação oferece as seguintes funcionalidades:

* Cadastro de livros
* Cadastro de autores
* Listagem de livros
* Listagem de autores
* Busca de livros por editora
* Atualização de livros
* Exclusão de livros
* Atualização de autores
* Exclusão de autores

## Rotas

A aplicação define as seguintes rotas:

* `/livros`: lista todos os livros
* `/livros/busca`: busca livros por editora
* `/livros/:id`: lista um livro específico
* `/livros`: cadastra um novo livro
* `/livros/:id`: atualiza um livro específico
* `/livros/:id`: exclui um livro específico
* `/autores`: lista todos os autores
* `/autores/:id`: lista um autor específico
* `/autores`: cadastra um novo autor
* `/autores/:id`: atualiza um autor específico
* `/autores/:id`: exclui um autor específico

## Modelos

A aplicação define os seguintes modelos:

* `Livro`: representa um livro com atributos como título, editora, preço, páginas e autor
* `Autor`: representa um autor com atributos como nome e nacionalidade

## Controllers

A aplicação define os seguintes controllers:

* `LivroController`: lida com as requisições relacionadas a livros
* `AutorController`: lida com as requisições relacionadas a autores

## Banco de Dados

A aplicação utiliza o MongoDB como banco de dados. O arquivo `dbConnect.js` define a conexão com o banco de dados.

