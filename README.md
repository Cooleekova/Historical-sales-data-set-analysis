# Análise de Dados de Vendas com Jupyter Notebook

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) utilizando Python e Jupyter Notebook.

## 📁 Estrutura do Projeto

- Importação de Dados: Os arquivos CSV são carregados para análise.

- Limpeza dos Dados: Verificação e remoção de valores nulos e duplicados.

- Criação de Banco de Dados SQLite: Os dados limpos são inseridos em tabelas para facilitar consultas estruturadas.

- Análise Exploratória: Gráficos e estatísticas para responder perguntas sobre vendas e entregas.

## 📊 Principais Resultados

- **Volume de Pedidos por Mês:** A análise não revelou uma sazonalidade significativa nas vendas.

- **Tempo de Entrega:**

    - A maioria das entregas ocorre entre 4 e 17 dias.

    - Entregas muito rápidas (<4 dias) são menos comuns.

    - Há um número considerável de entregas muito longas (18 a 60 dias).

- **Custo de Frete vs. Distância de Entrega:**

    - Correlação positiva moderada (0.53), indicando que fretes mais caros tendem a ocorrer em entregas mais distantes.


## 🛠️ Tecnologias Utilizadas
- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- SQLite3
