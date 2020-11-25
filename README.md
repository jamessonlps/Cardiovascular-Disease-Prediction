# Projeto 2 - Ciência dos Dados
____

## Modelos Preditivos para Doenças Cardiovasculares

### Alunos:
- **Guilherme Rosada**
- **Jamesson Leandro Paiva Santos**

### Professoras Orientadoras:
- **Maria Kelly Venezuela**
- **Barbara Agena**

### Curso: Engenharia de Computação, 2º semestre - Insper

____

Esse repositório consiste no Projeto Final da disciplina de Ciência dos Dados, cuja finalidade é construir modelos preditivos para classificar indivíduos como portadores ou não de doenças cardiovasculares a partir de um conjunto de dados disponíveis da plataforma [Kaggle](https://www.kaggle.com/). Todo o trabalho está desenvolvido no arquivo [Cardiovascular_Disease_Prediction](https://github.com/jamessonlps/Projeto2_CDados/blob/main/Cardiovascular_Disease_Prediction.ipynb).

O tema foi escolhido por se tratar da área de medicina, a qual tem cada vez mais se apoiado em diversos trabalhos de Inteligência Artificial e *Machine Learning* para obter mais êxitos em exames, diagnósticos e previsões de doenças. Neste projeto, o tema aborda a existência ou não de doenças cardiovasculares no indivíduo a partir de um conjunto de informações suas (idade, peso, altura, pressão sanguínea, índice de colesterol, entre outras). A base de dados utilizado foi extraída [daqui](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset).

As técnicas de *machine learning* utilizadas nesse projeto eram para classificação, isto é, para prever um rótulo (o indivíduo porta ou não alguma doença cardiovascular). Para isso, foram implementadas três abordagens diferentes:

- Árvores de Decisão (*Decision Tree*)
- Floresta Aleatória (*Random Forest*)
- Regressão Logística (*Logistic Regression*)

A aplicação desse modelo foi feita com o uso de uma bilbioteca bastante popular entre programadores para *data science* e *machine learning*: [scikit-learning](https://scikit-learn.org/stable/). Além disso, para recursos visuais, foram utilizadas as bibliotecas [matplotlib](https://matplotlib.org/) e [seaborn](https://seaborn.pydata.org/index.html). O tratamento e a manipulação de dados foi feita com [Pandas](https://pandas.pydata.org/) e [Numpy](https://numpy.org/). Recursos e módulos adicionais, cuja aplicação foi pontual, encontram-se nas primeiras células do arquivo jupyter.

____

### Participação de cada contribuidor do projeto

#### Guilherme Rosada

- Implementação do modelo de Floresta Aleatória;
- Análise das variáveis qualitativas;
- Implementação de recursos gráficos na Análise Exploratória;

#### Jamesson Leandro Paiva Santos

- Implementação dos modelos de Árvore de Decisão e Regressão Logística.
- Análise das variáveis quantitativas;

As demais tarefas no desenvolvimento do projeto foram feitas de forma mista, com participação de ambos.