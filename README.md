# Jurimetria usando Python a partir de relatórios .xlsx
Este notebook realiza a análise de recursos judiciais a partir de dados extraídos de planilhas Excel. Ele inclui a leitura dos dados, filtragem, contagem de resultados e visualização gráfica dos dados.

## Estrutura do Projeto
- Distribuidos outubro 2024.xlsx: Planilha contendo dados de recursos distribuídos.
- Julgados outubro 2024.xlsx: Planilha contendo dados de recursos julgados.
- Notebook.ipynb: Notebook Jupyter contendo o código de análise.

##  [Gráficos gerados](./Apresenta%C3%A7%C3%A3o%20-%20Projeto%20An%C3%A1lise%20de%20Dados.pdf)

## Requisitos
- Python 3.7+
- Pandas
- Matplotlib

## Instalação
Clone o repositório:

```shell
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_REPOSITORIO>
```

Crie um ambiente virtual e ative-o:

```shell
python -m venv venv
source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
```

Instale as dependências:

```shell
pip install pandas matplotlib
```

## Uso
Coloque as planilhas Distribuidos outubro 2024.xlsx e Julgados outubro 2024.xlsx no diretório do projeto.

Abra o notebook Notebook.ipynb no Jupyter Notebook ou JupyterLab.

Execute as células do notebook para carregar os dados, realizar a análise e visualizar os resultados.

## Funcionalidades
- Carregamento de Dados: Carrega todas as abas das planilhas Excel e concatena em um único DataFrame.
- Filtragem de Dados: Filtra os dados com base em critérios específicos, como tipo de recurso e decisão.
- Contagem de Resultados: Conta a quantidade de cada tipo de decisão para diferentes tipos de recursos.
- Visualização Gráfica: Gera gráficos de pizza e barras para visualizar a distribuição dos resultados.
