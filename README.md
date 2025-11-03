# 📊 Projeto de Ciência de Dados – Northwind Traders

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?logo=powerbi)
![Python](https://img.shields.io/badge/Python-ETL%20%26%20An%C3%A1lise-3776AB?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?logo=pandas)
![DAX](https://img.shields.io/badge/DAX-Business%20Logic-blue)
![Portfolio](https://img.shields.io/badge/Portf%C3%B3lio-Ci%C3%AAncia%20de%20Dados-green)

---

## 🧠 Descrição

Projeto de portfólio em **Ciência de Dados**, com foco em **ETL, modelagem e visualização analítica**.  
A proposta é construir um **dashboard interativo no Power BI** a partir dos dados da empresa fictícia **Northwind Traders**, simulando um processo completo de análise de desempenho empresarial.

🔹 **Tecnologias utilizadas:** Python, Pandas, DAX, Power BI  
🔹 **Objetivo:** apoiar decisões gerenciais e otimizar resultados de vendas  
🔹 **Tema:** análise de clientes, faturamento, produtos e eficiência operacional  

---

## 🎯 Objetivos do Projeto

- Acompanhar indicadores de **receita e eficiência operacional**
- Promover o **aumento do ticket médio**
- Reduzir o **churn de clientes**
- Facilitar o **acesso a métricas estratégicas** por meio de um dashboard visual

---

## 🗂️ Escopo dos Dados

O projeto utiliza **14 tabelas** do ERP Northwind.
As tabelas principais incluem: `categories`, `customers`, `employees`, `order_details`, `orders`, `products`, `suppliers`, `us_states`

Tabelas descartadas:  
`customer_customer_demo`, `customer_demographics`, `employee_territories`, `region`, `territories`, `shippers`.

---

## ⚙️ Etapas do Projeto

### 1️⃣ Tratamento dos Dados (ETL – Python/Pandas)

- Renomeação, criação e junção de colunas  
- Cálculo de métricas como:
  - `total_amount = unit_price * quantity - discount`
  - `order_total = soma(total_amount)` por pedido  
- Adição da coluna `shipper_name` em `orders`  
- Exportação das tabelas transformadas em formato **Excel**

🔗 [Notebook de tratamento dos dados (Google Colab)](https://drive.google.com/file/d/1B9jcO6YcKU-C0iAo7lyRq_MnYGurkrXQ/view?usp=sharing)

---

### 2️⃣ Enriquecimento dos Dados (DAX – Power BI)

- Criação de tabela **Calendar** (análise temporal)
- Criação da tabela **CategoriaPairs** (associação entre produtos)
- Criação de **Score de Churn** com base em:
  - Recência  
  - Frequência  
  - Ticket médio  
- Outras medidas: **Frete médio**, **Faturamento**, **Ticket Médio**, etc.

---

### 3️⃣ Dashboard Analítico (Power BI)

O dashboard foi dividido em **5 seções**:
1. **Geral**
2. **Finanças**
3. **Locais**
4. **Clientes**
5. **Vendedores**

Cada aba contém:
- De **2 a 4 gráficos** interativos  
- De **2 a 4 cartões** com métricas diretas  
- Filtros dinâmicos por **Ano**, **Trimestre** e **Mês**

🔗 [Visualizar Dashboard no Power BI]([https://app.powerbi.com/groups/me/reports/7d4cfdaa-aa77-46a5-8dc1-d50b02d2987e/d698430edfa234eccc9b?ctid=639941cd-f7c0-4c54-9d7d-7ed7b2595e44&experience=power-bi](https://app.powerbi.com/links/SDxekBiUZp?ctid=639941cd-f7c0-4c54-9d7d-7ed7b2595e44&pbi_source=linkShare))

---

## 🧰 Tecnologias Utilizadas

| Categoria | Ferramenta / Linguagem |
|------------|------------------------|
| ETL / Tratamento | Python (Pandas, Google Colab) |
| Análise e Medidas | Power BI (DAX) |
| Armazenamento | Excel |
| Visualização | Power BI Desktop / Service |

---

## 📈 Principais Insights

- Identificação de **padrões de compra e churn**
- Análise dos **produtos mais rentáveis** e **regiões com maior faturamento**
- Métricas de **frete médio**, **ticket médio** e **eficiência operacional**
- Apoio à tomada de decisão gerencial por meio de indicadores visuais

---

## 🙌 Agradecimentos

Projeto desenvolvido como parte do meu **portfólio de Ciência de Dados**, explorando o uso integrado de **Python, DAX e Power BI** para transformar dados em decisões.

---

💡 *Autor:* **Luiz Roberto**  
📬 *Contato:* [LinkedIn](https://www.linkedin.com/luiz-rbferreira) | [E-mail](mailto:lrbf@cin.ufpe.br)


