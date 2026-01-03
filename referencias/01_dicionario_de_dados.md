# Dicionário de dados

Fonte dos dados: [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)

Origem dos dados: conjunto público disponibilizado no Kaggle, voltado à detecção de fraudes em transações com cartão de crédito.

| Nome da coluna | Descrição             | Tipo de dado |
|----------------|-----------------------|--------------|
| `Time`         | Tempo decorrido, em segundos, desde a primeira transação registrada no conjunto de dados | float     |
| `Vx`           | Variáveis derivadas por meio da Análise de Componentes Principais (PCA), representando combinações das variáveis originais | float   |
| `Amount`       | Valor monetário associado a cada transação | float         |
| `Class`        | Indicador da transação: 0 para operação legítima e 1 para operação fraudulenta | int        |

##### Descrição das variáveis
Devido a restrições relacionadas à privacidade e segurança das informações, as variáveis originais do conjunto de dados não são disponibilizadas. Em seu lugar, a maior parte dos atributos foi transformada utilizando a Análise de Componentes Principais (PCA).

As variáveis identificadas como V1, V2, ..., V28 correspondem a componentes principais gerados a partir dessa técnica estatística, cujo objetivo é reduzir a dimensionalidade dos dados, preservando o máximo possível da variabilidade original. Essas transformações permitem a realização de análises e modelagens sem expor informações sensíveis. Ao longo do trabalho, serão discutidos alguns impactos dessa transformação nos resultados obtidos.
