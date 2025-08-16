# super_store_sql_project

Este projeto demonstra o uso de **SQL para limpeza, análise e imputação de dados** em uma loja fictícia (Super Store).

## Objetivos do Projeto

1. **Top 5 produtos por categoria**
   - Identificar os 5 principais produtos de cada categoria com base nas maiores vendas totais.
   - Classificação: por categoria (crescente) e vendas (decrescente dentro da categoria).
   - Colunas da saída: 
     - `category`
     - `product_name`
     - `product_total_sales`
     - `product_total_profit`
     - `product_rank`

2. **Imputação de valores ausentes**
   - Calcular a quantidade dos pedidos com valores ausentes na coluna `quantity`.
   - Determinar o preço unitário de cada produto considerando desconto, mercado e região.
   - Estimar a quantidade faltante e salvar em `calculated_quantity`.
   - Colunas da saída:
     - `product_id`
     - `discount`
     - `market`
     - `region`
     - `sales`
     - `quantity`
     - `calculated_quantity`

