# Dashboard de Análise de Salários na Área de Dados

Este projeto foi desenvolvido como parte da Imersão Dados com Python, promovida pela Alura. O objetivo é criar um dashboard interativo para explorar e analisar dados salariais de profissionais da área de dados ao redor do mundo.

## Sobre o Projeto

O dashboard é construído com Streamlit e permite que os usuários visualizem métricas e gráficos sobre salários, utilizando um conjunto de filtros interativos na barra lateral. A análise se concentra em aspectos como salário médio, distribuição salarial, proporção de trabalho remoto e salários por cargo e país.

## Projeto Concluído

Você pode acessar o dashboard interativo no seguinte link:
[Dashboard de Salários na Área de Dados](https://dashboard-salario-area-dados.streamlit.app/)

### Funcionalidades

* Métricas Chave: Visualize de forma rápida o salário médio, salário máximo, número total de registros e o cargo mais frequente, todos baseados nos filtros aplicados.
* Gráficos Interativos:
* Top 10 Cargos por Salário Médio: Um gráfico de barras que mostra os cargos com as maiores médias salariais.
* Distribuição de Salários: Um histograma que ilustra a frequência de salários em diferentes faixas.
* Proporção dos Tipos de Trabalho: Um gráfico de pizza que exibe a porcentagem de profissionais que trabalham de forma remota, híbrida ou presencial.
* Salário Médio de Cientista de Dados por País: Um mapa-múndi que mostra a média salarial para o cargo de Cientista de Dados em diferentes países.
* Filtros Dinâmicos: A barra lateral oferece filtros para Ano, Senioridade, Tipo de Contrato e Tamanho da Empresa, permitindo uma análise granular dos dados.
* Tabela de Dados Detalhados: Uma tabela que exibe o conjunto de dados filtrado, possibilitando uma inspeção mais detalhada dos registros.

### Tecnologias Utilizadas

* Streamlit: Framework utilizado para a criação da interface do dashboard.
* Pandas: Biblioteca para manipulação e análise dos dados.
* Plotly Express: Biblioteca para a criação de gráficos interativos e visualizações.
* Python: Linguagem de programação principal do projeto.

### Como Rodar o Projeto Localmente

Para executar este dashboard em sua máquina, siga os passos abaixo:

**1. Clone o repositório:**
    
```
git clone https://github.com/ajuliasse/imersao-dados-python-alura-2025.git 

cd dashboard\_salarios\_dados
```
**2. Crie um ambiente virtual (opcional, mas recomendado):**
```
python -m venv venv

source venv/bin/activate  # No Linux/macOS

venv\Scripts\activate  # No Windows
```
**3. Instale as dependências:**

* Crie um arquivo ```requirements.txt``` na raiz do seu projeto com o seguinte conteúdo:

```
streamlit

pandas

plotly
```

* Então, instale as dependências:
```
pip install -r requirements.txt
```

**4. Execute o dashboard:**
```
streamlit run seu\_arquivo\_streamlit.py
```

* Substitua `seu\_arquivo\_streamlit.py` pelo nome do arquivo Python que contém o código do seu dashboard (por exemplo, `app.py` ou `dashboard.py`).

**Fonte dos Dados**

Os dados utilizados neste projeto foram fornecidos pela Alura durante a Imersão Dados com Python. Você pode encontrar o CSV original [aqui](https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv).

**Autor**

* Arthur A. Juliasse
