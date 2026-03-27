# analise-dados-python
analise-dados-python/
│
├── notebook.ipynb
├── data/
│   └── default_of_credit_card_clients.xls
└── README.md
# Análise de Dados com Python

Projeto desenvolvido para estudo de Python e Ciência de Dados.

## Tecnologias
- Python
- Pandas
- Jupyter Notebook

## Objetivo
Explorar um dataset de clientes de cartão de crédito, analisando:
- Quantidade de linhas e colunas
- Tipos de variáveis
- Estatísticas descritivas
- Dados faltantes

## Autor
Alexander Oliveira

1. Ver os pacotes do Anaconda

No terminal:
conda list

2. Abrir o Python no terminal
3. python

4. 3. Loop for (0 até 4)
   4. for counter in range(5):
    print(counter)
  
Saída:
0
1
2
3
4

4. Criar um dicionário
5. example_dict = {'apples':5, 'oranges':8, 'bananas':13}

6. 5. Converter para lista
   6. dict_to_list = list(example_dict)
dict_to_list
  
Saída:['apples', 'oranges', 'bananas']

1. Importar o pandas
2. import pandas as pd
3. 2. Carregar o dataset
   3. df = pd.read_excel('default_of_credit_card_clients__courseware_version_1_21_19.xls')
  
   4. 1. Quantidade de colunas
      2. df.shape[1]
      3. Resposta:

O dataset contém 25 colunas.

2. Quantidade de linhas
3. df.shape[0]
4. Resposta:

O dataset possui 30.000 linhas (amostras).

3. Tipos de características
4. df.dtypes
5. As variáveis podem ser classificadas em:

Numéricas: idade, limite de crédito, valores de fatura, pagamentos
Categóricas: sexo, educação, estado civil, status de pagamento

4. Aparência dos dados
Primeiras linhas:
df.head()
Estatísticas:
df.describe()
As variáveis numéricas apresentam diferentes escalas de valores. Por exemplo:

Limite de crédito varia bastante
Valores de pagamento podem ser positivos ou negativos
Idade varia dentro de um intervalo esperado

5. Frequência de variáveis categóricas

Exemplo:
df['SEX'].value_counts()
df['EDUCATION'].value_counts()
df['MARRIAGE'].value_counts()
Explicação:

As variáveis categóricas possuem valores discretos representando categorias específicas.

6. Verificar dados faltantes
7. df.isnull().sum()
8. Resposta esperada:

Não há valores faltantes no dataset (ou apresentar resultado real caso apareça algum).
# Jupyter Notebook - Alexander Oliveira

## Introdução

Estou achando a atividade interessante, pois permite aprender na prática como utilizar o Python e ferramentas como o pandas para análise de dados. O uso do Jupyter Notebook facilita a organização do código e a visualização dos resultados.

## Objetivo

Explorar um conjunto de dados de clientes de cartão de crédito, analisando suas características e identificando padrões importantes.
