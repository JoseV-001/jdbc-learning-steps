# JDBC Learning Steps

Projeto criado para estudar **JDBC em Java**, incluindo conexão, consultas e operações básicas no MySQL.

## 📁 Estrutura

* **src/** – Código-fonte Java
* **database/** – Arquivos SQL (criação e dados iniciais)
* **db.properties** – Configurações do MySQL
* **jdbc-learning-steps/** – Outras versões do projeto usadas nos estudos

## ▶️ Como executar

1. Importe o projeto no IntelliJ.
2. Certifique-se de ter um banco no MySQL chamado **`coursejdbc`**.
3. Rode o arquivo **`seed.sql`** presente na pasta **database/**.
4. Ajuste o arquivo **db.properties** com usuário e senha do MySQL.
5. Execute a classe principal para testar as operações JDBC.

## 🗃️ Banco de dados

O banco deve ter o nome:

```
coursejdbc
```

Para criar as tabelas e inserir os dados iniciais, basta rodar no MySQL:

```sql
SOURCE seed.sql;
```

## 🚀 Objetivo

Projeto criado para estudo pessoal de **Java + JDBC**, com cada versão demonstrando um recurso específico (consultas, inserção, atualização, deleção e transações).
