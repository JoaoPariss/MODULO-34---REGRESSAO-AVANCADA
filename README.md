# MÓDULO 34 - Regressão: Conceitos Avançados

Neste projeto, utilizei uma base de dados para prever o valor do aluguel a partir de diferentes variáveis usando regressão polinomial.

1. **Importação e preparação dos dados**  
   Importei as bibliotecas necessárias, carreguei a base e selecionei a variável **Valor Condomínio** como preditora (`X`), por ser a segunda variável com maior correlação com o valor do aluguel.

2. **Transformação polinomial (grau 2)**  
   Apliquei o `PolynomialFeatures` com grau 2 para expandir as características de `X`, permitindo capturar relações não lineares entre a variável preditora e o aluguel.

3. **Divisão dos dados**  
   Separei os dados em conjuntos de treino e teste para avaliar o desempenho do modelo em dados que não foram usados no treinamento.

4. **Treinamento e avaliação do modelo (grau 2)**  
   Treinei o modelo de regressão polinomial com os dados de treino e fiz previsões no conjunto de teste. Avaliei o desempenho usando métricas como R² e Mean Squared Error, além de plotar o gráfico do ajuste.

5. **Repetição com grau 4**  
   Repiti todo o processo utilizando grau 4 na transformação polinomial para verificar se o aumento do grau melhora o ajuste e a capacidade preditiva do modelo.

Ao final, comparei os resultados dos modelos de grau 2 e grau 4, concluindo que o modelo com grau 4 foi superior, apresentando melhor desempenho na previsão do valor do aluguel.
