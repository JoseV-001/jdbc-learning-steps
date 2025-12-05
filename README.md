# JDBC Learning Steps

Projeto criado para estudar **JDBC em Java**, incluindo conexões e operações básicas no MySQL.

## 📁 Estrutura

* **src/** – Código-fonte Java
* **database/** – Arquivos SQL para criar e popular o banco
* **db.properties** – Configurações do MySQL
* **jdbc-learning-steps/** – Outras versões do projeto

## ▶️ Como executar

1. Importe o projeto no IntelliJ.
2. Certifique-se de ter um banco no MySQL chamado **`coursejdbc`**.
3. Rode o script SQL em **database/** (opcional).
4. Ajuste o arquivo **db.properties** com usuário e senha do MySQL.
5. Execute a classe principal.

## 🗃️ Banco de dados

O banco deve ter o nome:

```
coursejdbc
```

Basta rodar no MySQL:

```sql
SOURCE create_tables.sql;
```

## 🚀 Objetivo

Estudo pessoal de Java + JDBC.
