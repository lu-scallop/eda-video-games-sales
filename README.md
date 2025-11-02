# Análise Exploratória (EDA) de Vendas Globais de Videogames (1980-2016)

![Status do Projeto](https://img.shields.io/badge/status-conclu%C3%ADdo-green)

Projeto de Análise Exploratória de Dados (EDA) focado no dataset "Video Game Sales" do Kaggle. O objetivo foi praticar o ciclo completo de análise de dados (desde a limpeza e transformação até a visualização e geração de insights) para entender as tendências históricas da indústria de jogos.

## 🚀 Tecnologias Utilizadas

* **Python 3.12.3**
* **Pandas** 
* **Matplotlib**
* **Jupyter Notebook** 

## 📊 Sobre o Dataset

Os dados utilizados são uma compilação de vendas de jogos (em milhões de unidades) de 1980 até 2020, extraídos do VGChartz e disponibilizados no Kaggle.

* **Arquivo:** `vgsales.csv`
* **Fonte:** [Video Game Sales - Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales)

## 🔍 Análises Realizadas

O notebook `main.ipynb` segue um fluxo lógico para investigar os dados:

1.  **Limpeza e Preparação:**
    * Análise e remoção de valores nulos nas colunas `Year` e `Publisher`.
    * Verificação da integridade dos dados (ex: dados pós-2016 incompletos).

2.  **Manipulação de dados:**
    * Criação da coluna `Decade` (década) a partir da coluna `Year` para facilitar análises de tendências de longo prazo.

3.  **Visualização de Dados e Insights:**
    * **Vendas Totais por Ano:** Análise da curva de vendas da indústria, identificando o pico histórico.
    * **Vendas Totais por Década:** Gráfico de barras para quantificar o volume de mercado em cada década.
    * **Análise Regional América do Norte(NA) vs. Europa(EU) vs. Japão(JP):** Gráfico de barras agrupadas para comparar as preferências de gênero de jogos entre as três regiões.
    * **Evolução dos Gêneros:** Gráfico de barras empilhadas de 100% para mostrar a mudança do *market share* de cada gênero ao longo das décadas.
    * **"Guerra dos Consoles":** Gráfico de barras empilhadas de 100% para identificar as plataformas dominantes em cada década.

## 💡 Principais Conclusões

1.  **Mudança nos Gêneros:** O mercado dos anos 80 e 90, dominado por jogos de **Plataforma** e **Puzzle**, é irreconhecível em comparação com os anos 2010, que são massivamente dominados por jogos de **Ação** e **Tiro (Shooter)**.

2.  **A "Era de Ouro" dos videogames (2000-2010):** A década de 2000 viu uma explosão no volume de vendas, com seu pico histórico em 2008. Esse aumento abrupto teve como um dos responsáveis o lançamento do **PlayStation 2** (o mais vendido da história).

3.  **Vendas regionais:** O Japão apresenta um perfil de consumo único, com uma preferência histórica e clara por **RPGs**, gênero que tem vendas modestas na América do Norte. Em contraste, América do Norte e Europa lideram com vendas de jogos do gênero Ação e Tiro.

4.  **As Gerações de Consoles:** A análise de *market share* por plataforma mostra claramente a ascensão e queda das gerações: do domínio do **NES** nos anos 80, para a "guerra" entre **PS1** e **SNES** nos anos 90, até o domínio entre **PS2/Wii/DS** nos anos 2000.

## 📈 Gráficos de Destaque

**Vendas Globais de jogos de 1980 até 2016**
![Gráfico vendas globais](/graphics/vendas_globais_ano.png
)

**Top 10 Plataformas com jogos mais vendidos**
![Gráfico plataformas](/graphics/plataformas_jogos_mais_vendidos.png)

**Top 10 Gêneros de jogos mais vendidos**
![Gráfico Gêneros](/graphics/generos_mais_vendidos.png)

**Top 10 Publishers com os jogos mais vendidos**
![Gráfico Publishers](/graphics/plublishers_jogos_mais_vendidos.png)

**Vendas globais de jogos por década**
![Gráfico décadas](/graphics/vendas_globais_totais_por_década.png)

**Vendas regionais por gênero**
![Gráfico regional](/graphics/vendas_regionais_por_genero.png)

**Evolução da Popularidade dos Gêneros**
![Gráfico de Gêneros por Década](/graphics/proporcao_vendas_globais_por_genero.png)

**Market Share das Plataformas por Década**
![Gráfico de Plataformas por Década](/graphics/participacao_mercado_por_plataforma.png)

## 🛠️ Como Executar o Projeto

1.  Clone este repositório:
    ```bash
    git clone https://github.com/lu-scallop/eda-video-games-sales
    ```
2.  Navegue até a pasta do projeto e instale as dependências:
    ```bash
    pip install requirements.txt
    ```
3.  Abra o arquivo `main.ipynb`.

## 👨‍💻 Contato

* **LinkedIn:** `https://www.linkedin.com/in/lucas-vieira-rocha/`