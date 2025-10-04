# Projeto de Mineração de Dados: Análise e Previsão de Evasão Escolar

Este projeto, desenvolvido para a disciplina de **[Nome da sua Disciplina, ex: BANCO DE DADOS E MINERAÇÃO]**, explora a aplicação de técnicas de mineração de dados para identificar e prever a evasão escolar. O objetivo é analisar fatores de risco e propor estratégias de intervenção com base em dados de estudantes.

---

## 🚀 Etapas do Projeto

O projeto foi dividido em duas etapas principais, conforme solicitado na atividade.

### Etapa 1: Coleta e Preparação de Dados

Nesta fase, o foco foi a elaboração e o pré-processamento de um conjunto de dados robusto e limpo, essencial para a qualidade da análise futura. As seguintes ações foram realizadas:

- **Elaboração da Planilha de Dados:** Foi criada uma planilha contendo dados fictícios, mas realistas, sobre estudantes, com o objetivo de simular um cenário de análise de evasão.
- **Limpeza e Organização:**
  - Remoção de duplicatas para garantir a unicidade de cada registro de aluno.
  - Normalização dos formatos de dados (ex: conversão de porcentagens e tratamento de valores categóricos).
  - Correção de inconsistências para assegurar a integridade do conjunto de dados.
- **Seleção de Atributos:** Os atributos foram cuidadosamente selecionados com base em sua relevância para a evasão escolar. A planilha final contém os seguintes campos:
  - `ID do Aluno`
  - `Nome`
  - `Nota Média`
  - `Frequência (%)`
  - `Participação em Atividades Extracurriculares`
  - `Absenteísmo (número de faltas)`
  - `Participação em Programa de Apoio (Sim/Não)`
  - `Participação nas Aulas (%)`
  - `Evasão (Sim/Não)`

### Etapa 2: Análise e Tomada de Decisões

Nesta etapa, as técnicas de mineração de dados foram aplicadas para extrair insights valiosos e tomar decisões informadas sobre a evasão.

- **Aplicação de Técnicas de Mineração:** Foram utilizadas técnicas como **Agrupamento (Clustering)** e **Classificação (Árvore de Decisão)** para identificar padrões e agrupar alunos com perfis de risco semelhantes.
- **Desenvolvimento do Score de Risco de Evasão:** Um **Score de Risco** foi calculado para cada aluno, variando de 0 a 100, para quantificar a probabilidade de evasão. Este score foi desenvolvido com base em uma fórmula de ponderação dos atributos considerados mais relevantes.
- **Interpretação e Proposta de Ações:** Com base na análise dos dados, foram identificados os principais fatores associados à evasão (baixas notas, alta frequência de faltas e baixa participação). A partir disso, foram propostas estratégias de intervenção personalizadas, como:
  - **Tutorias:** Para alunos com baixo desempenho acadêmico.
  - **Aconselhamento Pedagógico:** Para abordar as causas do absenteísmo.
  - **Incentivo à Participação:** Para engajar alunos em atividades extracurriculares e fortalecer o vínculo com a instituição.

---

## 🛠️ Tecnologias Utilizadas

- **Python:** Linguagem de programação principal.
- **Pandas:** Para manipulação e análise
