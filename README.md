# Predição de Preços de Imóveis com Redes Neurais e Machine Learning

## Descrição do Projeto
Este projeto tem como objetivo analisar e prever os preços de imóveis na cidade de São Paulo utilizando diferentes modelos de machine learning, incluindo redes neurais artificiais (MLP - Multilayer Perceptron), regressão linear, perceptron e árvores de decisão. O dataset utilizado foi obtido online e contém informações sobre diversos aspectos dos imóveis, como localização, tipo de negociação, tipo de propriedade, entre outros.

## Tecnologias Utilizadas
- Python
- Pandas
- Scikit-learn
- Redes Neurais (MLPRegressor)
- Regressão Linear
- Perceptron
- Árvore de decisão

## Etapas do Projeto

### 1. Importação das Bibliotecas
As bibliotecas necessárias para manipulação de dados, modelagem e avaliação dos modelos foram importadas.

### 2. Leitura e Análise do Dataset
Os dados foram carregados a partir de um CSV online e analisados por meio de descrição estatística e visualização de amostras.

### 3. Padronização e Limpeza dos Dados
Os dados passaram por um processo de limpeza, incluindo remoção de duplicatas e padronização dos valores para melhorar a performance dos modelos.

### 4. Pré-processamento dos Dados
- Foi aplicada a normalização dos dados com `StandardScaler`.
- Os dados categóricos foram convertidos em valores numéricos utilizando `LabelEncoder`.
- A base de dados foi dividida em conjunto de treinamento e teste.

### 5. Modelagem
Foram testados quatro modelos diferentes:
- **Regressão Linear**: Modelo simples de previsão baseado em relações lineares entre as variáveis.
- **Perceptron**: Um modelo de rede neural simples para classificação e previsão.
- **Multilayer Perceptron (MLP)**: Rede neural com camadas ocultas para previsão mais sofisticada.
- **Árvore de Decisão**: Modelo baseado em divisões sequenciais dos dados para tomada de decisão.

### 6. Avaliação dos Modelos
Os modelos foram avaliados com diferentes métricas:
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R² Score**

Os resultados foram comparados para verificar qual modelo apresentou melhor performance na previsão de preços dos imóveis.

## Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install pandas scikit-learn
   ```
3. Execute o notebook no Jupyter Notebook ou Google Colab.

## Conclusão
Este projeto demonstrou a importância da escolha adequada de modelos para previsão de preços de imóveis. A abordagem com redes neurais mostrou-se promissora, especialmente o modelo MLP, que conseguiu capturar melhor a complexidade dos dados em comparação com modelos mais simples como a regressão linear.

## Autor
- Nome: [Seu Nome]
- RM: [Seu RM]
- Contato: [Seu email ou GitHub]

