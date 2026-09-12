# superstore-sales-dashboard
# Relatório Comercial — Análise de Faturamento e Performance de Vendas
 
Case study de Business Intelligence: dashboard interativo em Power BI para análise de faturamento, produtos, categorias, regiões e desempenho comercial.
 
**Dashboard:** [link do Power BI aqui]
**Portfólio:** [link do seu site Wix aqui]
 
## Objetivo
 
Desenvolver uma solução de Business Intelligence a partir de uma base real de vendas, transformando registros brutos de transações em uma visão consolidada do negócio, com foco em acompanhamento de faturamento e apoio à tomada de decisão.
 
## Fonte dos dados
 
**Sample Superstore Dataset** — dados reais de vendas (2014–2017) de uma rede varejista americana de móveis, suprimentos de escritório e tecnologia.
Disponível em: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final
 
> O dataset não está incluído neste repositório (arquivo de terceiros). Baixe diretamente do Kaggle para reproduzir a análise.
 
## Processo
 
1. **Análise exploratória** (`eda_superstore.ipynb`) — estrutura, tipos de dados, valores ausentes, duplicidades e inconsistências.
2. **Tratamento dos dados (ETL)** — padronização e limpeza no Power Query.
3. **Modelagem e construção** — medidas em DAX, hierarquia de datas, visuais organizados por página.
4. **Validação** — indicadores confrontados com a base original.
## Como rodar o EDA
 
```bash
pip install pandas
python eda_superstore.py "Sample - Superstore.csv"
```
Script para estudo exploratório dos dados:
- Estrutura geral (linhas, colunas, tipos de dados)
- Valores ausentes por coluna
- Linhas duplicadas
- Consistência de categorias, datas e valores numéricos
- Estatísticas descritivas
- Resumo de negócio (faturamento por categoria e região)
## Principais insights
 
- As três categorias (Tecnologia, Móveis, Suprimentos de Escritório) têm participação equilibrada no faturamento, sem concentração dominante.
- Os 3 produtos mais vendidos representam apenas ~5% da receita — cauda longa relevante.
- A região Oeste lidera o faturamento; a região Sul é a menos representativa.
- Descontos acima de determinado patamar (até 80%) geram prejuízo em parte dos pedidos.

## Tecnologias
 
Excel · Power Query · Power BI · DAX · Python (Pandas)
