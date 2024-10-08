# Flask API CRUD Project

Esta API foi desenvolvida utilizando **Flask** e implementa um **CRUD completo** (Create, Read, Update, Delete) para gerenciar produtos de um delivery. A API permite criar, listar, atualizar e deletar produtos, fornecendo informações como **nome**, **produto** e **valor**.

## Funcionalidades

- Criar, listar, atualizar e deletar produtos.
- API REST com suporte para operações **GET**, **POST**, **PUT**, e **DELETE**.

## Tecnologias Utilizadas

- Python 3.11.1
- Flask
- SQLAlchemy 
- Banco de dados: MySQL

**Corpo da Requisição** (JSON):
```json
{
        "cliente": "Jessica ",
        "id": 1,
        "produto": "sashimi",
        "valor": 100.00
    }
