# IA para Análise e Previsão de Score de Crédito

Este projeto realiza a análise e previsão de score de crédito de clientes utilizando algoritmos de machine learning. As bibliotecas Pandas e Scikit-learn são utilizadas para manipulação dos dados e criação dos modelos preditivos.

## Pré-requisitos

Antes de executar o código, certifique-se de que você possui os seguintes itens instalados:

1. Python 3.x
2. As bibliotecas necessárias do Python (Pandas e Scikit-learn)

## Instalação

### 1. Instale o Python

Caso não tenha o Python instalado, você pode baixá-lo e instalá-lo a partir do site oficial: [Python.org](https://www.python.org/downloads/)

### 2. Instale as Bibliotecas do Python

Para instalar as bibliotecas necessárias, execute os seguintes comandos no terminal:
    pip install pandas
    pip install scikit-learn


## Configuração do Código

- Certifique-se de que os arquivos CSV (clientes.csv e novos_clientes.csv) estejam no mesmo diretório do código ou especifique o caminho completo dos arquivos no código.
- Atualize o código se necessário para garantir que os nomes das colunas no código correspondam aos nomes das colunas nos seus arquivos CSV.

## Executando o Código
O código realiza as seguintes etapas:

- Importação dos dados de clientes do arquivo clientes.csv.
- Verificação de valores vazios ou dados incorretos.
- Codificação de variáveis categóricas usando LabelEncoder.
- Separação dos dados em conjuntos de treino e teste.
- Treinamento dos modelos RandomForestClassifier e KNeighborsClassifier.
- Avaliação da acurácia dos modelos.
- Previsão de scores de crédito para novos clientes a partir do arquivo novos_clientes.csv.
- Identificação das características mais importantes para a previsão do score de crédito.

## Observações

- Certifique-se de que os arquivos CSV estejam acessíveis e os dados estejam corretamente formatados.
- Dependendo do desempenho do seu sistema, pode ser necessário ajustar os parâmetros dos modelos ou os tempos de espera.
