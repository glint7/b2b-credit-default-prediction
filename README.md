# Previsão de Inadimplência para Micro e Pequenas Empresas (MPEs) com Machine Learning

## Descrição Resumida
Projeto de análise preditiva focado em identificar a probabilidade de inadimplência de micro e pequenas empresas, utilizando técnicas de machine learning. O objetivo é apoiar instituições financeiras na tomada de decisão de crédito, reduzindo riscos e aumentando a rentabilidade da carteira B2B.

## Problema de Negócio
Pequenas empresas representam uma parcela significativa das operações de crédito, mas apresentam altos índices de inadimplência. Muitos modelos tradicionais falham ao capturar fatores comportamentais, como a maturidade financeira da empresa, que impactam diretamente no risco de crédito.

## Objetivo do Projeto
Desenvolver um modelo preditivo que:
- Estime a probabilidade de inadimplência de MPEs.
- Incorpore variáveis financeiras e comportamentais (ex.: maturidade financeira).
- Apoie decisões mais assertivas no processo de concessão de crédito.

## Dataset Utilizado
- Dataset simulado com base em padrões do Banco Central, Serasa e bases públicas do Kaggle.
- Variáveis principais:
  - Score de crédito
  - Faturamento histórico
  - Nível de endividamento
  - Tempo de relacionamento com o banco
  - Maturidade financeira (proxy: tempo de formalização, estrutura contábil)
  - Segmento da empresa

## Tecnologias Utilizadas
- Python 3.x
- Pandas
- Scikit-learn
- LightGBM
- Matplotlib / Seaborn (visualizações)
- Power BI ou Streamlit (visualização final, opcional)

## Metodologia
- Análise exploratória de dados (EDA)
- Pré-processamento e engenharia de features
- Modelagem preditiva (Regressão Logística, Random Forest, LightGBM)
- Avaliação de performance (Accuracy, Precision, Recall, AUC-ROC)
- Interpretação dos resultados e insights de negócio

## Resultados Esperados
- Identificação das principais variáveis que impactam a inadimplência.
- Modelo com capacidade preditiva aplicável em cenários reais.
- Insights acionáveis para a área de risco de crédito em bancos.

## Cronograma de Entrega (21 Dias)
| Etapa                             | Período          |
|------------------------------------|------------------|
| Coleta/Simulações de Dados         | 14/05 a 16/05    |
| EDA + Feature Engineering          | 17/05 a 20/05    |
| Modelagem Preditiva                | 21/05 a 25/05    |
| Validação e Interpretação          | 26/05 a 28/05    |
| Visualização e Documentação Final  | 29/05 a 03/06    |

## Dataset
O dataset utilizado neste projeto está disponível [nesta pasta](./data/dataset_inadimplencia_realista_MPE_ptBR.csv).
