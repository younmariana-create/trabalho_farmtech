# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

## FarmTech Solutions - Análise de Rendimento Agrícola com Machine Learning

## Grupo 32

---

## 👨‍🎓 Integrantes

* Henrique Honorio da Silva – RM 
* João Victor Matos de Paiva – RM 
* Luiz Frederico Nunes Campêlo – RM 
* Manoella Menezes Weiser – RM 
* Mariana Youn – RM 568548

---

## 👩‍🏫 Professores

### Tutor(a)

Sabrina Otoni

### Coordenador(a)

André Godoi Chiovato

---

# 📜 Descrição

Este projeto foi desenvolvido como parte das atividades da Fase 5 do curso da FIAP, com foco na aplicação de técnicas de Machine Learning em um cenário de agronegócio.

A atividade simula um contexto profissional no qual a empresa **FarmTech Solutions** presta serviços de Inteligência Artificial para uma fazenda de médio porte com aproximadamente 200 hectares de área produtiva. O objetivo da empresa é utilizar dados ambientais e climáticos para compreender melhor as condições que influenciam a produtividade agrícola e, a partir disso, auxiliar na tomada de decisões estratégicas.

Para essa análise foi utilizada uma base de dados contendo informações relacionadas às condições climáticas e ao tipo de cultura cultivada, incluindo variáveis como precipitação, temperatura e níveis de umidade. Além dessas variáveis ambientais, o conjunto de dados também apresenta o rendimento das culturas agrícolas medido em toneladas por hectare.

Com base nesse dataset, foi realizada inicialmente uma **análise exploratória dos dados**, com o objetivo de compreender a estrutura da base, identificar possíveis padrões e verificar a existência de valores discrepantes (outliers).

Posteriormente, foram aplicadas técnicas de **Machine Learning**, incluindo métodos de clusterização para identificar tendências de produtividade entre diferentes culturas e condições climáticas.

Na etapa final do projeto foram desenvolvidos **modelos preditivos**, utilizando diferentes algoritmos de Machine Learning. Esses modelos têm como objetivo prever o rendimento das safras agrícolas a partir das condições ambientais observadas.

Todo o processo de análise, preparação dos dados, treinamento dos modelos e avaliação de desempenho foi documentado no notebook Jupyter presente neste repositório.

---

# 📁 Estrutura de Pastas

Dentre os arquivos e pastas presentes na raiz do projeto, destacam-se:

### data

Contém o dataset utilizado no projeto, incluindo o arquivo:

* `crop_yield.csv` → base de dados com informações climáticas e rendimento das culturas.

### notebook

Contém o notebook Jupyter responsável pela implementação da análise de dados e dos modelos de Machine Learning:

* `MarianaYoun_rm568548_pbl_fase4.ipynb`

Neste notebook estão presentes:

* análise exploratória dos dados
* visualizações e gráficos
* preparação dos dados para modelagem
* treinamento dos modelos de Machine Learning
* avaliação dos resultados obtidos

### README.md

Arquivo responsável por apresentar a documentação geral do projeto e orientar o leitor sobre o funcionamento da solução.

---

# 🔧 Como executar o projeto

Para executar este projeto em sua máquina, siga os passos abaixo.

### 1 – Clonar o repositório

Clone o repositório do GitHub para sua máquina:

git clone LINK_DO_REPOSITORIO

Após o download, acesse a pasta do projeto.

---

### 2 – Instalar as bibliotecas necessárias

O projeto foi desenvolvido utilizando a linguagem **Python** e bibliotecas comuns de análise de dados e Machine Learning.

Principais bibliotecas utilizadas:

* pandas (manipulação de dados)
* numpy (operações numéricas)
* matplotlib (visualização de dados)
* seaborn (visualização estatística)
* scikit-learn (algoritmos de Machine Learning)

Caso necessário, instale as dependências utilizando:

pip install pandas numpy matplotlib seaborn scikit-learn

---

### 3 – Executar o notebook

Abra o arquivo localizado em:

notebook/MarianaYoun_rm568548_pbl_fase4.ipynb

O notebook pode ser executado utilizando:

* Jupyter Notebook
* Jupyter Lab
* Visual Studio Code

Após abrir o notebook, execute todas as células para reproduzir a análise completa.

---

# 🎥 Vídeo de Demonstração

Um vídeo demonstrando o funcionamento do projeto foi gravado e disponibilizado no YouTube como **não listado**.

Link do vídeo:

(INSERIR LINK DO VÍDEO AQUI)

---

# 🗃 Histórico de Lançamentos

### 0.1.0 – Entrega inicial do projeto

* Estrutura inicial do repositório
* Upload do dataset
* Implementação do notebook de análise e modelagem

---

# 📋 Licença

Este projeto segue o modelo de repositório acadêmico da FIAP.

MODELO GIT FIAP por FIAP é licenciado sob **Attribution 4.0 International**.
