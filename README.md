# Modelagem de Banco de Dados: [PROJETO]

## Introdução
Este repositório contém os scripts SQL utilizados para criar e estruturar o banco de dados do projeto [Projeto]. O foco inicial está na tabela "Cliente", que serve como base para armazenar informações sobre os clientes do sistema.

## Conceitos Básicos
* **Entidade:** Representa um objeto do mundo real sobre o qual desejamos armazenar dados (ex: Cliente, Produto, Pedido).
* **Atributo:** Corresponde a uma característica da entidade (ex: Nome, CPF, Preço).
* **Tabela:** A representação de uma entidade em um banco de dados relacional.
* **Campo:** Corresponde a um atributo em uma tabela.

## Scripts SQL
### Criando o Banco de Dados

CREATE DATABASE PROJETO;
USE PROJETO;

## Criando a Tabela Cliente

CREATE TABLE CLIENTE (
    NOME VARCHAR(30),
    SEXO CHAR (1),
    EMAIL VARCHAR(30),
    CPF INT(11),
    TELEFONE VARCHAR(30),
    ENDERECO VARCHAR(100)
);

## Consultando a Estrutura da Tabela

DESC CLIENTE;




