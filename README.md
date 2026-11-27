# Impacto dos Atrasos nas Entregas sobre e a Satisfação dos Clientes (Olist)
Projeto Integrador: Ciência de Dados Aplicada a Situações de Mercado (Senac), 1.ª entrega.

## Problema
Os atrasos nas entregas afetam a satisfação dos clientes? Este projeto busca analisar a relação entre o atraso em relação a data estimada de entrega e a nota de avaliação ('review_score') dos pedidos na base da Olist, além de identificarmos categorias, regiões e até períodos que concentram mais atrasos.


## Dados
Brazilian E-Commerce Public Dataset by Olist (2016–2018) - (https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Tabelas utilizadas: olist_order_items_dataset, olist_costumers_dataset, olist_order_items_dataset, olist_orders_dataset e olist_order_reviews_dataset.


## Principais resultados
- 96.478 pedidos com status `delivered`, base ampla para cruzar logística e satisfação.
- Categorias com mais pedidos atrasados: `cama_mesa_banho` e `beleza_saude`.
- Sudeste concentra o maior volume absoluto de atrasos (4.048 pedidos).
- Picos de atraso em novembro de 2017 e março de 2018.
- Média de `review_score` cai de 4,29 (no prazo) para 3,29 (até 3 dias de atraso) e 2,11 (até 7 dias).


## Tecnologias
- Python (utilizadas as bibliotecas pandas, numpy, matplotlib e integração com Kaggle feita via kagglehub)
- Google Colab


## Equipe
- IAN INAGAKI SANTOS   
- KATHLEEN DE OLIVEIRA MAIA   
- LUIZ FELIPE DA SILVA LEITE   
- MARTA PEREIRA SANTOS   
