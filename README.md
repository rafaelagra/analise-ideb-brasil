# 🇧🇷 Análise Completa da Qualidade da Educação no Brasil (IDEB)

## 📌 Visão Geral do Projeto
Este projeto demonstra todas as etapas de um processo profissional de Análise de Dados. O foco é investigar a evolução e as disparidades do **Índice de Desenvolvimento da Educação Básica (IDEB)** entre os estados e diferentes redes de ensino (Pública vs. Privada) no Brasil, utilizando dados do INEP referentes ao período de 2005 a 2021.

## 🎯 Requisitos Mínimos Atendidos

| Requisito do Projeto | Status | Observações |
| :--- | :--- | :--- |
| **Seleção de Dados** | ✅ | Utilização de 4 tabelas de dados públicos do INEP. |
| **Tratamento e Preparação**| ✅ | Limpeza de valores ausentes, padronização de tipos de dados e criação de colunas derivadas. |
| **Criação de Novas Colunas** | ✅ | **`diferenca_meta`** e **`status_meta`**. |
| **Análise Exploratória (5+)** | ✅ | Aplicação de 5+ análises com Python (Tendência Temporal, Outliers, Correlação, etc.). |
| **Visualização (5+)** | ✅ | Dashboard interativo com 5+ gráficos diferentes. |
| **Dashboard Interativo** | ✅ | Painel criado no Looker Studio com filtros ativos. |

## 📊 Principais Insights da Análise

| Indicador | Valor Médio (Geral) | Insight Principal |
| :--- | :--- | :--- |
| **Média IDEB Nacional** | **4.5** | O valor representa a média histórica de desempenho. |
| **Média Superação Meta** | **0.2** | A nota IDEB média superou a meta projetada em 0.2 pontos (historicamente), indicando um desempenho ligeiramente acima do esperado. |
| **Média Taxa de Aprovação**| **89.2%** | Alta taxa de aprovação média, que se correlaciona positivamente com o desempenho IDEB. |

**Outras Descobertas Chave:**

1.  **Disparidade de Rede:** A rede **Privada** demonstra uma performance significativamente superior à rede Pública em todos os níveis.
2.  **Estagnação do Ensino Médio:** A análise da Série Temporal (Gráfico de Linha) revela que o Ensino Médio apresenta uma clara estagnação no crescimento do IDEB, um ponto crítico para políticas educacionais.

## 📈 Dashboard Interativo Final

O painel de controle permite a navegação detalhada por todos os estados e níveis de ensino.

🔗 **Acesse o Dashboard Aqui:** **[https://lookerstudio.google.com/reporting/96678d55-d0c0-445b-85ff-209e62710a6d](https://lookerstudio.google.com/reporting/96678d55-d0c0-445b-85ff-209e62710a6d)**

## 💻 Tecnologias Utilizadas
* **Linguagem:** Python
* **Bibliotecas:** Pandas, Matplotlib, Seaborn
* **Visualização:** Looker Studio
* **Ambiente:** Google Colab
* **Versionamento:** GitHub

---

## 🙋 Contato / Autor

**Rafael Agra**

🔗 **LinkedIn:** [https://www.linkedin.com/in/rafael-agra-201005355/](https://www.linkedin.com/in/rafael-agra-201005355/)
