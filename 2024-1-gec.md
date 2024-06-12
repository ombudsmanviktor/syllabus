---
title: Oficina de Análise e Visualização de Dados
has_children: false
has_toc: true
nav_order: 2
layout: home
---

# Oficina de Análise e Visualização de Dados

Professor: Viktor Chagas [✉️](mailto:viktor@midia.uff.br?subject=[Oficina de Análise e Visualização de Dados])

Período Letivo: 2024.1

Horário: Terças-feiras às 18h


## Ementa

A disciplina se propõe a introduzir fundamentos básicos da análise e da visualização de dados. O curso pretende munir os alunos de conhecimento prático e laboratorial acerca da análise exploratória de dados. Os alunos aprenderão a ler e criar diferentes tipos de gráficos, a produzir análises sobre estatísticas descritivas, análises textuais lexicométricas, análises georreferenciadas e análises de redes sociais. Além disso, eles receberão treinamento para a coleta de dados de diferentes repositórios públicos, bem como para limpar e organizar bancos de dados (data wrangling).

Com caráter de oficina, o curso utilizará variados softwares e aplicativos para suas operações, e poderá fornecer ainda capacitação básica e instrumental em linguagem R e na gramática de gráficos de seu principal pacote de visualização de dados, ggplot2. Os conhecimentos adquiridos poderão instrumentalizar futuros profissionais analistas de dados, cientistas de dados e business intelligence (BI).

As vagas são limitadas à capacidade do laboratório DADOS: 20 vagas.

## Bibliografia Resumida

Aquino, J. A. (2014). R para Cientistas Sociais.

Bruce, P., & Bruce, A. (2019). Estatística Prática para Cientistas de Dados.

Cairo, A. (2016). Truthful Art Data: Charts, and Maps for Communication.

Cervi, E. (2019). Manual de Métodos Quantitativos para Iniciantes em Ciência Política, vol. 1.

Cervi, E. (2019). Manual de Métodos Quantitativos para Iniciantes em Ciência Política, vol. 2.

Cherven, K. (2015). Mastering Gephi Network Visualization.

Cleveland, W. S. (1985). The Elements of Graphing Data.

D’Ignazio, C. (2020). Data Feminism.

Figueiredo Filho, D. (2019). Métodos Quantitativos em Ciência Política.

Knaflic, C. N. (2019). Storytelling com Dados: um Guia sobre Visualização de Dados para Profissionais de Negócios.

Krause, A., Rennie, N., & Tarran, B. (2023). Best Practices for Data Visualisation Insights.

Oliveira, P. F., Guerra, S., & McDonnell, R. (2018). Ciência de Dados com R: Introdução.

Salviati, M. E. (2017). Manual do Aplicativo Iramuteq.

Spiegelhalter, D. (2022). A arte da estatística: Como Aprender a Partir de Dados.

Wickham, H. (2019). R para Ciência de Dados: importe, arrume, transforme, visualize e modele dados.

Wickham, H. (2010). ggplot2: Elegant Graphics for Data Analysis.

Wurman, R. S. (1999). Ansiedade De Informação: Como Transformar Informação em Compreensão.


## Entregas de Exercícios

| Nomes  | Manipulação de Dados 1 | Manipulação de Dados 2 | Manipulação de Dados 3 | Manipulação de Dados 4 | Visualização de Dados |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Thábata e Paulo  | -------------  | ✔ | ✔ | ✔ | ✔ |
| Amanda e Bruna  | -------------  | ✔ | ✔ | ✔ | ✗ |
| Ana Julia e Ana Clara  | -------------  | ✔ | ✔ | ✔ | ✔ |
| Ana Júlia e Ana Luiza  | -------------  | ✔ | ✔ | ✔ | ✔ |
| Beatriz e Thainá  | -------------  | ✔ | ✔ | ✔ | ✔ |
| Nathalia e Mavi  | -------------  | ✔ | ✗ | ✗ | ✗ |
| Isaque e Rafaela  | -------------  | ✔ | ✔ | ✔ | ✔ |
| Helena e Clara | -------------  | ✔ | ✔ | ✔ | ✔ |
| Fernanda e Gabriela  | -------------  | ✔ | ✔ | ✔ | ✔ |
| Victor e Katarina  | -------------  | ✔ | ✔ | ✔ | ✔ |


