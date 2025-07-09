# 📊 MiniLab – Análise Estatística de Churn em Clientes de Cartão

Este MiniLab aplica técnicas de **análise estatística descritiva e inferencial** para investigar padrões de cancelamento de clientes (churn) em uma base realista de cartões de crédito.  
O foco é identificar variáveis com potencial preditivo e interpretar os resultados com base em hipóteses estatísticas e conexão com estratégias de retenção.

## 🎯 Objetivo

Investigar possíveis fatores associados ao churn de clientes, utilizando métodos estatísticos para:

- Identificar padrões comportamentais e de consumo
- Realizar testes de hipótese para validar diferenças entre grupos
- Gerar insights práticos aplicáveis ao negócio

## 📌 Etapas Desenvolvidas

- Importação, carregamento e prévia da base de dados
- Análise de frequência e variáveis categóricas
- Estatística descritiva e visualização de variáveis numéricas
- Comparações entre grupos (clientes ativos vs cancelados)
- Testes de hipótese (teste t) para variáveis relevantes
- Interpretação dos resultados com conexão ao negócio

## 🛠️ Ferramentas Utilizadas

- Python
- Pandas / NumPy
- Seaborn / Matplotlib
- SciPy (`ttest_ind`)
- Jupyter Notebook

## 📁 Estrutura do Projeto

02_churn_statistical_analysis/
├── data/
│ └── ClientesBanco.csv
├── notebook/
│ └── minilab_analise_estatistica_churn_cartao.ipynb.ipynb
└── README.md

## 🧠 Principais Aprendizados / Insights

- Como aplicar e interpretar testes de hipótese entre grupos
- Importância do Teorema Central do Limite em grandes amostras
- Utilização prática de boxplots e histogramas para suporte à inferência
- Identificação de variáveis como **Produtos Contratados**, **Contatos 12m** e **Taxa de Utilização** como potenciais sinalizadores de churn
- Tradução dos achados estatísticos em **ações práticas de retenção**

---

📦 Este projeto faz parte do ciclo de desenvolvimento do **Small Data Lab (SDL)**, uma iniciativa voltada à consolidação de fundamentos práticos em Ciência de Dados e à documentação de projetos autorais durante a transição de carreira.


