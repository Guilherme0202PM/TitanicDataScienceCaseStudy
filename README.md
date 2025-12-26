# Titanic Data Science Case Study

## 📌 Visão Geral

Este repositório apresenta um **estudo de Ciência de Dados aplicado ao clássico conjunto de dados do Titanic**, com foco em **exploração, análise estatística e entendimento dos fatores associados à sobrevivência dos passageiros**.

O objetivo do projeto não é construir modelos preditivos, mas sim **analisar os dados de forma estruturada**, levantando hipóteses, padrões e relações entre variáveis relevantes, exatamente como é feito em etapas iniciais de projetos reais de Data Science.

Todo o conteúdo apresentado no README é fiel ao que está implementado no notebook do repositório.

---

## 🎯 Objetivos do Estudo

* Compreender a estrutura e a qualidade do conjunto de dados do Titanic
* Explorar variáveis demográficas e socioeconômicas dos passageiros
* Investigar padrões de sobrevivência por meio de análises estatísticas e visuais
* Aplicar técnicas de **agrupamento, tabelas de contingência e correlação entre variáveis**
* Realizar **engenharia de atributos simples** para enriquecer a análise

---

## 📂 Estrutura do Projeto

```
TitanicDataScienceCaseStudy/
│
├── Titanic.ipynb        # Notebook principal com todo o estudo
└── README.md               # Documentação do projeto
```

---
## 🛠️ Tecnologias Utilizadas

* **Python**
* **Pandas** – manipulação e análise de dados
* **Matplotlib** – visualização de dados
* **Seaborn** – visualizações estatísticas
* **Jupyter Notebook** – organização e apresentação do estudo

---

## 🧪 Etapas Desenvolvidas

### 1️⃣ Exploração Inicial dos Dados (EDA)

* Leitura do dataset utilizando **pandas**
* Visualização das primeiras linhas para entendimento da estrutura
* Análise de identificadores e valores únicos
* Inspeção inicial de variáveis categóricas e numéricas

Essa etapa teve como objetivo **entender o formato dos dados, suas colunas e possíveis inconsistências**.

---

### 2️⃣ Análises por Agrupamento

Foram realizadas análises baseadas em **agrupamentos (groupby)** para investigar padrões de sobrevivência associados a diferentes características, como:

* Classe do passageiro (Pclass)
* Sexo
* Idade (quando aplicável)

Essas análises permitem observar **tendências gerais** e comparar grupos de forma objetiva.

---

### 3️⃣ Tabelas de Contingência e Correlação

O estudo inclui **testes de associação entre variáveis categóricas**, utilizando:

* `pd.crosstab` para construção de tabelas de contingência
* Comparação entre variáveis como classe, sexo e sobrevivência

O objetivo aqui foi verificar **relações estatísticas e padrões de dependência** entre as variáveis, sem avançar para modelos preditivos.

---

### 4️⃣ Visualização de Dados

Foram utilizados gráficos para tornar os padrões mais claros e interpretáveis, incluindo:

* Gráficos de contagem (`countplot`)
* Visualizações segmentadas por classe e sobrevivência
* Comparações visuais entre grupos

As visualizações foram construídas com **Seaborn e Matplotlib**, priorizando clareza e interpretação.

---

### 5️⃣ Engenharia de Atributos

Foi realizada uma **engenharia de atributos simples**, extraindo informações relevantes da coluna `Cabin`:

* Criação da variável `Cabin_Letter`, representando a letra da cabine
* Análise da distribuição de sobreviventes considerando a seção da cabine

Essa etapa demonstra como **transformações simples podem enriquecer a análise exploratória**.

---

## 📊 Tipo de Análise Realizada

✔️ Análise exploratória de dados (EDA)
✔️ Análises estatísticas descritivas
✔️ Agrupamentos e comparações entre variáveis
✔️ Visualização de padrões e tendências
❌ Não há treinamento de modelos de Machine Learning
❌ Não há métricas preditivas ou validação de modelos

---

## 📌 Considerações Finais

Este estudo demonstra uma **abordagem realista e sólida de Ciência de Dados**, focada em entender o problema e os dados antes de qualquer modelagem. É um exemplo prático de como conduzir análises exploratórias bem estruturadas, interpretáveis e alinhadas com boas práticas da área.

O projeto é especialmente indicado para:

* Portfólios de Ciência de Dados
* Estudos acadêmicos
* Demonstração de habilidades em EDA e análise estatística
* Apresentações técnicas introdutórias

---

## 👤 Autor

Projeto desenvolvido como estudo prático em Ciência de Dados, com foco em análise exploratória e interpretação de dados reais.

---
