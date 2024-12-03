
# Sistema de Previsão de Score de Crédito

Este projeto utiliza aprendizado de máquina para prever o score de crédito de clientes com base em seus dados financeiros e de comportamento.

## Estrutura do Projeto

- **clientes.csv**: Base de dados com informações detalhadas de clientes.
- **novos_clientes.csv**: Dados adicionais para teste ou integração no sistema.
- **main.ipynb**: Notebook contendo o código para pré-processamento, treinamento e avaliação do modelo.

## Tecnologias Utilizadas

- **Python**: Linguagem principal.
- **Pandas**: Manipulação e análise de dados.
- **Scikit-learn**: Treinamento e validação de modelos de machine learning.

## Passos do Sistema

1. **Carregamento de Dados**:
   - O arquivo `clientes.csv` é carregado e exibido.

2. **Pré-processamento**:
   - Conversão de colunas categóricas em valores numéricos usando `LabelEncoder`.
   - Tratamento de valores ausentes e análise inicial.

3. **Treinamento**:
   - Dados são divididos em treino (70%) e teste (30%).
   - Dois modelos são treinados:
     - **Random Forest Classifier**.
     - **K-Nearest Neighbors (KNN)**.

4. **Avaliação**:
   - O desempenho dos modelos é avaliado nos dados de teste.

## Como Executar

1. Certifique-se de ter Python 3.8+ instalado.
2. Instale as dependências necessárias:
   ```bash
   pip install pandas scikit-learn
   ```
3. Execute o notebook `main.ipynb` em um ambiente como Jupyter Notebook ou VSCode.

## Autor

Pedro Henrique de Lima
