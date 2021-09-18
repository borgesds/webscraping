![question22](/images/614.png)

# Loja de Roupas Masculinas

**Aviso:** O seguinte contexto é completamente fictício, a empresa, o contexto, o CEO, as questões de negócios existem apenas para elaboração desse contexto.

Dois empresários estão querendo expandir seus negócios para os Estados Unidos, e pediram uma ajuda para buscar informações em uma loja conceituada nos EUA. Esses empresários gostariam de começar um E-commerce voltado no começo para venda de calças masculinas..

Com uma visão para o mercado dos EUA eles apresentaram um relatório Research & Markets que aponta que o mercado global de beleza masculinaalcançou o valor de US$ 57,7 bilhões em 2017, segundo relatório da [Research & Markets](https://forbes.com.br/?s=Research+%26+Markets). A previsão da consultoria é de que a soma chegue aos US$ 78,6 bilhões em 2023. O mercado brasileiro é o segundo maior do mundo, atrás apenas dos EUA. “Quando se fala em cosméticos, o Brasil está sempre nas primeiras colocações dos [rankings](https://forbes.com.br/?s=rankings)”, afirma o coordenador de varejo da FGV, Maurício Morgado. E querem está nesse primeiro lugar do consumismo masculino.

# Problema de Negócio

Nesse contexto, você foi contratado como consultor de Data Science para extrair dados de plataformas E-commerce mais populares nos EUA e construir um modelo que mostre o tipo de calças, preços, materiais e outros dados relevantes para montar uma base para fabricação desses novos produtos.

Com a solução, os clientes prever o foco total em produtos com um preço mais atrativo e redução de insumos ou substituição.

# Planejamento da Solução

## Qual é a solução?
É necessário retirar os dados dos sites concorrentes para essa avaliação usando o Web scraping que é o processo de coleta de dados estruturados da web de maneira automatizada.

## Como será a solução?
Será gerado o modelo em csv, deixando disponibilizado para os clientes a tabela e depois de um ok do cliente os próximos passos  é produzir dashboard para analises.

## Hospedagem
A hospedagem será feita no banco de dados local e terá coletas realizadas duas vezes na semana.

## Tabela - Método de Entrega

Recebe os atributos referente os produtos coletados.



##  Modelo

**Web Scraping**

| product_id | product_category | product_name         | product_price | scrapy_datetime     | style_id | color_id | color_name               | Fit        | size_number | size_model | contton | polyester | elasterell | elastane |
| ---------- | ---------------- | -------------------- | ------------- | ------------------- | -------- | -------- | ------------------------ | ---------- | ----------- | ---------- | ------- | --------- | ---------- | -------- |
| 690449022  | men_jeans_ripped | skinny_jeans         | 39.99         | 2021-08-16 16:00:46 | 690449   | 22       | light_denim_blue/trashed | skinny_fit | 187         | 32/32      | 0.98    | 0.0       | 0.0        | 0.02     |
| 690449022  | men_jeans_ripped | skinny_jeans         | 39.99         | 2021-08-16 16:00:46 | 690449   | 22       | denim_blue               | skinny_fit | 187         | 32/32      | 0.98    | 0.0       | 0.0        | 0.02     |
| 690449022  | men_jeans_ripped | skinny_jeans         | 39.99         | 2021-08-16 16:00:46 | 690449   | 22       | light_denim_blue         | skinny_fit | 187         | 32/32      | 0.98    | 0.0       | 0.0        | 0.02     |
| 427159006  | men_jeans_ripped | trashed_skinny_jeans | 39.99         | 2021-08-16 16:00:46 | 427159   | 6        | blue_washed_out          | skinny_fit | 184         | 31/32      | 0.93    | 0.06      | 0.0        | 0.01     |
| 427159006  | men_jeans_ripped | trashed_skinny_jeans | 39.99         | 2021-08-16 16:00:46 | 427159   | 6        | dark_denim_blue          | skinny_fit | 184         | 31/32      | 0.93    | 0.06      | 0.0        | 0.01     |
| 427159006  | men_jeans_ripped | trashed_skinny_jeans | 39.99         | 2021-08-16 16:00:46 | 427159   | 6        | black_washed_out         | skinny_fit | 184         | 31/32      | 0.93    | 0.06      | 0.0        | 0.01     |

## Modelo Final
O modelo final é apresentado para uma avaliação das categorias dos produtos, se o modelo estiver no padrão desejado será feito as analise de negócio e apresentar os dashboard.

#  Conclusão
Ao Final desta primeira parte do projeto foi possível compreender como é a retirada de dados de um web site  e como é utilizado para os resultados da pesquisa com base em coisas como padrões de uso reais. A quantidade de informações que se pode retirar com web scraping só com informações primarias visualizando dentro do sites são enormes e podem ser catalogadas e transformadas e soluções diversas.

#  Próximos Passos

Iniciar mais um ciclo para analisar o problema buscando abordagens diferentes, tendo em vista principalmente a construção de dashboard.

Possíveis pontos para serem abordados no segundo ciclo:

-**Estatística**

-**Power BI**

-**Tableau**

-**Adicionar mais produtos**

