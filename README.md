# Projeto de Mineração de Dados

## Análise e Previsão de Evasão Escolar

Este projeto, desenvolvido para a disciplina de **Banco de dados e mineração**, explora a aplicação de técnicas de mineração de dados para identificar e prever a evasão escolar. O objetivo é analisar fatores de risco e propor estratégias de intervenção com base em dados de estudantes.

---

## 🚀 Etapas do Projeto

O projeto foi dividido em duas etapas principais para garantir uma análise completa e eficaz.

### Etapa 1: Coleta e Preparação de Dados

Nesta fase, o foco foi a elaboração e o pré-processamento de um conjunto de dados robusto e limpo, essencial para a qualidade da análise futura.

* **Elaboração dos Dados:** Foi criado um arquivo `.csv` contendo dados fictícios, mas realistas, sobre estudantes para simular um cenário de análise de evasão.
* **Limpeza e Organização:**
    * Remoção de dados nulos.
    * Remoção de duplicatas para garantir a unicidade de cada registro.
    * Normalização de formatos de dados (por exemplo, conversão de porcentagens e tratamento de valores categóricos).
* **Seleção de Atributos:** Os atributos foram selecionados com base na sua relevância para a evasão escolar. A planilha final contém campos como `Nota Média`, `Frequência`, `Absenteísmo` e `Participação em Atividades`.

### Etapa 2: Análise e Tomada de Decisões

Nesta etapa, técnicas de mineração de dados foram aplicadas para extrair insights valiosos e tomar decisões informadas sobre a evasão (análise presente no documento relatório).

* **Aplicação de Técnicas de Mineração:** Foram utilizadas técnicas de **Agrupamento (Clustering)** para identificar padrões e **Classificação (Árvore de Decisão)** para prever a evasão.
* **Desenvolvimento do Score de Risco de Evasão:** Um **Score de Risco**, de 0 a 100, foi calculado para cada aluno, quantificando a probabilidade de evasão.
* **Interpretação e Proposta de Ações:** Com base na análise, foram identificados os principais fatores associados à evasão (baixas notas, alta frequência de faltas e baixa participação), o que permitiu propor estratégias de intervenção personalizadas.

---

## 📊 Visualização e Resultados

A análise revelou três perfis de alunos distintos, agrupados por seu nível de risco. Os gráficos a seguir demonstram as principais diferenças entre eles:

<img src="Média da nota vs Falta por cluster.png" alt="Média das Porcentagens por Cluster de Risco">
<img src="Outras porcentagens vs Falta por cluster.png" alt="Relação entre Faltas e Notas, por Cluster de Risco">

**Interpretação:**
-   **Cluster 0 (Risco Baixo):** Alunos com as melhores notas e maior frequência.
-   **Cluster 1 (Risco Alto):** Alunos com as piores notas e maior número de faltas.
-   **Cluster 2 (Risco Médio):** Alunos com notas razoáveis, mas baixa frequência.

---

## 🛠️ Tecnologias Utilizadas

* **Python:** Linguagem de programação principal para desenvolvimento e análise.
* **Pandas:** Para manipulação e análise de dados.
* **Numpy:** Para operações numéricas e geração de dados.
* **Scikit-learn:** Para a aplicação de modelos de Machine Learning.
* **Matplotlib:** Para a visualização dos dados e geração de gráficos.
* **VSCode:** Ambiente para execução e documentação do código (em `.ipynb`).

---

## 📂 Estrutura do Repositório

* `README.md`: Este arquivo.
* `dados_brutos.csv`: Planilha com o conjunto de dados inicial.
* `dados_limpos.csv`: Planilha com o conjunto de dados final, após a preparação.
* `analise_projeto.ipynb`: Arquivo com o código-fonte utilizado para a análise, incluindo a preparação dos dados, a aplicação das técnicas de mineração e a interpretação dos resultados.
* `Relatório da Análise dos Dados.md`: Análise e interpretação dos dados em formato de relatório.
* `Média da nota vs Falta por cluster.png`: Gráfico que mostra a Média das Porcentagens por Cluster de Risco
* `Outras porcentagens vs Falta por cluster.png`: Gráfico que mostra a Relação entre Faltas e Notas, por Cluster de Risco
