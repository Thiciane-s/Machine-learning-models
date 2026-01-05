# Machine learning models

Este repositório tem como objetivo reunir implementações de **modelos de Machine Learning**, desenvolvidos tanto de forma **manual** quanto utilizando bibliotecas consolidadas da área.

Cada pasta corresponde a um modelo diferente, contendo código e o dataset.


## [Regressão Linear](https://github.com/Thiciane-s/Machine-learning-models/tree/main/Regress%C3%A3o)

O primeiro modelo implementado é a **Regressão Linear Simples**, aplicada ao dataset de salários em função dos anos de experiência.

### Objetivo

- Implementar a regressão linear **do zero**, usando apenas Python e pandas  
- Comparar os resultados com a implementação do **Scikit-Learn**  
- Validar matematicamente os coeficientes e métricas

---

## Fórmulas Utilizadas

Coeficiente angular:

$b_1 = \frac{\sum (x_i - \bar{x})(y_i - \bar{y})}{\sum (x_i - \bar{x})^2}$

Intercepto:

$b_0 = \bar{y} - b_1 \bar{x}$

Predição:

$\hat{y} = b_0 + b_1 x$

---

## Métricas de Avaliação

- **RMSE** – Raiz do Erro Quadrático Médio  
- **R²** – Coeficiente de Determinação

As métricas dos dois modelos são comparadas em um DataFrame.

---

## Visualização

O gráfico gerado apresenta:

- Pontos reais do dataset  
- Reta do modelo manual  
- Reta do modelo Scikit-Learn  

As retas praticamente se sobrepõem, validando a implementação.

---
