# Escola de Inglês API

[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Sobre
REST API de gerenciamento de uma escola de inglês desenvolvida com **Node.JS** e **Express** e conexão com **MySQL**, durante a aula de ORM com Node.JS da plataforma
de ensino Alura, com o objetivo de compreender a utilizar as funcionalidades do **Sequelize**. Além do **CRUD** básico, 
a API também apresenta diferentes métodos e refina as consultas do banco de forma eficiente através das funcionalidades
do Sequelize, fazendo o gerenciamento de diferentes tabelas com associações entre si. 

### Models

- Pessoas
- Matrículas
- Níveis
- Turmas


### Métodos

Todos as tabelas possuem suporte ao CRUD básico, podendo listar, listar por id, inserir, atualizar, apagar e também
restaurar (através do soft delete). No entanto, a tabela Pessoas e Matrículas que fazem associações entre si apresentam
também métodos adicionais:

- Listar matrículas por id da pessoa
- Listar matrículas por id da turma
- Cancelar pessoa e todas as suas matrículas, tornando-a inativa
- Listar apenas pessoas ativas
- Listar e contar turmas lotadas através da quantidade de matrículas cadastradas

## Tecnologias utilizadas
- Node.js
- Express
- Sequelize
- MySQL

## Autor

LinkedIn: https://www.linkedin.com/in/emanuele-rangel-7b50971b8/

e-mail: emanuele.rangel52@gmail.com
