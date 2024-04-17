# Geração de Dados e Data Warehouse

Este projeto consiste em um script Python desenvolvido para gerar dados simulados de vendas e produtos, armazená-los em arquivos CSV e, em seguida, integrá-los em um "data warehouse" usando a biblioteca pandas. O objetivo é fornecer uma ferramenta útil para aprendizado e prática em manipulação de dados e integração de conjuntos de dados heterogêneos.

## Dados Gerados, código 1:
![Print Google Colab](https://i.imgur.com/jpSPuNI.png)

Os dados gerados incluem informações sobre produtos e vendas:

- **Produtos:** Cada produto é caracterizado por um `ID único`, um `nome descritivo` e uma `categoria`, que pode ser 'Eletrônicos', 'Roupas' ou 'Alimentos'.
- **Vendas:** Cada venda registra a `data da transação`, o `ID do produto vendido`, a `quantidade vendida` e o `valor total da transação`.

Os dados são gerados de forma aleatória para fornecer uma variedade de cenários e cenários de análise.

## Resultados do Código

Os resultados obtidos a partir da execução do código incluem:

- Geração de dados simulados de vendas e produtos.
- Armazenamento desses dados em arquivos CSV ('vendas.csv' e 'produtos.csv').
- Mesclagem dos dados em um único conjunto de dados representando um "data warehouse" ('data_warehouse.csv').

## Acesso ao Google Colab

O código utilizado neste projeto está disponível no [Google Colab](https://colab.research.google.com/drive/1lb7AyWNA10QpnyAtfmnO6WTBD3E-8jer?usp=sharing). Você pode acessá-lo e executá-lo diretamente no seu navegador.
