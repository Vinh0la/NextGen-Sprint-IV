# Análise de Churn de Clientes

## Descrição do Projeto

Este projeto realiza uma análise de churn de clientes com base em dados fictícios de uma empresa de tecnologia que oferece múltiplos produtos. O churn refere-se ao número de clientes que deixam de utilizar os serviços da empresa após um determinado período.

O objetivo final é construir um modelo que possa prever se um cliente vai deixar de usar os serviços da empresa (churn) ou não.

O código utiliza as seguintes bibliotecas:

- **Pandas**: para manipulação e análise de dados.
- **Matplotlib** e **Seaborn**: para visualização de dados.
- **Scikit-learn**: para pré-processamento, divisão dos dados e implementação do modelo de regressão logística.

O objetivo final é construir um modelo que possa prever se um cliente vai deixar de usar os serviços da empresa (churn) ou não.

# Como Rodar o Projeto

Clone o repositório
- git clone https://github.com/Vinh0la/NextGen-Sprint-IV.git
Instale as dependências:
- pip install -r requirements.txt

# Etapas do Projeto

- Carregamento e Preparação dos Dados:

- Leitura do arquivo CSV contendo os dados dos clientes.

- Limpeza e reordenação das colunas.

- Substituição de valores categóricos por numéricos.

- Análise Exploratória dos Dados:

- Contagem de churn.

- Distribuição de produtos entre clientes que churnaram e não churnaram.

- Distribuição do tempo de permanência por churn.

- Relação entre o tipo de contrato e churn.

- Matriz de correlação entre as variáveis.

 Modelagem:

- Divisão dos dados em conjuntos de treino e teste.

- Implementação e avaliação de um modelo de Regressão Logística.

- Implementação e avaliação de um modelo KNN.

