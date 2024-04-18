# Geração de dados e utilização de Data Warehouse

![Print Google Colab](https://i.imgur.com/kRrBONk.png)

Este projeto consiste em um script Python desenvolvido para gerar dados simulados de vendas e produtos, armazená-los em arquivos CSV e, em seguida, integrá-los em um "data warehouse" usando a biblioteca pandas. O objetivo é fornecer uma ferramenta útil para aprendizado e prática em manipulação de dados e integração de conjuntos de dados heterogêneos.

## Dados gerados código 1:
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

# Dados gerados código 2:
![Print Google Colab](https://i.imgur.com/0XmEz1F.png)
  
## Análise de vendas e desempenho de Produtos

Este trecho contém análises de vendas e desempenho de produtos realizadas a partir de um conjunto de dados de um data warehouse gerado através do código 1 `'data_warehouse.csv'`. As análises foram conduzidas utilizando Python, com o auxílio das bibliotecas Pandas e Matplotlib para manipulação e visualização dos dados, respectivamente.

## Análises Realizadas:

1. **Análise de Vendas por Produto:** Calcula o total de vendas e o valor total das vendas para cada produto listado no data warehouse.

2. **Análise de Vendas por Categoria de Produto:** Agrupa os dados de vendas por categoria de produto, calculando o total de vendas e o valor total das vendas para cada categoria.

3. **Análise de Tendências Temporais:** Converte a coluna de data para o tipo datetime e agrupa as vendas por data, permitindo uma análise das tendências temporais ao longo do período dos dados.

4. **Análise de Desempenho de Produtos:** Calcula o valor total das vendas para cada produto, fornecendo insights sobre o desempenho individual de cada item.

## Resultados:

Os resultados das análises estão disponíveis no arquivo [Datawarehouse_codigo2.ipynb](https://github.com/jesercaceres/Datawarehouse/blob/main/DataWarehouse_codigo2.ipynb)

Além das análises mencionadas, o código também inclui a criação de um gráfico de linha mostrando a quantidade vendida ao longo do tempo.

## Acesso ao Google Colab

O código utilizado nos projetos acima estão disponíveis nos links:

 [Datawarehouse (Código 1)](https://colab.research.google.com/drive/1lb7AyWNA10QpnyAtfmnO6WTBD3E-8jer?usp=sharing). 
 
 [Datawarehouse (Código 2 )](https://colab.research.google.com/drive/1WgOyZp9Sen6DXddz0GupjNdx3APbbCsj?usp=sharing). 

Você pode acessá-los e executar diretamente no seu navegador.
