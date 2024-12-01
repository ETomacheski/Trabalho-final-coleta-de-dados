# Coleta e Análise de Dados

Este projeto visa estabelecer uma relação entre a quantidade de votos dos candidatos nas eleições de 2022 no Rio Grande do Sul (RS) e as receitas financeiras de suas campanhas eleitorais.

## Estrutura do Projeto

O projeto é composto pelos seguintes notebooks:

1. **ExtractDatasets**: Responsável por descompactar os datasets necessários.
2. **DataPreparation**: Prepara os dados para análise, unificando e limpando as informações.
3. **DataAnalytics**: Realiza a análise e gera gráficos para interpretação dos dados.

## Instruções de Execução

Para executar o projeto, siga os passos abaixo:

### 1. Criar o Ambiente Conda

Crie um ambiente Conda utilizando o arquivo `requirements.txt` localizado na raiz do projeto:

```bash
conda create --name coleta_analise --file requirements.txt
conda activate coleta_analise
```

### 2. Descompactar os Datasets

Execute o notebook `ExtractDatasets.ipynb` para descompactar os arquivos de dados necessários:

```bash
jupyter notebook ExtractDatasets.ipynb
```

### 3. Preparar os Dados

Rode o notebook `DataPreparation.ipynb` para limpar e organizar os dados:

```bash
jupyter notebook DataPreparation.ipynb
```

### 4. Gerar Gráficos e Análises

Finalmente, execute o notebook `DataAnalytics.ipynb` para realizar as análises e visualizar os gráficos:

```bash
jupyter notebook DataAnalytics.ipynb
```

## Dependências

As dependências estão listadas no arquivo `requirements.txt`. Certifique-se de que o Conda esteja instalado para configurar o ambiente corretamente.

## Resultados

Os resultados incluem:

- Comparativos entre a quantidade de votos e a receita das campanhas.
- Gráficos que mostram as correlações e insights derivados dos dados analisados.

