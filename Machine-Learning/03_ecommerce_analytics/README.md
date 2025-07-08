# 📊 MiniLab – E-commerce Analytics

Este MiniLab explora **Análise Exploratória de Dados (EDA)** e fundamentos estatísticos aplicados ao contexto de **logística e atraso em entregas**.  
A proposta é consolidar conceitos estatísticos e de visualização de dados em aplicações práticas, com foco em **interpretação crítica** e **geração de insights acionáveis** para o negócio.

## 🎯 Objetivo

Investigar padrões e relações entre atributos de pedidos e o status de entrega (no prazo ou atrasado), utilizando um conjunto de dados simulado de uma operação de e-commerce.

O foco está em entender quais variáveis influenciam mais os atrasos e como essas descobertas podem orientar decisões logísticas e operacionais futuras.

## 📌 Etapas Desenvolvidas

- Carregamento, pré-processamento e inspeção inicial dos dados
- Separação semântica de variáveis numéricas e categóricas
- Análise descritiva com medidas resumo e gráficos univariados
- Análise de correlação entre variáveis quantitativas
- Visualizações avançadas (boxplot, violino, histograma com KDE)
- Análise guiada por perguntas de negócio (modo de envio, prioridade e armazém)
- Geração de funções reutilizáveis para gráficos e tabelas percentuais
- Conclusão com insights práticos extraídos dos dados

## 🛠️ Ferramentas Utilizadas

- Python
- Pandas / Numpy
- Seaborn / Matplotlib

## 📁 Estrutura do Projeto

03_ecommerce_analytics/
├── data/  
│   └── dataset.csv  
├── notebook/  
│   └── minilab_E-commerce_Analytics.ipynb  
└── README.md

## 🧠 Principais Aprendizados / Insights

- O modo de envio parece influenciar os atrasos: navios apresentam maior percentual de entregas fora do prazo.
- Produtos com **prioridade baixa ou média** têm maior probabilidade de atraso.
- Certos corredores de armazém concentram mais atrasos, em especial o corredor F.
- A variável `desconto` apresenta uma leve inclinação em direção a entregas fora do prazo.
- Não foram observados problemas graves como **valores ausentes** ou **multicolinearidade** entre variáveis numéricas.
- O projeto reforça a importância de análises visuais e segmentadas para diagnósticos logísticos.

---

📦 Este projeto faz parte do ciclo de desenvolvimento do **Small Data Lab (SDL)**, uma iniciativa voltada à consolidação de fundamentos práticos em Ciência de Dados e à documentação de projetos autorais durante a transição de carreira.

