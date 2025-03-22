# Dp-100_Challenge1

Projeto de Previsão de Vendas de Sorvetes com Azure Machine Learning

O projeto teve como objetivo prever a quantidade de vendas de sorvetes com base na temperatura do dia, utilizando técnicas de regressão linear no Azure Machine Learning. Para isso, foi utilizada a base de dados Sorvetes_ML, composta por duas colunas: Vendas e Temperatura.

A abordagem foi implementada utilizando o Azure Machine Learning Designer, que permite criar pipelines de machine learning de forma visual e intuitiva. Primeiramente, os dados foram carregados e submetidos a um processo de pré-processamento, incluindo a remoção de valores nulos e a normalização das variáveis.

Em seguida, um modelo de Regressão Linear foi treinado para identificar a relação entre a temperatura e as vendas de sorvetes. A métrica de desempenho utilizada para avaliar o modelo foi o erro médio quadrático (MSE). Após a validação, o modelo foi implantado como um endpoint no Azure, permitindo sua integração com outros sistemas para fornecer previsões em tempo real.

Com essa solução, foi possível obter insights sobre o impacto da temperatura nas vendas, auxiliando na tomada de decisões estratégicas para otimizar o estoque e o planejamento de produção.
