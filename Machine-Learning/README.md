# 🤖 MiniLabs – Machine Learning

Este diretório reúne uma coleção de **MiniLabs voltados para experimentação, validação e treino prático de técnicas de Machine Learning**.

Os MiniLabs têm como objetivo:

- **Apoiar a implementação dos projetos principais** do Small Data Lab, servindo como ambiente de testes e validação de abordagens específicas.
- **Explorar modelos ou técnicas que não estão diretamente integradas aos projetos maiores**, mas que merecem estudo isolado por sua relevância teórica ou prática.
- **Consolidar o aprendizado de algoritmos, bibliotecas e boas práticas**, com foco em reprodutibilidade e organização técnica.

## ⚙️ Ambiente Virtual

Todos os MiniLabs desta área compartilham um **ambiente virtual exclusivo**, criado e mantido dentro deste diretório (`.venv/`).  
Este ambiente contém as dependências acumuladas de cada MiniLab, listadas no arquivo `requirements.txt`.

Para garantir reprodutibilidade:

```bash
# Ativação do ambiente virtual (Linux/macOS)
source .venv/bin/activate

# Ativação do ambiente virtual (Windows)
.venv\Scripts\activate

Machine-Learning/
├── .venv/                         # Ambiente virtual da área de Machine Learning
├── requirements.txt              # Bibliotecas utilizadas nos MiniLabs
├── 01__statsmodels/              # MiniLab 01 – Análise Estatística com Statsmodels
    ├── data/                     # Dataset utilizado no notebook
    ├── notebook/                 # Notebook principal (.ipynb)
    └── README.md                 # Descrição técnica do minilab

## 🧠 Observações

- Todos os MiniLabs desta pasta compartilham o mesmo ambiente virtual, localizado em `.venv/`.
- O arquivo `requirements.txt` centraliza as dependências acumuladas de cada projeto.
- Cada notebook inclui um bloco final com `watermark`, exibindo as versões das bibliotecas e do Python utilizadas.
- A estrutura modular permite evolução contínua sem quebrar reprodutibilidade ou isolar o conhecimento.

---
