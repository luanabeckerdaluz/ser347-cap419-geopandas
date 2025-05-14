# 2025 - SER-347/CAP-419 - Introdução à Programação com Dados Geoespaciais
## Análise de Dados Geoespaciais - GeoPandas 🌍
- Luana Becker da Luz

---

Este repositório contém um exemplo prático de uso da biblioteca **GeoPandas**. Há 2 Jupyter Notebooks onde usamos 3 arquivos shapefiles. Todos estes são detalhados abaixo:

---

### ▶️ Como usar

Após clone do repositório ou download da pasta, rode os comandos `unzip biomas.zip`, `unzip uf_2018.zip` e `unzip focos_2024_br.zip` para extrair os arquivos shapefiles.

---

### 📂 Arquivos shapefile

O repositório inclui três shapefiles principais no formato **.zip** que são utilizados nos notebooks:

1. **uf_2018.shp** – Polígonos das UFs do Brasil (2018);
2. **biomas.shp** – Polígonos dos biomas do Brasil;
3. **focos_2024_br.shp** – Conjunto de pontos com dados de queimadas para o Brasil entre Maio/Dezembro de 2024;

---

### 📓 Notebooks

### `geopandas.ipynb`: 
Esse notebook apresenta exemplos de como filtrar, analisar, mesclar e visualizar os shapefiles. Dentre os tópicos estão:
- Qual a distribuição dos focos ao longo dos meses do ano em 2024?
- Qual a distribuição dos focos por estado?
- Como filtrar os focos de queimada do estado do PARÁ?
- Além de filtrar para PARÁ, como podemos filtrar somente para um mês (e.g. setembro)?
- Como podemos mesclar os focos com os biomas?
- Qual a frequência mensal de queimadas por bioma?
- Qual a quantidade de focos por município ao longo dos meses?

### `desafio.ipynb`: 
Esse notebook contém a solução do desafio proposto ao final do notebook `geopandas.ipynb`
