# Projeto de Análise de Dados: E-commerce (ADS)

![Status: Em Andamento](https://img.shields.io/badge/status-em_andamento-yellow)
![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-blue?logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-orange?logo=jupyter)

Este repositório contém o desenvolvimento do projeto de análise de dados para um e-commerce brasileiro, como parte da avaliação da cadeira de Probabildiade e Estatistica do curso de Análise e Desenvolvimento de Sistemas.

---

## 1. 🎯 Contexto do Projeto

A direção de um e-commerce fictício busca respostas confiáveis (com tratamento estatístico) sobre sua operação. O objetivo deste projeto é produzir um **relatório analítico** (acompanhado de um notebook de análise) que demonstre uma análise exploratória de dados (EDA) completa, focando em receita, margens, frete, prazos de entrega e comportamento do cliente.

## 2. 👥 Equipe 

Este projeto foi desenvolvido pelos seguintes membros:

* **[Camila Teixeira]** - Negócio/Coordenação
* **[Victor Marques]** - Engenharia de Dados
* **[Ana Sofia]** - Ciência de Dados


## 3. Entregáveis

O projeto é composto por dois entregáveis principais, ambos contidos neste repositório:

1.  📄 **/relatorio_final.pdf**: O relatório analítico em formato PDF, que contempla:
    * Sumário Executivo (principais achados)
    * Metodologia e Preparação dos Dados
    * Análise Descritiva (EDA) com gráficos
    * Análise Inferencial (Intervalos de Confiança)
    * Insights e Recomendações de Negócio

2.  💻 **/codigo/analise_ecommerce.ipynb**: O notebook Python (Jupyter) contendo todo o pipeline de análise, garantindo a reprodutibilidade. Inclui:
    * Importação e Limpeza de Dados (Data Cleaning)
    * Engenharia de Features (Feature Engineering)
    * Cálculo de KPIs
    * Geração de todas as visualizações e cálculos estatísticos.

## 4. 🚀 Como Executar a Análise

Todo o código-fonte da análise está no notebook `codigo/analise_ecommerce.ipynb`. Para executá-lo, você precisará do arquivo de dados `[nome_do_dataset.csv]`.

**Importante:** Antes de começar, coloque o arquivo `[nome_do_dataset.csv]` dentro da pasta `dados/`. O notebook está programado para procurar o dataset nesse local.

Existem duas formas de rodar o projeto:

### Opção 1: Google Colab (Recomendado e mais fácil)

1.  Acesse o [Google Colab](https://colab.research.google.com/).
2.  Clique em `Arquivo > Upload de notebook...` e selecione o arquivo `codigo/analise_ecommerce.ipynb` do nosso projeto.
3.  No menu lateral esquerdo do Colab, clique no ícone de "Pasta" (Arquivos).
4.  Clique em "Fazer upload" e selecione o arquivo de dados `[nome_do_dataset.csv]`.
    * *Nota: Se o arquivo estiver em seu Google Drive, você pode conectá-lo clicando no ícone do Drive.*
5.  **Pronto!** Agora basta executar as células do notebook na ordem. As bibliotecas (`pandas`, `seaborn`, etc.) já vêm instaladas no Colab.

### Opção 2: Localmente (Jupyter Notebook ou VS Code)

Se preferir rodar na sua própria máquina:

1.  **Clone o projeto:**
    ```bash
    git clone https://github.com/vic-fmr/ecommerce-analytics.git
    cd ecommerce-analytics
    ```

2.  **Verifique o dataset:** Confirme se esses arquivos existem na pasta `dados/`.
<img width="241" height="210" alt="image" src="https://github.com/user-attachments/assets/68864a42-b5c6-4469-8e77-c49ad20c70d2" />

3.  **Instale as bibliotecas:** Você precisará das bibliotecas de análise de dados. Você pode instalá-las via `pip` no seu terminal:
    ```bash
    pip install pandas numpy matplotlib seaborn scipy jupyter
    ```

4.  **Execute o Notebook:**
    * **Pelo Terminal:**
      ```bash
      jupyter notebook codigo/analise_ecommerce.ipynb
      ```
    * **Pelo VS Code:**
      Abra o VS Code, acesse a pasta do projeto e abra o arquivo `codigo/analise_ecommerce.ipynb`.

5.  Execute todas as células na ordem.
