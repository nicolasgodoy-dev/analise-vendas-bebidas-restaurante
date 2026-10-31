# Análise de Vendas de Bebidas em Restaurante

Projeto de estudo em análise de dados, feito em Python no Visual Studio Code a partir do vídeo do canal [Eficiência Programada](https://www.youtube.com/@eficienciaprogramada).

O notebook lê uma planilha Excel com o movimento e o consumo de produtos de duas unidades de um restaurante, entre agosto e setembro de 2025. A partir dela, compara como cada unidade vende bebidas.

## O que o projeto faz

- Lê as duas abas da planilha `dados.xlsx`: **Por Canal** (movimento diário e número de pessoas) e **Consumo de Produtos**
- Filtra as categorias **Drinks** e **Soft Drinks**
- Calcula o total de clientes atendidos por loja
- Soma a quantidade de bebidas vendidas por loja e categoria
- Calcula a quantidade de bebidas por cliente
- Lista os 5 produtos mais vendidos de cada categoria em cada loja
- Gera um gráfico de barras horizontais com o resultado


## Ferramentas

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Visual Studio Code

## Conceitos praticados

- Leitura de Excel com `read_excel`
- Filtros com `isin`
- Agrupamentos com `groupby`
- Ordenação com `sort_values` e seleção dos primeiros itens com `head`
- Divisão entre séries do Pandas
- Gráficos com Matplotlib (`barh` e `bar_label`)

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/nicolasgodoy-dev/analise-vendas-bebidas-restaurante.git
   cd analise-vendas-bebidas-restaurante
   ```
2. Instale as dependências:
   ```bash
   pip install pandas matplotlib openpyxl ipykernel
   ```
3. Abra a pasta do projeto no **Visual Studio Code** (com as extensões Python e Jupyter instaladas), abra o arquivo `drinks.ipynb`, escolha o interpretador Python e execute as células.

Mantenha o arquivo `dados.xlsx` na mesma pasta do notebook.

## Arquivos

- `drinks.ipynb`: notebook com a análise
- `dados.xlsx`: dados usados no projeto
- `grafico_bebidas_por_cliente.png`: gráfico com o resultado

## Créditos

Dados e roteiro do projeto baseados no vídeo [Eficiência Programada](https://youtu.be/RFJopzRpCJY).