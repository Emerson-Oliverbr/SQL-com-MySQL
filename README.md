# Modelagem de Banco de Dados: [PROJETO]

## Introdução
Este repositório contém os scripts SQL utilizados para criar e estruturar o banco de dados do projeto [PROJETO]. O foco inicial está na tabela "Cliente", que serve como base para armazenar informações sobre os clientes do sistema.

## Conceitos Básicos
* **Entidade:** Representa um objeto do mundo real sobre o qual desejamos armazenar dados (ex: Cliente, Produto, Pedido).
* **Atributo:** Corresponde a uma característica da entidade (ex: Nome, CPF, Preço).
* **Tabela:** A representação de uma entidade em um banco de dados relacional.
* **Campo:** Corresponde a um atributo em uma tabela.

## Scripts SQL
### Criando o Banco de Dados
```sql
CREATE DATABASE nome_do_seu_projeto;
USE nome_do_seu_projeto;

## Criando a Tabela Cliente

CREATE TABLE Cliente (
    id_cliente INT PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(100) NOT NULL,
    cpf CHAR(11) UNIQUE,
    email VARCHAR(100),
    telefone VARCHAR(20),
    endereco VARCHAR(255)
);

## Consultando a Estrutura da Tabela

DESC Cliente;




