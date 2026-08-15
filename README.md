# Power BI Sales Report

## 📊 Desafio de Projeto — DIO

Atualização de um relatório desenvolvido em Power BI com foco em **Experiência do Usuário (UX)**, organização visual, navegação, segmentação dos dados e análise de desempenho e rentabilidade.

O projeto foi desenvolvido a partir do relatório apresentado durante o curso, aplicando melhorias de **posicionamento, contraste, proporção, hierarquia visual e interatividade**.

---

## 🎯 Objetivo

Modificar e aprimorar o relatório original considerando os seguintes princípios:

- Posicionamento dos elementos;
- Contraste visual;
- Proporção áurea como referência de composição;
- Segmentação dos dados;
- Experiência de navegação do usuário;
- Clareza na apresentação dos indicadores.

A proposta foi utilizar esses princípios como orientação, mantendo liberdade para adaptar e quebrar regras quando isso contribuísse para uma melhor experiência visual e analítica.

---

## 📑 Estrutura do relatório

O relatório é composto por **3 páginas principais**:

### 1. Overview

Visão executiva dos principais indicadores e resultados de vendas.

Principais elementos:

- Sales
- Profit
- Units Sold
- Profit Margin
- Sales Contribution & Cumulative Share
- Sales & Profit Margin — Monthly Trend
- Sales by Product / Segment
- Sales by Quarter

![Overview](screenshots/01-overview.png)

---

### 2. Performance

Página dedicada à análise de desempenho comercial e aos principais direcionadores das vendas.

Principais elementos:

- KPIs de Sales, Profit, Units Sold e Profit Margin;
- Sales Decomposition;
- Análise de Sales × Profit Margin;
- Análise por Segment, Product e Country;
- Sales Contribution;
- Árvore hierárquica para exploração dos dados.

![Performance](screenshots/02-performance.png)

---

### 3. Profitability

Página dedicada à análise de rentabilidade e seus principais fatores.

Principais elementos:

- Profit & Profit Margin — Monthly Trend;
- Profit Contribution by Segment;
- Profitability Drivers;
- Profit by Product;
- Análise por Segment, Product e Country.

![Profitability](screenshots/03-profitability.png)

---

## 🧭 Navegação e experiência do usuário

O relatório possui menus de navegação entre as três páginas:

**Overview → Performance → Profitability**

Também foram implementados:

- Botões de navegação;
- Estados visuais dos botões;
- Filtros acessíveis por ícone;
- Segmentação por período e dimensões de análise;
- Interações entre os visuais;
- Hierarquia visual para facilitar a leitura dos KPIs e gráficos.

---

## 🎨 Design

A identidade visual foi desenvolvida com foco em:

- Fundo escuro;
- Contraste entre elementos;
- Hierarquia de informação;
- Consistência entre páginas;
- Organização em grid;
- Destaque visual para indicadores positivos e negativos;
- Padronização de títulos, cartões e gráficos.

A proporção áurea foi utilizada como **referência de composição**, sem tratá-la como uma regra rígida.

---

## 🛠️ Ferramentas e recursos

- Power BI
- DAX
- Power Query
- Modelagem de dados
- KPIs
- Segmentações
- Filtros
- Navegação entre páginas
- Árvore hierárquica
- Treemap
- Gráfico de dispersão
- Gráfico de cascata
- Gráficos combinados
- Interações entre visuais

---

## 📁 Estrutura do repositório

```text
power-bi-sales-report/
│
├── dashboard/
│   └── Sales_Report.pbix
│
├── screenshots/
│   ├── 01-overview.png
│   ├── 02-performance.png
│   └── 03-profitability.png
│
└── README.md
