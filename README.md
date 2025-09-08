# **UrbanWear Sales Analysis**

Análise de vendas da UrbanWear (dados fictícios) utilizando a metodologia CRISP-DM.
O objetivo foi aplicar técnicas de Data Science e Análise de Dados para gerar insights sobre crescimento, comportamento de canais de venda (loja física vs online) e apoiar decisões estratégicas.

## **Objetivos do Projeto**

    - Analisar as vendas da UrbanWear entre 2018 e 2024.

    - Comparar o desempenho entre loja física e e-commerce.

    - Identificar tendências de crescimento, sazonalidade e ticket médio.

    - Aplicar a metodologia CRISP-DM para estruturar a análise.

    - Criar um case de portfólio para demonstração de habilidades em Data Science.

## **Metodologia CRISP-DM**

    - Business Understanding

    - Definição do problema: compreender o crescimento das vendas, impacto do e-commerce e riscos para a loja física.

### **Questões de negócio:**

    - Qual canal cresce mais rápido?

    - O e-commerce ameaça a relevância da loja física?

    - Qual o ticket médio por canal?

### **Data Understanding**

    - Base com 840 linhas e 8 colunas (2018–2024).

    - Variáveis: Ano, Canal, Receita Bruta, Quantidade Vendida, entre outras.

    - Observação inicial: forte correlação entre Quantidade Vendida e Receita Bruta (0.99).

### **Data Preparation**

    - Tratamento de nulos e consistência nos nomes dos canais.

    - Agrupamento de dados por ano e canal.

    - Criação de métricas derivadas: CAGR, Ticket Médio (AOV), Participação percentual por canal.

### **Modeling**

    - Não foi necessário machine learning neste estágio.

    - Modelagem analítica com Python (pandas, matplotlib, seaborn) para identificar padrões de crescimento e sazonalidade.

    - Evaluation

    - CAGR total da empresa (2018–2024): 0.98% ao ano (crescimento tímido).

    - E-commerce com taxa de crescimento superior à loja física.

    - Ticket médio mais alto no canal online.

    - Possível risco de perda de relevância da loja física.

### **Deployment**

    - Resultados documentados neste repositório.

    - Arquivos exportados para relatórios em CSV.

## **Principais Insights**

    - Crescimento Online: o e-commerce apresentou a maior taxa de crescimento ano a ano.

    - Loja Física Estagnada: embora ainda relevante, cresce pouco e pode perder participação.

    - Ticket Médio: mais elevado no online, indicando consumidores dispostos a gastar mais.

    - Tendência: reforçar o digital é estratégico para o futuro da marca.

## **Ferramentas Utilizadas**

    - Linguagem: Python 3.11

    - Bibliotecas: pandas, numpy, matplotlib, seaborn

    - Metodologia: CRISP-DM

    - Ambiente: Jupyter Notebook
