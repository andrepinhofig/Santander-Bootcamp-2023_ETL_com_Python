<div align="center">
<h1>Santander Bootcamp 2023 <br> Ciência de Dados com Python</h1>
<img src="https://hermes.dio.me/tracks/03253ff0-95b9-4904-84e7-2063e9d6cb26.png" alt="Logo Bootcamp" width="220">
</div>

##  Desafio Original DIO: Explorando IA Generativa em um Pipeline de ETL com Python
Desafio original da DIO:

<a target="_blank" href="https://colab.research.google.com/drive/1SF_Q3AybFPozCcoFBptDSFbMk-6IVGF-?usp=sharing#scrollTo=k5fA5OrXt1a3">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Entendendo o desafio
Inspirado pelo projeto modelo o aluno deve replicar ou reimaginar uma pipeline ETL utilizando Python.

## Meu projeto 
Imaginando uma loja de produtos esportivos meu desafio foi criar um pipeline ETL para extrair dados de vendas de um arquivo CSV, realizar algumas transformações simples como cálculo de total de vendas por produto e por período e por fim realizar carregamento dos dados transformados em um novo arquivo CSV além de criar uma visualização em tela para mostrar o resultados por meio de gráficos.

## Etapas do Pipeline de ETL
### :white_check_mark: Extract
Nesta etapa vamos extrair os dados de vendas do arquivo `dados-venda.csv`. Este arquivo traz informações referentes ao ano de 2023 considerando o período de janeiro a agosto. As colunas contidas no arquivo são as seguintes: `Produto`, `Data`, `Quantidade` e `Valor`.

### :white_check_mark: Transform
Agora vamos calcular o total de vendas por produto e por mês.

### :white_check_mark: Load
 Salvando os dados transformados em um novo arquivo CSV e gerando gráfico de barras e de linha usando a biblioteca `Matplotlib`

## Notebook do meu projeto no Google Colab
<a target="_blank" href="https://colab.research.google.com/github/walterowisk/DIO_LabProject-Pipeline-ETL-Python/blob/main/DIO_LabProject_Pipeline_ETL_Analisando_Dados_de_Venda.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
