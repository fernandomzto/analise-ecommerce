# Análise de Desempenho de um E-commerce Fictício - Power BI

Este projeto tem como objetivo explorar e visualizar o desempenho de um e-commerce fictício ao longo de 12 meses. Através da modelagem e visualização dos dados no Power BI, busquei praticar conceitos de análise de dados, estruturação de modelos, criação de KPIs e design de dashboards interativos.

---

## Objetivo

Aplicar e consolidar os conhecimentos iniciais adquiridos em análise de dados e Power BI, desenvolvendo um projeto completo com:
- Modelagem de dados (fato e dimensão)
- Criação de KPIs relevantes
- Visualizações interativas
- Segmentações de dados
- Interpretação de insights

---

##  Base de Dados

Os dados utilizados neste projeto foram obtidos no Kaggle:  
[E-commerce Sales Analysis Dataset – por Fahmida Chowdhury](https://www.kaggle.com/datasets/fahmidachowdhury/e-commerce-sales-analysis)

A base de dados é fictícia e representa um e-commerce com os seguintes campos:
- Informações sobre os produtos: nome, categoria, preço, pontuação de avaliação e número de avaliações
- Vendas mensais de cada produto ao longo de 12 meses
- Receita mensal calculada a partir das vendas e preços

Os dados foram inicialmente organizados no Excel.

---

## Etapas do Projeto

1. **Limpeza e preparação dos dados** no Excel
2. **Unpivot das colunas mensais** (vendas por mês → linha por produto e mês)
3. **Criação de duas tabelas**:
   - **Fato**: vendas e receita por produto e mês
   - **Dimensão**: informações do produto
4. **Criação de coluna categórica** de avaliação: *Bad, Good, Excellent*
5. **Início da análise descritiva, criação de tabelas de frequência**
6. **Importação no Power BI**
7. **Relacionamento entre as tabelas**
8. **Criação de KPIs e medidas DAX simples**
9. **Criação de dashboards em duas páginas**
10. **Inserção de filtros interativos (slicers)**

---

## Ferramentas Utilizadas

- Microsoft Excel
- Power BI Desktop
- Power Query (Unpivot)
- DAX básico
- Ferramentas de IA como Google Gemini e ChatGPT

---

##  Principais Aprendizados

- Reaplicação de conceitos de limpeza, formatação e validação dos dados utilizando Power Query no Excel
- Entendimento da **estrutura de dados relacional (fato x dimensão)**
- Aplicação de **unpivot** para facilitar análises temporais
- Criação e interpretação de **KPIs relevantes** para negócio
- **Design de dashboards** e organização visual
- Uso de **slicers** para segmentação e interatividade
- Interpretação de dados para gerar **insights descritivos**

---

##  Pontos a Melhorar

- Melhorar o desenvolvimento do **pensamento analítico inicial** (Quais respostas estou buscando? Que solução quero implementar?) e consequentemente **obter melhores insights**.
- Organizar melhor as ideias no Excel, criando abas específicas e com melhor visual para análises descritivas e tabelas dinâmicas.
- Estudar mais sobre **design visual** (tipografia, cores, layout)
- Trabalhar com **narrativa de dados (data storytelling)** mais estruturada
- Utilizar menos, ou com mais sabedoria, ferramentas auxiliares de inteligência artificial.

---

##  Dashboard

### Página 1 - Visão Geral

![Dashboard Página 1](/imagens/pg1dash.png)

### Página 2 - Categorias

![Dashboard Página 2](/imagens/pg2dash.png)
---

## Como Abrir o Projeto

1. Baixe os arquivos `.pbix` disponíveis neste repositório
2. Abra com o [Power BI Desktop](https://powerbi.microsoft.com/)
3. Navegue entre as páginas e interaja com os filtros para explorar os dados

---

##  Contato

[LinkedIn](https://www.linkedin.com/in/fernandomiyazato)  
[GitHub](https://github.com/fernandomzto)
