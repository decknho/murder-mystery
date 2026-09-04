# 🔎 SQL Murder Mystery — Investigação com SQL e Python

## 📌 Sobre o projeto

Este projeto consiste na investigação de um caso de assassinato utilizando **SQL e Python** para analisar um banco de dados relacional e identificar o responsável pelo crime.

A investigação é conduzida a partir de diferentes registros disponíveis no banco, incluindo informações sobre a cena do crime, pessoas, entrevistas e outros dados relacionados ao caso.

O objetivo é utilizar **consultas SQL, cruzamento de tabelas e análise dos dados** para encontrar evidências, reduzir o número de suspeitos e chegar à solução do caso.

---

## 🎯 Objetivos

* Explorar e compreender a estrutura de um banco de dados relacional;
* Identificar informações relevantes para a investigação;
* Realizar consultas SQL para encontrar evidências;
* Cruzar informações entre diferentes tabelas;
* Utilizar consultas intermediárias e avançadas para filtrar suspeitos;
* Construir uma linha de investigação baseada nos dados;
* Identificar o responsável pelo crime;
* Demonstrar conhecimentos práticos de **SQL aplicado à análise de dados**.

---

## 🛠️ Tecnologias utilizadas

* **Python**
* **SQL**
* **SQLite**
* **Pandas**
* **Jupyter Notebook**
* **Git/GitHub**

---

## 🗂️ Estrutura do projeto

```text
sql-murder-mystery/
│
├── README.md
│
├── data/
│   └── sql-murder-mystery.sqlite
│
├── notebooks/
│   ├── 01_exploracao_e_investigacao.ipynb
│   ├── 02_cruzamento_de_evidencias.ipynb
│   └── 03_solucao_do_caso.ipynb
│
└── images/
    └── ...
```

---

# 🔍 Investigação

## 1. Exploração do banco de dados

A primeira etapa consiste em compreender a estrutura do banco de dados, identificando as tabelas disponíveis, seus campos e a quantidade de registros.

Também são realizadas consultas exploratórias para entender quais informações estão disponíveis e quais delas podem ser relevantes para a investigação.

**Principais conceitos utilizados:**

* `SELECT`
* `LIMIT`
* `COUNT`
* `WHERE`
* Exploração da estrutura das tabelas

---

## 2. Investigação inicial

Após compreender a estrutura do banco, são analisados os registros relacionados à cena do crime e às primeiras evidências disponíveis.

A partir dessas informações, são identificadas as pessoas e registros potencialmente relacionados ao caso.

**Principais conceitos utilizados:**

* Filtros com `WHERE`
* Ordenação com `ORDER BY`
* Condições lógicas
* Agregações
* Análise dos registros

---

## 3. Cruzamento de evidências

Com as primeiras informações identificadas, diferentes tabelas são relacionadas para encontrar novas evidências.

Essa etapa permite cruzar informações de pessoas, entrevistas e outros registros, reduzindo progressivamente o número de possíveis suspeitos.

**Principais conceitos utilizados:**

* `INNER JOIN`
* `LEFT JOIN`
* `GROUP BY`
* `HAVING`
* Subqueries
* `CASE WHEN`
* CTEs (`WITH`)

---

## 4. Identificação do suspeito

Na etapa final, as evidências encontradas ao longo da investigação são combinadas para identificar o responsável pelo crime.

As consultas finais são utilizadas para validar se o suspeito identificado atende às condições encontradas durante a investigação.

---

# 📊 Principais conhecimentos demonstrados

Este projeto demonstra conhecimentos práticos em:

### SQL

* Consultas e filtros de dados;
* Agregações;
* Múltiplos `JOINs`;
* Subqueries;
* CTEs;
* Condições com `CASE`;
* Análise de dados relacionais;
* Construção de consultas para resolução de problemas.

### Python

* Conexão com banco SQLite;
* Execução de consultas SQL através do Python;
* Utilização do Pandas para tratamento e visualização dos resultados;
* Integração entre Python e SQL.

### Análise de dados

* Exploração de bases relacionais;
* Identificação de padrões;
* Cruzamento de informações;
* Raciocínio analítico;
* Transformação de dados em evidências para tomada de decisão.

---

# 💡 Principais aprendizados

O projeto permitiu aplicar SQL em um cenário de investigação, demonstrando como consultas podem ser utilizadas não apenas para recuperar informações, mas também para **relacionar dados de diferentes fontes e construir conclusões a partir das evidências encontradas**.

Além dos conceitos técnicos, a investigação também reforçou a importância de compreender o problema antes de construir as consultas e de utilizar os resultados de cada etapa para direcionar a próxima análise.

---

# ✅ Resultado

Por meio da análise e do cruzamento das informações disponíveis no banco de dados, foi possível reconstruir a sequência de evidências e chegar à identificação do responsável pelo crime.

A solução completa e o processo utilizado para chegar à conclusão estão disponíveis nos notebooks deste repositório.

---

## 📚 Fonte

Projeto baseado no **[SQL Murder Mystery](https://www.kaggle.com/datasets/johnp47/sql-murder-mystery-database)**, desenvolvido como um exercício de investigação e aprendizado de SQL.

---

## 👨‍💻 Autor

**Dereck Eder**

Estudante de Ciência da Computação | Cientista de Dados

[GitHub](https://github.com/decknho) • [LinkedIn](https://www.linkedin.com/in/dereckeder/)
