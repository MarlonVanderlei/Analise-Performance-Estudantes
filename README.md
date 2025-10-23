# 📈 Análise de Performance de Estudantes: O Fator Crítico para a Pontuação Final

## 🎯 Visão Geral do Projeto

Este projeto de análise de dados tem como objetivo central identificar e quantificar a influência de diversos fatores (esforço e hábitos) na performance acadêmica de estudantes, medida através de suas pontuações finais. A análise visa responder à pergunta: **Qual variável tem o maior impacto na nota de um aluno?**

O projeto foi construído utilizando um conjunto de dados fictício de mais de 200 alunos, cobrindo variáveis como Horas Estudadas, Horas de Sono e Frequência em Aulas.

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **Microsoft Excel:** Utilizado para a limpeza, modelagem, cálculo de métricas (Média, Mediana, Correlação) e construção do Dashboard Analítico.
* **Modelagem de Dados:** Aplicação de conceitos de Modelo Lógico para estruturar os dados de forma eficiente (Entidades Estudante e Performance).
* **Visualização de Dados:** Uso de Gráficos de Barras (Distribuição) e Gráficos de Dispersão (Correlação) para a apresentação dos *insights*.

## 🔑 Metodologia e Modelagem

Para garantir a integridade da análise, o projeto seguiu as seguintes etapas:

1.  **Modelagem Lógica:** Estruturação dos dados em duas entidades principais (`Estudante` e `Performance`), definindo chaves primárias e tipos de dados.
2.  **Limpeza e Tratamento:** Ajuste de formatos (decimais) e cálculo de métricas descritivas (Média e Mediana).
3.  **Análise de Correlação:** Utilização do coeficiente `CORREL` do Excel e Gráficos de Dispersão para quantificar a relação entre as variáveis de hábito e a pontuação final.

## 💡 Principal Insight (O Achado Mais Relevante)

A análise revelou um *insight* decisivo sobre a performance dos estudantes:

| Relação Analisada | Coeficiente de Correlação | Força da Relação |
| :--- | :--- | :--- |
| **Horas Estudadas vs. Pontuação Final** | **0,78** | **Correlação Positiva Forte** |
| Horas de Sono vs. Pontuação Final | 0,19 | Correlação Fraca |
| Frequência vs. Pontuação Final | 0,23 | Correlação Fraca |

**Conclusão:** O fator com maior impacto no sucesso acadêmico é o **tempo de estudo dedicado**. O coeficiente de **0,78** demonstra que, entre os fatores analisados, o **esforço direto (Horas Estudadas) é o principal motor do desempenho final.**

## 📂 Arquivos do Repositório

* [`Relatório.docx`](Relatório.docx): Relatório Analítico completo com a metodologia e a conclusão do projeto.
* `Dashboard.pdf`: Visualização final do dashboard construído no Excel.
* `Dados/`: Pasta contendo o arquivo de dados original (para replicação da análise).

---
*Este projeto demonstra proficiência em análise de dados, modelagem, visualização e geração de insights acionáveis usando ferramentas de mercado.*
