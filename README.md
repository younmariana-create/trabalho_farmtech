# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href="https://www.fiap.com.br/">
<img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width=40% height=40%>
</a>
</p>

<br>

# Análise de Rendimento Agrícola com Machine Learning

## FarmTech - Predição de Safras Agrícolas

## 👨‍🎓 Integrantes

- Henrique Honorio da Silva – RM XXXXX  
- João Victor Matos de Paiva – RM XXXXX  
- Luiz Frederico Nunes Campêlo – RM XXXXX  
- Manoella Menezes Weiser – RM XXXXX  
- Mariana Carvalho Youn – RM 568548  

---

## 👩‍🏫 Professores

### Tutor(a)
- Professor(a) responsável pela disciplina

### Coordenador(a)
- Coordenação do curso de Inteligência Artificial / Machine Learning - FIAP

---

# 📜 Descrição

Este projeto foi desenvolvido como parte da atividade de **Problem Based Learning (PBL)** da FIAP, com foco na aplicação de técnicas de **Machine Learning para análise de dados agrícolas**.

O objetivo principal do projeto é analisar dados climáticos e ambientais para identificar padrões que influenciam o rendimento das plantações e desenvolver modelos preditivos capazes de estimar o rendimento de uma safra agrícola com base em variáveis climáticas.

Para atingir esse objetivo, foi utilizado um dataset contendo informações relevantes como:

- Precipitação
- Umidade específica
- Umidade relativa
- Temperatura
- Rendimento agrícola (Yield)

O projeto foi estruturado em diferentes etapas típicas de um fluxo de trabalho de **Machine Learning**, incluindo:

### 1. Análise Exploratória de Dados (EDA)

Inicialmente foi realizada uma exploração da base de dados para compreender suas características, estrutura e distribuição das variáveis. Foram utilizados métodos como:

- `df.info()`
- `df.describe()`
- análise de distribuição das variáveis
- visualização gráfica

Essa etapa permitiu entender melhor os dados e identificar possíveis padrões iniciais.

### 2. Clusterização

Foi aplicada uma técnica de **clusterização utilizando o algoritmo K-Means**, com o objetivo de identificar agrupamentos naturais dentro dos dados.

A clusterização permitiu observar possíveis padrões entre variáveis climáticas e o rendimento agrícola, ajudando a entender cenários semelhantes dentro da base de dados.

### 3. Identificação de Outliers

Foi realizada a detecção de **valores discrepantes (outliers)** utilizando gráficos como **boxplots**, permitindo identificar possíveis observações extremas que podem influenciar o desempenho dos modelos preditivos.

A identificação desses valores auxilia na compreensão da variabilidade presente no rendimento agrícola.

### 4. Modelagem Preditiva

Foram desenvolvidos **cinco modelos de regressão supervisionada**, com o objetivo de prever o rendimento agrícola (Yield) com base nas variáveis climáticas disponíveis.

Os modelos implementados foram:

- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Regression (SVR)**

Cada modelo foi treinado utilizando os dados de treinamento e posteriormente avaliado com dados de teste.

### 5. Avaliação dos Modelos

Os modelos foram avaliados utilizando métricas comuns em problemas de regressão, como:

- **Mean Squared Error (MSE)**
- **R² Score**

Essas métricas permitiram comparar o desempenho dos diferentes algoritmos e entender qual modelo apresentou melhor capacidade preditiva.

Os resultados indicaram que os modelos apresentaram desempenho limitado, sugerindo que as variáveis disponíveis podem não ser suficientes para explicar completamente a variação do rendimento das safras.

---

# 📁 Estrutura de Pastas

A estrutura do projeto está organizada da seguinte forma:

TRABALHO_FARMTECH
│
├── assets
│   └── logo-fiap.png
│
├── data
│   └── crop_yield.csv
│
├── notebook
│   └── MarianaYoun_rm568548_pbl_fase4.ipynb
│
└── README.md


Onde:

- **assets**: contém arquivos visuais utilizados no repositório, como imagens.
- **dataset (.csv)**: base de dados utilizada na análise.
- **notebook (.ipynb)**: notebook Jupyter contendo toda a análise, modelagem e resultados.

---

# 🔧 Como Executar o Projeto

Para executar o projeto localmente, siga os passos abaixo.

### 1. Pré-requisitos

Certifique-se de possuir instalado:

- Python 3.x
- Jupyter Notebook ou VS Code
- Bibliotecas Python:

pandas
numpy
matplotlib
seaborn
scikit-learn


Para instalar as bibliotecas necessárias:

pip install pandas numpy matplotlib seaborn scikit-learn

---

### 2. Executar o Notebook

1. Clone o repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git


2. Abra a pasta do projeto.

3. Execute o notebook:

MarianaYoun_rm568548_pbl_fase4.ipynb


4. Execute todas as células do notebook para reproduzir a análise.

---

# 🎥 Vídeo de Demonstração

Um vídeo demonstrando o funcionamento do projeto foi disponibilizado no YouTube como **não listado**.

Link do vídeo:

***

---

# 🗃 Histórico de Lançamentos

* 0.1.0 - Entrega inicial do projeto
    * Implementação da análise exploratória
    * Aplicação de clusterização
    * Identificação de outliers
    * Desenvolvimento dos modelos de Machine Learning
    * Avaliação comparativa dos modelos

---

# 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg">
<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg">

MODELO GIT FIAP por FIAP está licenciado sob **Attribution 4.0 International**.


