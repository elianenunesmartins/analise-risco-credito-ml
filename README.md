#  Contexto

Este projeto foi desenvolvido como parte do desafio do Bootcamp de Dados&GenAI da DIO em parceria com o Bradesco, com o objetivo de utilizar Inteligência Artificial como ferramenta de aprendizagem ativa.
O tema que escolhi foi a aplicação de Machine Learning na análise de risco de crédito, explorado por meio da criação de um caderno temático no NotebookLM.


#  Objetivo

Entender como modelos de Machine Learning são utilizados para prever inadimplência \
Comparar diferentes algoritmos aplicados ao risco de crédito \
Analisar métricas utilizadas na avaliação dos modelos \
Explorar a importância da explicabilidade em modelos financeiros

##  Notebook

Acesse o caderno temático desenvolvido no NotebookLM: \
https://notebooklm.google.com/notebook/5723f379-e4fa-448f-a488-546c110368c5

# Curadoria de Fontes

Foram selecionados artigos acadêmicos recentes com foco na aplicação de Machine Learning em risco de crédito, priorizando materiais com abordagem prática, comparação de modelos e uso de dados reais.

1. Machine Learning for Credit Risk Assessment (2024)  
https://www.researchgate.net/publication/385863348_Machine_learning_for_credit_risk_assessment_and_scoring  

2. Credit Risk Scoring Analysis Based on Machine Learning Models  
https://www.researchgate.net/publication/338526492_Credit_Risk_Scoring_Analysis_Based_on_Machine_Learning_Models  

3. Credit Risk Analysis: Performance of Machine Learning Techniques (2024)  
https://www.researchgate.net/publication/397015681_Credit_Risk_Analysis_An_Assessment_of_the_Performance_of_Six_Machine_Learning_Techniques_in_Credit_Scoring_Modelling  

4. Credit Risk in Emerging Markets (2025)  
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5570578  

5. Explainable AI for Credit Risk  
https://arxiv.org/abs/2009.13384  


# Engenharia de Prompts e Aprendizados

Durante o desenvolvimento do projeto, foram testados diferentes tipos de prompts para avaliar como o nível de detalhamento impacta a qualidade das respostas.

###  Prompt 1 — Abordagem geral

"Explique como Machine Learning é aplicado na análise de risco de crédito"

Resultado:
A resposta apresentou uma visão geral bem estruturada, incluindo modelos, métricas e desafios, porém com foco mais conceitual.

Aprendizados:
- Prompts mais amplos geram respostas organizadas, mas pouco específicas
- O nível de detalhamento influencia diretamente na utilidade da resposta

---

###  Prompt 2 — Com direcionamento

"Explique como aplicar Machine Learning na análise de risco de crédito utilizando um dataset real, descrevendo passo a passo"

Resultado:
A resposta passou a seguir uma estrutura mais próxima de um pipeline, incluindo etapas como pré-processamento, engenharia de features, treinamento e avaliação.

Aprendizados:
- Incluir contexto melhora a qualidade das respostas
- Solicitar um passo a passo ajuda a estruturar melhor o conteúdo

---

###  Prompt 3 — Aplicação prática

"Gere um exemplo prático em Python para análise de risco de crédito, incluindo pré-processamento, treinamento e avaliação com AUC"

Resultado:
Foi gerado um exemplo completo em Python, com etapas de tratamento de dados, modelagem com LightGBM e avaliação utilizando AUC.

Aprendizados:
- Prompts mais específicos permitem obter respostas mais aplicáveis
- Estruturas comuns da área de Data Science são bem reproduzidas
- Pequenos ajustes podem ser necessários no código gerado

---

### ⚠️ Dificuldades e Ajustes

- Algumas respostas iniciais foram genéricas e pouco aplicáveis
- Foi necessário refinar os prompts para obter maior profundidade
- Nem todas as etapas importantes (como tratamento de desbalanceamento) foram incluídas automaticamente


# Miniguia de Estudo
##  Resumo

A análise de risco de crédito consiste em prever a probabilidade de um cliente não cumprir suas obrigações financeiras. Com o uso de Machine Learning, é possível identificar padrões complexos nos dados e melhorar a precisão dessas previsões.

O processo geralmente envolve etapas como pré-processamento de dados, engenharia de variáveis, treinamento de modelos e avaliação com métricas como AUC. Modelos como LightGBM, Random Forest e redes neurais são frequentemente utilizados nesse contexto.

Além da performance, a interpretabilidade dos modelos também é um fator importante, especialmente no setor financeiro, onde decisões precisam ser justificáveis.

##  Glossário

- **Inadimplência**: Falha no pagamento de uma dívida
- **AUC (Area Under Curve)**: Métrica que avalia a capacidade do modelo de distinguir classes
- **Feature Engineering**: Criação e seleção de variáveis relevantes
- **Overfitting**: Quando o modelo aprende demais os dados de treino e perde generalização
- **LightGBM**: Algoritmo de boosting eficiente para grandes volumes de dados
- **One-hot encoding**: Técnica para transformar variáveis categóricas em numéricas

  ##  Prompts Reutilizáveis

- "Explique como aplicar Machine Learning em análise de risco de crédito passo a passo"
- "Compare modelos de classificação utilizados em crédito (LightGBM, Random Forest, etc.)"
- "Quais métricas são mais adequadas para avaliar modelos de risco de crédito?"
- "Gere um exemplo prático em Python para análise de risco de crédito com avaliação em AUC"





