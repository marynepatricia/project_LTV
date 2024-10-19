# Life time value (LTV)

Este algoritmo calcula o LTV de novos clientes através de um modelo de regressão linear gerado e treinado por dados preliminares.

## O que foi feito:

- Carregamento e inspecionamento dos dados;
- Eliminação de parte do dataframe que não seria necessário para a análise;
- Análise de correlação das variáveis independentes com a variável dependente;
- Treinamento e teste do modelo;
- Construção de um modelo de Regressão Linear;
- Testes do modelo de regressão;
- Aplicação do modelo gerado na simulação de calculo de LTV para um novo cliente com base nos gastos dos três primeiros meses.

## O que foi concluido:

Os dados fornecidos mostraram-se adequados para serem utilizados como variáveis independentes no cálculo do LTV, devido à sua correlação com esse indicador. Além disso, o modelo de regressão linear gerado apresentou um coeficiente de determinação (R²) superior a 0.90, demonstrando uma excelente capacidade preditiva em relação ao valor alvo.