## Recursos da Disciplina

- [Grupo de WhatsApp](https://chat.whatsapp.com/HllM1TpoyZqI5szgC8QuQM)

- [Pasta de Textos](https://drive.google.com/drive/folders/1JR_QqsFbDpjVKJiIaIz7Svo5LQ-BYXmy?usp=sharing)

- [Programa de Curso](https://ombudsmanviktor.github.io/syllabus/2024-1-gec.html)

- [Tutoriais e Scripts](https://colab-uff.github.io/docs/dataviz)


## Programa de Curso

### 19/03

**SEMANA INAUGURAL**

---

### 26/03 

Apresentação do Curso.

O que é Visualização de Dados? 

Adequação de Vocabulário: Gráfico, Grafo, Chart, Plot.

Visualização de Dados e Infografia.

As Origens do Campo: William Playfair, Florence Nightingale, John Tukey, William S. Cleveland, Edward Tufte, Alberto Cairo.

Tipos de gráficos: Gráficos Estatísticos, Diagramas, Mapas.

Exercício
{: .label .label-purple } 

> Instalação de Softwares (R, R Studio, Gephi, IramuteQ).
> 
> R Base.

Leituras Recomendadas
{: .label .label-purple } 

D’Ignazio, C. (2020). Data Feminism. (cap. 2)

Knaflic, C. N. (2019). Storytelling com Dados: um Guia sobre Visualização de Dados para Profissionais de Negócios. (cap. 2)

Playfair, William (1801). The Commercial and Political Atlas.

---

### 02/04

Arquitetura da informação e Visualização de Dados.

Dado e Informação.

Dado e Metadado.

Dado e Variável.

Tipos de Variáveis: Variáveis Numéricas e Categóricas.

Princípios de Arrumação de Bancos de Dados (Data Wrangling).

Datalakes e Repositórios Digitais.

Exercício
{: .label .label-purple } 

Arrumação de Bancos de Dados (TSE, IBGE, World Happines, V-Dem, 1746, IMDB, Facebook).

* https://worldhappiness.report/data/

* https://developer.imdb.com/non-commercial-datasets/

Dplyr (Aula 1).

Leituras Recomendadas
{: .label .label-purple } 

Wurman, R. S. (1999). Ansiedade De Informação: Como Transformar Informação em Compreensão. (cap. 1 e 2)

Spiegelhalter, D. (2022). A arte da estatística: Como Aprender a Partir de Dados. (cap. 1)

Figueiredo Filho, D. (2019). Métodos Quantitativos em Ciência Política. (cap. 2.1)

Wickham, H. (2019). R para Ciência de Dados: importe, arrume, transforme, visualize e modele dados.

---

### 09/04

Amostra e População.

Amostragem Aleatória e Viés de Amostra.

Análise Exploratória de Dados (AED).

Estatísticas Descritivas: Estimativas de Localização e Estimativas de Variabilidade.

Correlação e Causalidade: Estatísticas Espúrias.

Exercício
{: .label .label-purple } 

Dplyr (Aula 2).

Joins.

Tidyr.

Leituras Recomendadas
{: .label .label-purple } 

Bruce, P., & Bruce, A. (2019). Estatística Prática para Cientistas de Dados. (cap. 1)

Figueiredo Filho, D. (2019). Métodos Quantitativos em Ciência Política. (cap. 2.1)

Cervi, E. (2019). Manual de Métodos Quantitativos para Iniciantes em Ciência Política, vol. 1. (caps. 2.1, 5.1, 5.2 e 5.3)

Spiegelhalter, D. (2022). A arte da estatística: Como Aprender a Partir de Dados. (cap. 2)

---

### 16/04

Princípios de Construção de Gráficos: Títulos, Escalas, Rótulos, Regiões, Marcadores, Legendas, Facetas.

Métodos Gráficos.

Tipos de Gráficos I: Gráficos de Barras e de Colunas.

Típos de Gráfico II: Gráficos de Linhas e de Áreas.

Tipos de Gráficos III: Gráficos de Pizza, Donut e Waffle.

Exercício
{: .label .label-purple } 

GGplot2 (Aula 1).

Leituras Recomendadas
{: .label .label-purple } 

Knaflic, C. N. (2019). Storytelling com Dados: um Guia sobre Visualização de Dados para Profissionais de Negócios. (cap. 2)

Cleveland, W. S. (1985). The Elements of Graphing Data. (cap. 2)

Cairo, A. (2016). Truthful Art Data: Charts, and Maps for Communication. (cap. 5)

Wickham, H. (2010). ggplot2: Elegant Graphics for Data Analysis.

---

### 23/04

**FERIADO (S. JORGE)**

---

### 30/04

Tipos de Gráficos IV: Gráficos de Pontos e de Dispersão.

Tipos de Gráficos V: Gráficos Boxplot, Beeswarm, e Violino.

Exercício
{: .label .label-purple } 

GGplot2 (Aula 2).

Leituras Recomendadas
{: .label .label-purple } 

Knaflic, C. N. (2019). Storytelling com Dados: um Guia sobre Visualização de Dados para Profissionais de Negócios. (cap. 2)

Cleveland, W. S. (1985). The Elements of Graphing Data. (cap. 2)

Cairo, A. (2016). Truthful Art Data: Charts, and Maps for Communication. (cap. 5)

Wickham, H. (2010). ggplot2: Elegant Graphics for Data Analysis.

---

### 07/05

Tipos de Gráficos VI: Outros (Streamgraph, Alluvial, Sankey, Parallel).

Tipos de Gráficos VII: Análise de Correspondência Canônica (ACC).

Exercício
{: .label .label-purple } 

GGplot2 (Aula 3).

RAW Graphics.

Rankflow.

CA.

Leituras Recomendadas
{: .label .label-purple } 

Cervi, E. (2019). Manual de Métodos Quantitativos para Iniciantes em Ciência Política, vol. 2. (caps. 3.3.1)

---

### 14/05

Análise Lexical.

Nuvem de Palavras.

Análise de Similitude.

Classificação Hierárquica Descendente (CHD) de Reinert.

Análise Fatorial de Correspondência (AFC).

Exercício
{: .label .label-purple } 

IramuteQ.

Leituras Recomendadas
{: .label .label-purple } 

Salviati, M. E. (2017). Manual do Aplicativo Iramuteq.

---

### 21/05

Diagramas de Relações.

Diagramas Ilustrativos.

Diagramas de Venn e Euler.

Diagrama de Conceitos.

Diagramas de Hierarquias.

Diagramas de Fluxo.

Diagramas de Rede.

Análise de Redes Sociais (ARS).

Exercício
{: .label .label-purple } 

Gephi.

Leituras Recomendadas
{: .label .label-purple } 

Cherven, K. (2015). Mastering Gephi Network Visualization.

---

### 28/05

Mapas Coropléticos.

Mapas de Símbolos.

Cartogramas.

Exercício
{: .label .label-purple } 

GeoBR.

Leituras Recomendadas
{: .label .label-purple } 

Pereira, R.H.M., Gonçalves, C.N., et. al (2019). geobr: Loads Shapefiles of Official Spatial Data Sets of Brazil.

---

### 04/06

Percepção Gráfica: Ângulo, Área, Cor, Densidade, Distância, Posição, Volume.

Princípios da Gestalt, Atributos Pré-Atentivos e Carga Cognitiva.

Erros Comuns.

Exercício
{: .label .label-purple } 

GGplot2 (Aula 4).

Leituras Recomendadas
{: .label .label-purple } 

Knaflic, C. N. (2019). Storytelling com Dados: um Guia sobre Visualização de Dados para Profissionais de Negócios. (cap. 3)

Cleveland, W. S. (1985). The Elements of Graphing Data. (cap. 4.1 e 4.2)

---

### 11/06

Projeto Final I. Brainstorm.

---

### 18/06

Projeto Final II. Brainstorm.

---

### 25/06

Entrega do Trabalho Final.

---

### 02/07

**DÚVIDAS, SE HOUVER**

---

### 09/07

**LIVRE**
