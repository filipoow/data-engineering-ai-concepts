# 🧠 data-engineering-concepts

> *Don't learn tools. Learn how systems work.*

Repositório pessoal para documentar minha jornada pelos **100 conceitos fundamentais de Data Engineering & AI** — do básico de modelagem até agentes e governança de dados em escala.

A ideia aqui não é acumular snippets soltos. É entender os sistemas por baixo: por que as coisas funcionam do jeito que funcionam, quando aplicar cada conceito e quais são os trade-offs reais.

---

## 🎯 O que quero dominar

- Fundamentos sólidos de modelagem, armazenamento e arquitetura de dados
- Como pipelines de dados funcionam de ponta a ponta (batch, stream, CDC)
- Processamento distribuído com Spark — entender o motor, não só a sintaxe
- Orquestração, qualidade e contratos de dados em produção
- Arquitetura Lakehouse (Delta Lake, Iceberg, Hudi)
- Sistemas de ML/AI — de feature engineering até agentes e RAG
- Governança, privacidade e operação de dados em escala

---

## 🗂️ Seções de estudo

| Seção | Conceitos | Status |
|-------|-----------|--------|
| [01 · Fundamentos](./01-fundamentos/) | Data Modeling, OLTP vs OLAP, Star Schema, Snowflake Schema, Normalization, Denormalization, Data Warehouse, Data Lake, Lakehouse, Medallion | 🔲 |
| [02 · Pipelines & Processamento](./02-pipelines-processamento/) | Batch, Stream, Micro-batch, Event-Driven, CDC, ETL vs ELT, Ingestion, Transformation, Partitioning, File Formats, Schema Evolution... | 🔲 |
| [03 · Spark & Sistemas Distribuídos](./03-spark-distribuido/) | Parallelism, Fault Tolerance, Shuffle, Lazy Evaluation, DAG, Catalyst, Tungsten, Joins, Skew, Caching, Spill to Disk... | 🔲 |
| [04 · Orquestração & Confiabilidade](./04-orquestracao-confiabilidade/) | Airflow, DAG Scheduling, Retry Logic, Backfill, SLA, Observability, Data Quality, Data Contracts, Lineage | 🔲 |
| [05 · Lakehouse & Storage](./05-lakehouse-storage/) | Delta Lake, Iceberg, Hudi, ACID Lakes, Time Travel, Merge/Upserts, Incremental Loads, Compaction, Vacuum | 🔲 |
| [06 · AI & ML Systems](./06-ai-ml/) | Feature Engineering, Feature Store, Training vs Inference, Model Drift, RAG, LLM Pipelines, Prompt Engineering, Agents, Tool Calling... | 🔲 |
| [07 · Governança & Escala](./07-governanca-escala/) | Data Governance, Data Privacy, PII, RBAC, Encryption, Cost Optimization, FinOps, Architecture | 🔲 |

---

## 📁 Estrutura do repositório

```
data-engineering-concepts/
│
├── 01-fundamentos/
│   ├── 01-data-modeling.md
│   ├── 02-oltp-vs-olap.md
│   └── ...
│
├── 02-pipelines-processamento/
│   ├── 11-batch-processing.md
│   ├── 12-stream-processing.md
│   └── ...
│
├── 03-spark-distribuido/
├── 04-orquestracao-confiabilidade/
├── 05-lakehouse-storage/
├── 06-ai-ml/
├── 07-governanca-escala/
│
└── README.md
```

Cada conceito tem seu próprio `.md` seguindo o mesmo formato:

```
## O que é
## Como funciona internamente
## Quando usar — e quando não usar
## Conexão com outros conceitos
## Exemplo concreto
## Referências
```

---

## 🧱 Stack de referência

Os exemplos e anotações ao longo do repositório vão refletir o ambiente que trabalho no dia a dia:

| Tecnologia | Papel |
|------------|-------|
| **Databricks** | Processamento, Delta Lake, Genie/AI BI |
| **PySpark** | Transformações distribuídas |
| **Delta Lake** | Camada de storage Lakehouse |
| **Unity Catalog** | Governança e controle de acesso |
| **Python** | Scripts, automação, pipelines |
| **SQL** | Consultas, views, modelagem analítica |

---

## 📊 Progresso

```
Section 1 · Fundamentos               ░░░░░░░░░░  0/10
Section 2 · Pipelines & Processamento ░░░░░░░░░░  0/20
Section 3 · Spark & Distribuído       ░░░░░░░░░░  0/20
Section 4 · Orquestração              ░░░░░░░░░░  0/10
Section 5 · Lakehouse & Storage       ░░░░░░░░░░  0/10
Section 6 · AI & ML Systems           ░░░░░░░░░░  0/20
Section 7 · Governança & Escala       ░░░░░░░░░░  0/10

Total ░░░░░░░░░░░░░░░░░░░░  0 / 100
```

---

## 🔗 Referências

- Roadmap original: **B V Sarath Chandra** — [LinkedIn](https://www.linkedin.com/in/bvsarathchandra/)
- [Databricks Documentation](https://docs.databricks.com/)
- [Delta Lake Documentation](https://docs.delta.io/)
- [Apache Spark Documentation](https://spark.apache.org/docs/latest/)
