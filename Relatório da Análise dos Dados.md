# Relatório de Predição de Evasão Acadêmica

---

## 1. Análise de Agrupamento (K-Means)

A aplicação do algoritmo K-Means resultou na identificação de **três perfis distintos de alunos**, classificados por seu nível de risco de evasão. A análise das médias das variáveis de desempenho para cada grupo (cluster) revelou as seguintes características:

- **<ins>Cluster 0: Risco Baixo</ins>**
  - **Características:** Este grupo representa o perfil ideal do estudante. Apresenta as melhores métricas em todas as categorias: a maior média de nota (**74,41**), a maior frequência (**78%**), e a maior participação nas aulas (**84%**). A taxa de evasão neste cluster é de **0%**, indicando que nenhum aluno deste grupo evadiu.

- **<ins>Cluster 1: Risco Alto</ins>**
  - **Características:** Este é o perfil mais crítico e com maior risco de evasão. Os alunos deste cluster têm as piores métricas: a maior média de faltas (**49%**), a menor frequência (**14%**), e a menor nota média (**68,71**). A taxa de evasão é de **100%**, mostrando que todos os alunos deste grupo evadiram.

- **<ins>Cluster 2: Risco Médio</ins>**
  - **Características:** Este grupo apresenta um perfil intermediário de risco. Embora a nota média (**74,36**) seja similar à do Cluster 0, a frequência (**25%**) e a participação nas aulas (**24%**) são significativamente mais baixas. Assim como no Cluster 1, a taxa de evasão é de **100%**, sugerindo que as causas da evasão neste grupo estão mais ligadas à baixa participação e frequência do que ao desempenho acadêmico.

---

## 2. Análise e Desenvolvimento do Score de Risco de Evasão

Um **<ins>Score de Risco de Evasão</ins>** foi desenvolvido com base em um modelo de **Árvore de Decisão** para prever a probabilidade de um aluno evadir. A análise dos 10 alunos com as maiores pontuações de risco revelou que todos eles obtiveram um score de **100,0**.

- **Validação do Modelo:** A maioria desses alunos de alto risco pertence aos **Clusters 1 e 2**, o que valida a eficácia do modelo. Isso demonstra que os perfis de risco identificados pelo agrupamento K-Means estão diretamente correlacionados com as previsões do modelo de classificação.

---

## 3. Estratégias de Intervenção Personalizadas

Com base na segmentação e na pontuação de risco, propomos as seguintes ações estratégicas de intervenção, focando nos alunos dos **<ins>Clusters 1 e 2</ins>**, que representam o maior risco de evasão.

- **<ins>Foco em Tutorias Acadêmicas</ins>:**
  - **Público-alvo:** Alunos do **Cluster 1**.
  - **Proposta:** Oferecer tutorias especializadas para melhorar o desempenho acadêmico. O objetivo é mitigar a frustração causada por notas baixas, um fator determinante para a evasão neste grupo.

- **<ins>Foco em Aconselhamento Pedagógico</ins>:**
  - **Público-alvo:** Alunos com alto índice de faltas, especialmente no **Cluster 1**.
  - **Proposta:** Disponibilizar aconselhamento para identificar as causas do absenteísmo. O apoio psicopedagógico pode ajudar a resolver problemas que impedem a frequência regular, mantendo o aluno engajado com a instituição.

- **<ins>Foco em Incentivo à Participação</ins>:**
  - **Público-alvo:** Alunos dos **Clusters 1 e 2**.
  - **Proposta:** Criar programas e incentivos para engajar esses alunos em atividades extracurriculares e programas de apoio. O aumento da participação pode fortalecer o vínculo dos alunos com a instituição e melhorar a frequência, um fator crítico para a evasão em ambos os grupos de alto risco.
  - **Público-alvo:** Alunos com alto índice de faltas, especialmente no **Cluster 1**.
  - **Proposta:** Disponibilizar aconselhamento para identificar as causas do absenteísmo. O apoio psicopedagógico pode ajudar a resolver problemas que impedem a frequência regular, mantendo o aluno engajado com a instituição.

- **Foco em Incentivo à Participação:**
  - **Público-alvo:** Alunos dos **Clusters 1 e 2**.
  - **Proposta:** Criar programas e incentivos para engajar esses alunos em atividades extracurriculares e programas de apoio. O aumento da participação pode fortalecer o vínculo dos alunos com a instituição e melhorar a frequência, um fator crítico para a evasão em ambos os grupos de alto risco.
