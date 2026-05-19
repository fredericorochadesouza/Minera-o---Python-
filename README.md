# Análise de Dados de Mineração com Python

Projeto de análise de dados de exploração mineral e processamento metalúrgico
desenvolvido como portfólio técnico para a área de mineração.

## O que esse projeto faz

- Carrega e explora dados de sondagem (collar, survey, assay)
- Executa limpeza e controle de qualidade (QA/QC) dos dados
- Calcula teor médio ponderado (TWM) e espessura mineralizada por furo
- Classifica furos por categoria: Rico, Minério, Baixo teor, Estéril
- Gera mapas de localização dos furos com teores
- Calcula balanço metalúrgico de usina de flotação de cobre
- Exporta relatório técnico completo em Excel formatado

## Tecnologias utilizadas

- Python 3 + Jupyter Notebook
- pandas — manipulação de dados tabulares
- matplotlib — visualizações e gráficos
- openpyxl — exportação de relatórios Excel

## Principais resultados

- Depósito de cobre porfirítico com 20 furos de sondagem
- Teor médio Cu: 0.720% | Teor médio Au: 0.148 g/t
- 1 furo Rico (BH-013, TWM 1.035% Cu), 18 Minério, 1 Baixo teor
- Recuperação média da usina: 86.26% Cu
- 29.17 t Cu perdidas no rejeito em 30 turnos

## Estrutura do projeto

mineracao-python/
├── data/
│   ├── collar.csv
│   ├── survey.csv
│   └── assay.csv
├── output/
│   ├── relatorio_mineracao.xlsx
│   ├── metricas_furos_final.csv
│   ├── balanco_metalurgico.csv
│   └── *.png
└── notebook/
└── analise_mineracao.ipynb



## Como executar

1. Clone o repositório
2. Instale as dependências: `pip install pandas matplotlib openpyxl`
3. Abra o Jupyter na pasta `notebook/`
4. Execute as células em sequência

## Autor

Frederico — Graduando em Ciência e Tecnologia com ênfase em Mineração
