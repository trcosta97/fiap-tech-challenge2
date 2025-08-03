# Tech Challenge 2 - Análise de Dados do IBOVESPA

## Grupo
+ Airton da Silva Cruz - RM362447
+ Gustavo Pitarello - RM361594
+ João Paulo Giacherini de Moraes - RM 361571
+ Thiago Ribeiro da Costa - RM 362845
+ Victor Morene Galves Marcondes - RM 362219

## Descrição do Projeto

Este projeto apresenta uma análise exploratória de dados históricos do IBOVESPA (Índice Bovespa) dos últimos 5 anos. O objetivo é compreender o comportamento do principal índice da bolsa de valores brasileira através de visualizações e análises estatísticas.

## Estrutura do Projeto

```
tech2/
├── README.md
├── notebook.ipynb
├── dados_historicos_ibovespa_5_anos.csv
└── Links.txt
```

## Dataset

O dataset contém dados históricos do IBOVESPA com as seguintes colunas:
- **Data**: Data da negociação
- **Último**: Preço de fechamento
- **Abertura**: Preço de abertura
- **Máxima**: Maior preço do dia
- **Mínima**: Menor preço do dia
- **Vol.**: Volume negociado
- **Var%**: Variação percentual

## Análises Realizadas

### 1. Análise Exploratória de Dados (EDA)
- Verificação de dados nulos
- Estatísticas descritivas
- Tratamento e limpeza dos dados
- Conversão de tipos de dados

### 2. Visualizações
- Gráfico de variação diária (%)
- Gráfico de fechamento diário
- Gráfico de abertura diária
- Comparação entre abertura e fechamento

### 3. Principais Insights
- Período analisado: 5 anos de dados históricos
- Total de registros: 1.265 observações
- Variação média: 0.04%
- Desvio padrão da variação: 1.18%
- Maior variação positiva: 5.54%
- Maior variação negativa: -4.87%

## Tecnologias Utilizadas

- **Python**: Linguagem principal
- **Pandas**: Manipulação e análise de dados
- **Matplotlib**: Visualização de dados
- **Seaborn**: Visualizações estatísticas
- **NumPy**: Computação numérica
- **Jupyter Notebook**: Ambiente de desenvolvimento

## Como Executar

1. Clone o repositório:
```bash
git clone [URL_DO_REPOSITORIO]
cd tech2
```

2. Instale as dependências:
```bash
pip install pandas matplotlib seaborn numpy jupyter
```

3. Execute o notebook:
```bash
jupyter notebook notebook.ipynb
```

## Resultados

A análise revelou que o IBOVESPA apresentou:
- Comportamento típico de mercado financeiro com alta volatilidade
- Períodos de alta e baixa bem definidos
- Volume de negociação variável ao longo do período
- Tendências de longo prazo identificáveis através dos gráficos

## Próximos Passos

- Implementação de modelos preditivos
- Análise de correlação com outros indicadores econômicos
- Desenvolvimento de estratégias de investimento baseadas nos dados
- Análise de sazonalidade

