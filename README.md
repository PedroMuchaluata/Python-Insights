# Python-Insights
# 📊 Análise de Clientes e Percentual de Cancelamento

Este projeto tem como objetivo realizar a análise de uma base de dados de clientes, identificando padrões, extraindo insights e **calculando o percentual de cancelamento** (churn) dos clientes.

## 🎯 Objetivos

- Carregar e limpar a base de dados dos clientes
- Explorar características como idade, localização, tempo como cliente, entre outros
- Calcular o **percentual de cancelamento**
- Gerar visualizações para facilitar a compreensão dos dados

## 🧰 Tecnologias Utilizadas

- Python 3.x
- `pandas` – manipulação de dados
- `numpy` – operações matemáticas
- `matplotlib` e `seaborn` – visualizações gráficas
- `jupyter notebook` – ambiente de análise interativa

## 📁 Estrutura do Projeto

analise_clientes/
├── dados/
│ └── base_clientes.csv
├── notebooks/
│ └── analise_clientes.ipynb
├── README.md
└── requisitos.txt

markdown
Copiar
Editar

## 📊 Sobre a Base de Dados

A base de dados deve conter, por exemplo, as seguintes colunas:

- `ID_Cliente`
- `Nome`
- `Idade`
- `Tempo_como_Cliente` (em meses ou anos)
- `Localizacao`
- `Status` (Ativo ou Cancelado)

## 📈 Métricas Calculadas

- Total de clientes
- Quantidade e percentual de clientes cancelados
- Distribuição por idade, localização e tempo de contrato
- Comparações entre clientes ativos e cancelados
