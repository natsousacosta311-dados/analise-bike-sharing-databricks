Projeto Final - Bike Sharing (Databricks)
Este repositório contém o projeto de análise de dados do sistema de partilha de bicicletas (Bike Sharing), desenvolvido no ambiente Databricks utilizando PySpark.

📋 Sobre o Projeto
O objetivo principal deste projeto é explorar e analisar dados históricos de aluguel de bicicletas, identificando padrões de comportamento baseados em condições sazonais e ambientais.

O estudo foca-se na relação entre o volume de alugueres e variáveis como:

Condições climáticas (weathersit).

Dias úteis vs. fins de semana (workingday).

Variações sazonais e horárias.

🛠️ Tecnologias Utilizadas
Databricks: Plataforma de análise de dados.

Apache Spark (PySpark): Processamento distribuído de dados.

Spark SQL: Manipulação e consulta de dados estruturados.

Python: Linguagem principal para lógica de análise.

📊 Estrutura do Notebook
O projeto segue as seguintes etapas:

Exploração de Datasets: Localização e leitura dos dados originais no DBFS (/databricks-datasets/bikeSharing/).

Análise de Metadados: Consulta aos ficheiros README.md do dataset para entender os dicionários de variáveis.

Processamento de Dados:

Leitura de ficheiros CSV (day.csv e hour.csv) com inferência de schema.

Criação de tabelas temporárias para consultas SQL.

Agregação e Insights: Execução de queries SQL para calcular métricas como o total de alugueres por tipo de clima e dia da semana.

🚀 Como Visualizar
Como o arquivo está no formato .ipynb, pode visualizá-lo diretamente aqui no GitHub. Se desejar executar o código:

Importe o arquivo para o seu Workspace no Databricks.

Certifique-se de que tens um cluster ativo.

Executa as células para processar os dados em tempo real.

Dica de Personalização:
