## 🚗 Projeto Nova Drive Motors

> Projeto desenvolvido como parte do curso "Construa um Pipeline de Dados com Snowflake, Airflow, dbt, Postgres e Looker Studio" da Udemy.
> O objetivo é implementar um pipeline de dados completo (end-to-end), desde a ingestão até a visualização, aplicando boas práticas de engenharia de dados e conceitos de DataOps.


---

## 🧱 Arquitetura do Projeto
```
[ PostgreSQL (Fonte) ]
        ↓
[ Airflow (Orquestração) ]
        ↓
[ Snowflake (Data Warehouse) ]
        ↓
[ dbt (Transformações - ELT) ]
        ↓
[ Looker Studio (Visualização) ]
```
_______________________________________________________________

## ⚙️ Tecnologias Utilizadas

- PostgreSQL → Armazenamento inicial (staging)
- Snowflake → Data Warehouse
- Apache Airflow → Orquestração de pipelines
- DBT → Transformações e modelagem
- Looker Studio → Dashboards e visualização
- Python → Scripts e integração
- Docker → Ambiente de execução do Airflow

---

## 📁 Estrutura do Repositório

```
📦 NOVADRIVE
 ┣ 📂 macros/
 ┣ 📂 models/
 ┣ 📂 seeds/ 
 ┣ 📂 snapshots/
 ┣ 📂 tests/    
 ┣ 📄 dbt_project.yml      # Configuração principal do projeto dbt
 ┣ 📄 .gitignore
 ┗ 📄 README.md
```

---
## 👨‍💻 Autor
Alyson Gheno
📍 Brasil
