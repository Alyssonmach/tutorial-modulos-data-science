# Tutorial: Introdução aos Módulos de Análise de Dados

Material didático em português para quem quer começar a analisar dados com Python, NumPy, Pandas e Matplotlib.

**Autoras:** @leportella e @jtemporal

**Duração estimada:** 4 horas

**Pré-requisitos:** noções básicas de Python, como variáveis, condicionais e loops.

## Conteúdo

Recomendamos seguir os notebooks na ordem indicada:

1. [Jupyter Notebook](1-Jupyter.ipynb) — células, Markdown, fórmulas e visualizações.
2. [NumPy](2-Numpy.ipynb) — vetores, matrizes e operações numéricas.
3. [Pandas: Series](3-Series.ipynb) — séries, índices e valores ausentes.
4. [Pandas: DataFrames](4-DataFrames.ipynb) — leitura e manipulação de tabelas.
5. [Matplotlib](5-Matplotlib.ipynb) — criação e personalização de gráficos.

O GitHub exibe os notebooks diretamente no navegador. Para executar as células, siga as instruções abaixo.

## Tópicos abordados

- Noções básicas de Jupyter Notebook.
- Leitura e manipulação de arquivos CSV.
- Separação e exploração de dados.
- Estatísticas básicas, como média, moda, mediana e desvio padrão.
- Tratamento de valores ausentes e interpolação linear.
- Gráficos, incluindo histogramas e visualizações com dois eixos.

## Como executar localmente

Clone o repositório, crie um ambiente Python e instale as dependências:

```bash
git clone https://github.com/Alyssonmach/tutorial-modulos-data-science.git
cd tutorial-modulos-data-science
```

Crie e ative um ambiente virtual:

```bash
# macOS ou Linux
python3 -m venv .venv
source .venv/bin/activate
```

```powershell
# Windows PowerShell
py -m venv .venv
.venv\Scripts\Activate.ps1
```

Instale os pacotes e inicie o Jupyter:

```bash
python -m pip install -r requirements.txt
jupyter notebook
```

Abra os notebooks pela interface do Jupyter e execute as células em sequência. Os notebooks de DataFrames e Matplotlib leem `HR_comma_sep.csv` por um caminho relativo; iniciar o Jupyter na pasta do repositório permite que esses caminhos funcionem.

## Arquivos de dados

- `HR_comma_sep.csv` — tabela usada nos notebooks de DataFrames e Matplotlib.
- `world-happiness-report.zip` — arquivo compactado com tabelas CSV dos anos de 2015, 2016 e 2017, disponível para exploração adicional.

## Dependências

As bibliotecas usadas no material estão listadas em [`requirements.txt`](requirements.txt): Jupyter, IPython, NumPy, Pandas e Matplotlib.
