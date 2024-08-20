
# Estudo de viabilidade técnica para uso da espectroscopia Vis-NIR no monitoramento da qualidade em uvas de mesa

Este projeto visa melhorar a qualidade das uvas de mesa, tanto brancas quanto tintas, utilizando técnicas avançadas de espectroscopia de refletância no visível e infravermelho próximo (Vis-NIR). Por meio da análise espectral dessas variedades de uvas, buscamos desenvolver modelos preditivos que possam identificar e quantificar atributos de qualidade importantes. Além disso, o projeto se concentra em encontrar os melhores pré-processamentos para os sinais espectrais e em identificar assinaturas espectrais específicas que indiquem a qualidade das uvas. Esta iniciativa é voltada para pesquisadores, agrônomos, e produtores que buscam otimizar a qualidade dos seus produtos utilizando tecnologias de ponta.




## Apêndice

### Algoritmos de Pré-processamento
Os seguintes algoritmos de pré-processamento foram utilizados para preparar os dados espectrais:

- MSC (Multiplicative Scatter Correction): Correção multiplicativa de espalhamento para ajustar a variabilidade dos dados espectrais.
- SNV (Standard Normal Variate): Padronização normal de sinal para corrigir variações de intensidade e melhorar a comparabilidade entre amostras.
- SG (Savitzky-Golay Derivative): Aplicação da primeira derivada de Savitzky-Golay para realçar características espectrais e reduzir ruídos.

### Análise Exploratória
- PCA (Principal Component Analysis): Utilizado para a análise exploratória dos dados, PCA ajuda a identificar padrões e estruturas latentes na matriz espectral, facilitando a visualização e compreensão dos dados.

### Modelos Preditivos
Os seguintes modelos foram aplicados para análise e predição dos atributos das uvas:

- PLSR (Partial Least Squares Regression): Regressão por Mínimos Quadrados Parciais, utilizada para modelar relações entre variáveis espectrais e atributos de qualidade.
- PCR (Partial Components Regression): Regressão por Componentes Parciais, aplicável para reduzir a dimensionalidade dos dados e prever atributos.
- SVM (Support Vector Machine): Máquinas de Vetores de Suporte, empregadas para classificação e regressão de dados espectrais.
- RF (Random Forest): Florestas Aleatórias, utilizadas para modelar e prever os atributos das uvas com base em múltiplos modelos de decisão.



## Status
### Status Atual: *Em Testes*

Os algoritmos de pré-processamento e modelos preditivos estão atualmente em fase de testes. É importante observar que os resultados podem variar conforme os parâmetros utilizados e a configuração dos dados específicos. Para que as funções e modelos funcionem adequadamente com seus dados, é necessário ajustar os parâmetros conforme a natureza dos dados espectrais que você está utilizando. Siga estas diretrizes:

- Pré-processamento
Os algoritmos de pré-processamento, como MSC, SNV e SG, podem precisar de ajustes nos parâmetros para otimizar o desempenho com diferentes conjuntos de dados. 

- Modelos Preditivos
Em breve: Cada modelo preditivo (PLSR, PCR, SVM, RF) possui parâmetros que podem ser ajustados para melhorar a precisão das previsões. Consulte os notebook dos modelos de análise para orientações sobre como ajustar os parâmetros de cada modelo com base nos seus dados específicos.

- Instruções de Ajuste 
Em breve no notebook de pré-processamento e dos modelos preditivos você encontrará células específicas para configuração de parâmetros. Revise essas células e ajuste os valores conforme necessário para melhor adaptar o processo aos seus dados.