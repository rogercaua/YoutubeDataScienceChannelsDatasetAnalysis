# Análise de Dados do YouTube

Este projeto contém uma análise detalhada de dados relacionados a canais de Ciência de Dados no YouTube. A análise explora métricas como visualizações, curtidas, comentários e o crescimento dos canais ao longo do tempo. A partir dessa análise, geramos insights sobre os tópicos mais populares e os canais com maior crescimento.

## Estrutura do Projeto

A estrutura do projeto é a seguinte:

project_folder/ 
├── Youtube_dataset_all_dataScience_channels.csv # Conjunto de dados original 

├── views_by_topic.csv # Dados de visualizações por tópico para Power BI 

├── processed_youtube_data.csv # Dados processados para Power BI 

├── channel_growth.csv # Crescimento de visualizações por canal 

├── analiseDeDadosYoutube.ipynb # Notebook principal de análise 

├── requirements.txt # Dependências do projeto

├── dataset_analysis_powerbi.pbix # Este é o arquivo do Power BI, que contém as visualizações e relatórios baseados nos dados processados. 


## Descrição dos Arquivos

- **`Youtube_dataset_all_dataScience_channels.csv`**: Contém os dados originais extraídos de vídeos de canais de Ciência de Dados no YouTube, incluindo informações sobre visualizações, curtidas, comentários, e outros dados relacionados.
  
- **`analiseDeDadosYoutube.ipynb`**: Este é o arquivo principal do projeto, que contém as etapas de pré-processamento, análise exploratória e visualização dos dados. O notebook também inclui a categorização dos vídeos em tópicos como Ciência de Dados, IA, Python, Excel, entre outros.

- **`processed_youtube_data.csv`**: Dados processados para uso em ferramentas de visualização como o Power BI. Esse arquivo contém os dados limpos e estruturados para análises adicionais.

- **`views_by_topic.csv`**: Dados sobre a quantidade de visualizações por tópico, útil para análise no Power BI.

- **`channel_growth.csv`**: Contém informações sobre o crescimento das visualizações de cada canal, comparando os valores de visualizações no início e no final do período analisado.
  
- - **`YouTubeDataScienceChannelsDataSetAnalisys.pbit`**: Este é o arquivo do Power BI, que contém as visualizações e relatórios baseados nos dados processados. Pode ser aberto diretamente no Power BI Desktop para gerar gráficos e insights interativos.

- **`requirements.txt`**: Lista todas as dependências do Python necessárias para rodar o projeto. Para instalar as dependências, execute:

    ```bash
    pip install -r requirements.txt
    ```

## Como Usar

### 1. Instalar Dependências

Clone o repositório e instale as dependências necessárias utilizando o arquivo `requirements.txt`:

```bash
git clone <link-do-repositorio>
cd <diretorio-do-projeto>
pip install -r requirements.txt

2. Executar a Análise
A análise é realizada no notebook analiseDeDadosYoutube.ipynb. Você pode abrir e executar as células diretamente em um ambiente Jupyter Notebook ou JupyterLab:
jupyter notebook analiseDeDadosYoutube.ipynb

3. Gerar os Relatórios
Após a execução do notebook, os arquivos CSV (processed_youtube_data.csv, views_by_topic.csv, e channel_growth.csv) serão gerados. Esses arquivos podem ser usados para criar visualizações adicionais ou serem importados para o Power BI para análise mais profunda.

Dependências
pandas: Para manipulação e análise de dados.
matplotlib: Para visualização dos dados.
jupyter: Para executar os notebooks.
seaborn (opcional): Para gráficos mais elaborados (caso use).
Instale as dependências utilizando o arquivo requirements.txt.
```
### 2. Executar a Análise

A análise é realizada no notebook analiseDeDadosYoutube.ipynb. Você pode abrir e executar as células diretamente em um ambiente Jupyter Notebook ou JupyterLab:
```bash
jupyter notebook analiseDeDadosYoutube.ipynb
```

### 3. Gerar os Relatórios

Após a execução do notebook, os arquivos CSV (processed_youtube_data.csv, views_by_topic.csv, e channel_growth.csv) serão gerados. Esses arquivos podem ser usados para criar visualizações adicionais ou serem importados para o Power BI para análise mais profunda.

### Dependências
pandas: Para manipulação e análise de dados.

matplotlib: Para visualização dos dados.

jupyter: Para executar os notebooks.

seaborn (opcional): Para gráficos mais elaborados (caso use).

Instale as dependências utilizando o arquivo requirements.txt.
