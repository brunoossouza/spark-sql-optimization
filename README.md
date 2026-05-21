# 🚀 PySpark Optimization Project

Projeto desenvolvido utilizando PySpark com foco em processamento distribuído, otimização de joins e análise de performance em Big Data.

## 📌 Objetivo do Projeto

O objetivo deste projeto foi realizar a leitura de arquivos parquet, criar joins utilizando Spark SQL e aplicar técnicas de otimização para melhorar a performance do processamento de dados.

---

# 🛠 Tecnologias Utilizadas

- Python
- PySpark
- Spark SQL
- Apache Spark
- Parquet

---

# 📂 Estrutura dos Dados

Foram utilizados dois arquivos parquet:

- `videos-preparados.snappy.parquet`
- `videos-comments-tratados.snappy.parquet`

Os datasets contêm informações sobre vídeos, comentários, visualizações e sentimentos.

---

# ⚙️ Etapas Desenvolvidas

## ✅ Leitura de Dados
- Leitura dos arquivos parquet utilizando PySpark.

## ✅ Criação de DataFrames
- Criação dos DataFrames `df_video` e `df_comments`.

## ✅ Spark SQL
- Criação de tabelas temporárias com `createOrReplaceTempView()`.

## ✅ INNER JOIN
- Realização de JOIN entre os datasets utilizando `spark.sql()`.

## ✅ Repartition
- Redistribuição dos dados para melhorar o paralelismo do processamento.

## ✅ Coalesce
- Redução do número de partitions para diminuir custo computacional.

## ✅ Explain
- Análise do plano de execução utilizando `explain(True)`.

## ✅ Otimização Final
Foram aplicadas técnicas de otimização como:
- seleção apenas de colunas necessárias
- filtros antes do JOIN
- repartition utilizando chave de junção
- redução de shuffle

## ✅ Exportação
- Salvamento do dataframe otimizado no formato parquet.

---

# 📈 Técnicas de Otimização Utilizadas

- `repartition()`
- `coalesce()`
- `filter()`
- `select()`
- `spark.sql()`
- análise com `explain(True)`

---

# 🎯 Aprendizados

Este projeto permitiu praticar conceitos importantes de:
- Engenharia de Dados
- Processamento Distribuído
- Big Data
- Otimização com Apache Spark
- Spark SQL

---

# 👨‍💻 Autor

Bruno Souza

