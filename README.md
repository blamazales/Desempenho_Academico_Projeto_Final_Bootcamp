# 🎓 Desafio de Análise de Dados: O que influencia o desempenho acadêmico dos estudantes?

## 📌 Contexto
Este projeto foi desenvolvido como desafio final do Bootcamp de Data Analytics da WoMakers Code, com o objetivo de investigar quais fatores do cotidiano dos estudantes influenciam seu desempenho acadêmico em provas finais.  

A análise busca fornecer insights que possam orientar **políticas de apoio estudantil**, auxiliando a melhorar a performance de seus alunos.

## 📊 Etapas da Análise

### 1. Análise Exploratória dos Dados (EDA)
- Distribuição das notas dos estudantes (`exam_score`).
- Diferenças de desempenho por gênero.
- Relação entre **horas de estudo**, **tempo em redes sociais**, **tempo assistindo Netflix** e as notas finais.
- Impacto da **saúde mental** no desempenho acadêmico.

### 2. Investigação de Correlações e Tendências
- Identificação de hábitos mais associados ao **alto desempenho** (nota ≥ 85).
- Influência do nível de educação dos pais nas notas.
- Comparação de desempenho entre estudantes com e sem emprego de meio período.

### 3. Modelagem Preditiva
Foram testados dois modelos:
- **Regressão Linear**
- **Random Forest Regressor**

Com eles foi possível:
- Avaliar o impacto **positivo** e **negativo** de cada variável no desempenho.
- Identificar quais fatores explicam melhor as variações de notas.

### 4. Recomendações
Com base nos resultados, foram propostas **ações práticas** para universidades:
- Programas de acompanhamento e planejamento de estudos.
- Campanhas e suporte sobre **saúde mental e hábitos de sono**.
- Educação para o uso consciente de **redes sociais e streaming**.
- Incentivo a atividades físicas regulares.

---

## 🛠️ Tecnologias Utilizadas
- **Python 3**
- **Pandas, NumPy** – manipulação e análise de dados  
- **Matplotlib, Seaborn** – visualização de dados  
- **Scikit-learn** – modelagem preditiva (regressão linear e random forest)  
- **SciPy** – testes estatísticos
- **Power BI** - criação de dashboard para visualização das informações obtidas também em python
