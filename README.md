# Previsão de Custos de Seguro Saúde

Este projeto tem como objetivo entender e prever os custos de seguro saúde com base em fatores pessoais e demográficos.

## Entendimento do Problema

Muitos fatores que afetam quanto você paga pelo seguro saúde não estão sob seu controle. No entanto, é bom entender o que são esses fatores. Aqui estão alguns fatores que afetam quanto custam os seguro saúde:

- **Idade:** Idade do beneficiário principal.
- **Sexo:** Sexo do contratante de seguros (feminino, masculino).
- **IMC:** Índice de massa corporal, fornecendo uma compreensão do corpo, pesos relativamente altos ou baixos em relação à altura.
- **Filhos:** Número de filhos cobertos por seguro saúde / Número de dependentes.
- **Fumante:** Hábito de fumar.
- **Região:** Área residencial do beneficiário nos EUA (nordeste, sudeste, sudoeste, noroeste).

## Modelos Utilizados

Utilizamos dois modelos de machine learning para prever os custos:

1. **Regressão Linear**
2. **KNN (K-Nearest Neighbors)**

## Resultados

- **Regressão Linear:**
  - Erro Quadrático Médio (EQM): 5603.86
  - Erro Absoluto Médio (MAE): 57.38

- **KNN (K-Nearest Neighbors):**
  - Erro Quadrático Médio (EQM): 4596
  - Erro Absoluto Médio (MAE): 48

Os resultados indicam que o modelo KNN apresentou um desempenho superior ao da Regressão Linear, com menores valores de EQM e MAE.

## Implicações

Este projeto demonstra a importância de escolher o modelo certo para o tipo de dados que estamos analisando. O KNN, por sua natureza não paramétrica, conseguiu prever os custos de forma mais precisa, o que pode ser crucial para seguradoras ao definir políticas de preços mais justas e personalizadas.

## Considerações Finais

A análise dos custos de seguro saúde é um campo vasto e em constante evolução. Este projeto é um passo em direção a um entendimento mais profundo de como diversos fatores influenciam nos custos. Futuras melhorias podem incluir a incorporação de mais variáveis ou o uso de técnicas de machine learning mais avançadas para aumentar ainda mais a precisão das previsões.

---
