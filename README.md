# 🍻 Chopp & Cia — Análise de Risco Integrado | Projeto Integrador VI

**Curso:** Ciência de Dados para Negócios — Fatec Votorantim  
**Autores:** Ana Elisa Rubinato Cavalheiro, Arthur Nunes dos Santos, Bruno Felipe de Souza Araujo, Caio Cesar Corrá, Lucas Camelo e Nicole Fava Pires  
⚠️ *Projeto de caráter estritamente acadêmico.*

---

## 📌 Visão Geral

O projeto desenvolveu uma solução preditiva para a distribuidora *Chopp & Cia* (Ponta Porã/Pedro Juan Caballero) para avaliar o **Risco Integrado**:
- **Risco Financeiro:** Atraso nos pagamentos a prazo.
- **Risco Logístico:** Retenção indevida de equipamentos em comodato (chopeiras e cilindros).

---

## 📁 O que foi Desenvolvido

- **Arquitetura em Nuvem:** Migração para ambiente Databricks com arquitetura Lakehouse (Delta Lake) e Unity Catalog.
- **Práticas de MLOps:** Rastreamento de experimentos, hiperparâmetros e versão de modelos via MLflow.
- **Conformidade com a LGPD:** Pseudonimização de dados pessoais com chaves sintéticas (SHA-256) e remoção de identificadores diretos.
- **Modelagem Preditiva:** Treinamento de modelos (Regressão Logística, Árvore de Decisão e Random Forest) avaliados pela métrica MCC (Coeficiente de Correlação de Matthews).
- **Modelo Campeão:** Random Forest, gerando uma tabela de scoring (`carteira_escorada`) classificada em Baixo, Médio e Alto Risco.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagens & Bibliotecas:** Python (`scikit-learn`, `pandas`)
- **Nuvem & Big Data:** Databricks, Apache Spark, Delta Lake
- **MLOps & Governança:** MLflow, Unity Catalog
- **Gestão:** Microsoft Planner (Kanban)

---

## 📜 Licença e Uso

Este repositório foi criado para fins de registro acadêmico e portfólio.

- ❌ **Não é permitida** a cópia ou redistribuição do conteúdo sem autorização prévia.
- 👁️ Disponível apenas para consulta e visualização.
---
## 🎓 Contexto Acadêmico
- **Instituição:** Faculdade de Tecnologia de Votorantim (Fatec Votorantim)
- **Disciplina:** PI6 — Projeto Integrador VI (2026)
