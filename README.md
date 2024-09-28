# Descrição do Projeto

Este projeto realiza uma análise de dados e envolve processos de limpeza de duplicatas, remoção de valores nulos e tratamento de outliers. O objetivo principal é calcular o lucro e a porcentagem de cashback de cada grupo com base nos dados fornecidos para obter a viabilidade de investimento por grupos.

# Bibliotecas 

Este projeto foi implementado com as seguintes bibliotecas Python:

- pandas: Para manipulação de dados.
- numpy: Para cálculos matemáticos e tratamento de outliers.
- matplotlib e seaborn: Para visualização de dados.

# Descrição final das Colunas agrupadas.

- Grupos de Usuários: Identificação dos diferentes grupos de clientes no dataset.
- Compradores: Número total de compradores em cada grupo.
- Comissão: Valor total da comissão obtida para cada grupo.
- Cashback: Total devolvido como cashback para os compradores em cada grupo.
- Vendas Totais: Total de vendas realizadas em cada grupo.
- Porcentagem de Cashback: Percentual do valor total das vendas devolvido 

# Resultados

O cashback médio geral é de 5,84%, porém ao segmentarmos os dados em grupos, temos: grupo 1 com 4,16%, grupo 2 com 5,78% e grupo 3 com 7,38%. Outra análise que podemos realizar seria em termos de vendas, com os grupos apresentando os seguintes números: 9.633 vendas no grupo 1, 10.460 no grupo 2 e 10.769 no grupo 3. Por fim, para alcançar o melhor desempenho, é essencial calcular os lucros gerados por cada grupo, levando em consideração o cashback e o número de vendas, representando: R$ 404.715, R$ 344.813 e R$ 251.559, respectivamente. Com esses dados, concluímos que, apesar de o grupo 1 ter um número menor de vendas, a diferença em relação aos outros grupos não é tão significativa então o cashback mais baixo resulta em maior lucratividade, indicando que a taxa de 4,16% de cashback é a mais vantajosa nesse contexto.
