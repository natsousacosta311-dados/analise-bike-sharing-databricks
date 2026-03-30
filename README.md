# 🚲 Projeto Final - Bike Sharing (Databricks)

Este repositório apresenta um projeto de análise de dados baseado em um sistema de compartilhamento de bicicletas (*Bike Sharing*), desenvolvido no ambiente **Databricks** utilizando **PySpark**.

---

## 📋 Sobre o Projeto

O principal objetivo deste projeto é explorar e analisar dados históricos de aluguel de bicicletas, com o intuito de identificar padrões de comportamento dos usuários.

A análise busca compreender como diferentes fatores influenciam a demanda por bicicletas, com foco em:

- 🌦️ Condições climáticas (`weathersit`)
- 🗓️ Dias úteis vs. finais de semana/feriados (`workingday`)
- 🍂 Variações sazonais
- ⏰ Padrões ao longo do dia (análise por hora)

---

## 🛠️ Tecnologias Utilizadas

- **Databricks** → Plataforma de processamento e análise de dados  
- **Apache Spark (PySpark)** → Processamento distribuído de grandes volumes de dados  
- **Spark SQL** → Consulta e manipulação de dados estruturados  
- **Python** → Linguagem principal para análise e transformação de dados  

---

## 📊 Estrutura do Notebook

O projeto foi desenvolvido seguindo as etapas abaixo:

### 🔎 1. Exploração de Datasets
- Localização dos dados no diretório padrão do Databricks:
/databricks-datasets/bikeSharing/

- Identificação dos arquivos principais:
- `day.csv` (dados agregados por dia)
- `hour.csv` (dados por hora)

---

### 📖 2. Análise de Metadados
- Leitura do arquivo `README.md`
- Compreensão do dicionário de dados e contexto do dataset

---

### ⚙️ 3. Processamento de Dados
- Leitura dos arquivos CSV com:
- Inferência de schema
- Cabeçalho habilitado
- Criação de **DataFrames** no PySpark
- Criação de **Temp Views** para consultas em SQL

---

### 📈 4. Agregações e Insights
- Construção de tabelas de frequência
- Análises por:
- Ano e estação
- Hora do dia
- Condições climáticas
- Tipo de dia (útil ou não)
- Uso de **Spark SQL** para geração de métricas como:
- Total de alugueis
- Comparações entre cenários

---

## 🚀 Como Executar o Projeto

Para executar este projeto no Databricks:

1. Importe o arquivo `.ipynb` para o seu Workspace
2. Inicie um cluster no Databricks
3. Execute as células do notebook em sequência
4. Os dados serão carregados diretamente do diretório padrão (`DBFS`)

---

## 📌 Considerações Finais

Este projeto demonstra, de forma prática, o uso do **Databricks + PySpark** para análise exploratória de dados, destacando boas práticas como:

- Organização do fluxo analítico  
- Uso de SQL para exploração  
- Transformação de dados em escala  

---

