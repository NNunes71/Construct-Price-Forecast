# Construct Price Forecast

## Previsão da evolução dos custos de materiais de construção

Projeto final das disciplinas:

- C11 - Python para Análise de Dados
- C13 - Implementação de Modelos Analíticos com Python

## Objetivo

Desenvolver um modelo analítico para analisar a evolução histórica dos índices de custos de materiais de construção e realizar previsões de curto prazo.

O projeto pretende demonstrar como dados históricos podem ser utilizados para apoiar a estimativa futura dos custos de materiais no contexto da gestão de obras.

## Questão de negócio

> Qual será a evolução estimada do custo de um determinado material de construção nos próximos meses, com base na sua evolução histórica e na relação com outros índices de materiais?

## Scope do projeto

O projeto será desenvolvido inicialmente utilizando dados disponibilizados pelo IMPIC relativos aos índices de custos de materiais de construção.

A análise será centrada em:

1. Recolha dos dados históricos do IMPIC;
2. Tratamento e preparação dos dados;
3. Análise exploratória da evolução dos índices;
4. Análise das relações entre diferentes índices de materiais;
5. Construção de modelos de previsão;
6. Previsão de curto prazo;
7. Avaliação dos resultados.

Nesta primeira versão, os potenciais influenciadores serão limitados aos próprios índices disponibilizados pelo IMPIC.

A possibilidade de utilizar futuramente outras fontes de informação, como indicadores económicos, energéticos ou de matérias-primas, fica fora do âmbito deste projeto e poderá ser explorada numa futura implementação no Anturio Construct.

### Metodologia

O projeto seguirá a metodologia CRISP-DM:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modelling
5. Evaluation

## Fontes de dados

### IMPIC

Os índices de custos de materiais de construção publicados pelo IMPIC
constituem a principal fonte de dados do projeto.

Serão utilizados os históricos disponíveis para construir séries temporais
dos índices dos diferentes materiais e desenvolver modelos de previsão.

### Preços de referência

Para transformar os índices previstos em valores monetários, será utilizado
um preço de referência atual para cada material.

A relação entre o preço e o índice permitirá estimar preços para períodos
futuros e, quando aplicável, reconstruir valores equivalentes para períodos
históricos.


### Tecnologias

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git / GitHub

### Influenciadores de custos

O projeto irá também recolher, a partir da informação disponibilizada pelo
IMPIC, a identificação e descrição dos fatores/influenciadores associados
aos índices de materiais.

Nesta fase não serão modeladas as séries temporais desses influenciadores.
A sua utilização como variáveis explicativas dos modelos de previsão será
considerada como uma possível evolução futura do projeto e da plataforma
Anturio Construct.