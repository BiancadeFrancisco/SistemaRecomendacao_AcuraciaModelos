# SistemaRecomendacao_MetricasAcuracia

## Descrição Projeto

**Conjunto de dados:**
- Banco de dados contendo descrição de filmes (MovieLens), com sua identificação, ano de estreia e gêneros.
- Dataset pré-processado contendo a as métricas de validação dos modelos de recomendação: Top, ItemKNN e funkSVD. 
Obs: para obter o dataset com as métricas dos modelos, os mesmos foram treinados utilizando o dataset do MovieLens. O conjunto de validação é formado por 20% dos dados mais recentes do dataset.

**Arquivo:** .parquet

**Objetivo:**
Avaliar a qualidade da recomendação dos seguintes modelos: Top, ItemKNN e funkSVD.

**Observação:**
•	Top (Recomendação Não-personalizada)
•	ItemKNN (Collaborative Filtering)
•	FunkSVD (Collaborative Filtering)

**IDE:** Colab

**Linguagem:** Python 

**Principais bibliotecas utilizadas:**
•	Rexmex, biblioteca que contém diversas métricas atualizadas para linguagem Python;
•	Pandas, para manipulação e tratamento dos dados;
•	Matplotlib, visualização gráfica dos dados;
•	Cycler, utilizada para criar paletas de cores personalizadas nos gráficos;
•	Google.colab, para importar arquivos da núvem;
•	
**Resultado:**
Foi possível analisar graficamente as métricas dos 3 modelos de recomendação citados, plotando gráficos que demonstram como as recomendações personalizadas (ItemKNN e funkSVD) possuem maiores alcances e melhores métricas, comparadas a recomendação sem personalização (Top).
