# 🏫 Sistema de Apadrinhamento Escolar (PostgreSQL)

Projeto de Banco de Dados Relacional desenvolvido para gerir o acompanhamento e contribuições de padrinhos a estudantes escolares.

## 🚀 Tecnologias Utilizadas
- **SGBD:** PostgreSQL
- **Linguagem:** SQL (DDL, DML, DQL)

## 📌 Funcionalidades
- **Modelagem Relacional:** Criação de schemas, tabelas e chaves primárias/estrangeiras (`FOREIGN KEY`).
- **Restrições de Integridade:** Utilização de restrições `CHECK`, `NOT NULL` e `UNIQUE` para garantir consistência de dados.
- **Consultas Avançadas (DQL):**
  - Listagem de alunos sem apadrinhamento atrelado (utilizando subqueries).
  - Agregação e contagem de contribuições por padrinho.
  - Junção de tabelas (`JOIN`) para identificar escolas com maior número de participantes.
  - Filtragem por status de contribuições pendentes ou realizadas.

## 📂 Como Executar
1. Instale o **PostgreSQL** ou utilize uma ferramenta como **pgAdmin** / **DBeaver**.
2. Execute o script `M3_DQL_MiguelAlacoque_ArielGomes.sql` no seu ambiente SQL.