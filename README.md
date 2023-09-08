# Projeto de Econometria I

Este é um projeto de econometria desenvolvido por Iuri Soares, Mariana Tinouco e Miguel Melo como parte do curso de Econometria I. O projeto envolve análise de dados econômicos e a aplicação de modelos econométricos para entender e interpretar os resultados. Este README fornecerá uma visão geral do projeto, seu conteúdo e como utilizá-lo.

## Sumário

## Sumário

1. [Introdução](#introdução)
   1.1 [Objetivo do Projeto](#objetivo-do-projeto)
   1.2 [Equipe de Trabalho](#equipe-de-trabalho)
2. [Importação de Dados e Bibliotecas](#importação-de-dados-e-bibliotecas)
   2.1 [Importação de Pacotes e Bibliotecas](#importação-de-pacotes-e-bibliotecas)
   2.2 [Importação dos Dados](#importação-dos-dados)
      2.2.1 [Dataframe](#dataframe)
3. [Análise Gráfica](#análise-gráfica)
   3.1 [Cálculo da Volatilidade](#cálculo-da-volatilidade)
   3.2 [Gráfico das Volatilidades](#gráfico-das-volatilidades)
   3.3 [Gráfico de Retornos](#gráfico-de-retornos)
   3.4 [Gráfico de Boxplot](#gráfico-de-boxplot)
   3.5 [Gráfico de Linhas](#gráfico-de-linhas)
   3.6 [Gráfico de Histograma](#gráfico-de-histograma)
   3.7 [Gráfico de Dispersão](#gráfico-de-dispersão)
   3.8 [Mapa de calor](#mapa-de-calor)
   3.9 [Explicação dos Gráficos e do Dataframe](#explicação-dos-gráficos-e-do-dataframe)
4. [Modelo OLS](#modelo-ols)
   4.1 [Explicação do .summary()](#explicação-do-summary)
   4.2 [Plotando os Residuais](#plotando-os-residuais)
      4.2.1 [Explicação do Gráfico Residuais x Fitted Values](#explicação-do-gráfico-residuais-x-fitted-values)
5. [Testes de Heterocedasticidade](#testes-de-heterocedasticidade)
   5.1 [Breush-Pagan Test](#breush-pagan-test)
      5.1.1 [Análise do Teste Breush-Pagan](#análise-do-teste-breush-pagan)
   5.2 [White Test (Cross Terms)](#white-test-cross-terms)
      5.2.1 [Análise do White Test (Cross Terms)](#análise-do-white-test-cross-terms)
6. [Modelo WLS](#modelo-wls)
   6.1 [Calculando Pesos (Weights)](#calculando-pesos-weights)
   6.2 [Construindo o Modelo WLS](#construindo-o-modelo-wls)
      6.2.1 [Explicação do .summary()](#explicação-do-summary)
7. [Autocorrelação](#autocorrelação)
   7.1 [Explicação do .summary()](#explicação-do-summary)


## Visão Geral do Projeto

Este projeto de Econometria I envolve a análise de dados econômicos e a aplicação de modelos econométricos para avaliar e compreender as relações subjacentes aos dados. A equipe de trabalho é composta por Iuri Soares, Mariana Tinouco e Miguel Melo, que colaboraram para realizar análises estatísticas, criar visualizações gráficas e interpretar os resultados.

## Como Utilizar

Para explorar o projeto e suas análises, siga as instruções abaixo:

1. **Acesse o Código-Fonte:** O código e os notebooks utilizados neste projeto estão disponíveis neste repositório do GitHub. Você pode baixar ou clonar os arquivos para o seu computador.

2. **Execute o Código:** Utilize um ambiente de desenvolvimento Python (como Jupyter Notebook ou Google Colab) para executar o código contido nos notebooks.

3. **Analise os Gráficos:** Explore as visualizações gráficas geradas para compreender os dados e os resultados da análise.

4. **Leia as Explicações:** Dentro dos notebooks, você encontrará explicações detalhadas sobre cada etapa da análise, incluindo interpretações dos gráficos e resultados estatísticos.

## Contribuições

Contribuições para aprimorar e expandir este projeto são bem-vindas. Se você identificar melhorias, erros ou tiver sugestões adicionais, sinta-se à vontade para abrir problemas (issues) ou enviar solicitações de pull request.

## Agradecimentos

Agradecemos ao corpo docente da disciplina de Econometria I por fornecer orientações e recursos valiosos para a realização deste projeto. A experiência adquirida neste curso tem sido fundamental para o nosso aprendizado e crescimento na área de econometria.

