# Projeto de Mineração de Dados: Análise Preditiva de Preços de Smartphones para o Mercado de 2025

Este projeto foi desenvolvido para a disciplina de Mineração de Dados e tem como objetivo aplicar técnicas de análise de dados e machine learning para entender e prever os preços de smartphones com base em suas especificações técnicas.

## 1. Descrição do Problema e Objetivos

### Problema
O mercado de smartphones é segmentado por diversas faixas de preço, e o valor final de um aparelho é influenciado por uma complexa combinação de fatores (memória RAM, qualidade da câmera, capacidade da bateria, etc.). Para um consumidor ou analista de mercado, entender quais características mais contribuem para o custo de um aparelho é um desafio. O problema central deste projeto é: **Quais especificações técnicas são os principais fatores que determinam o preço de um smartphone no mercado previsto para 2025?**

### Objetivo Principal
Desenvolver um modelo de aprendizado de máquina capaz de **prever o preço (`price_usd`)** de um smartphone com base em suas especificações técnicas, como RAM, armazenamento, câmera e processador.

### Objetivos Secundários
*   Realizar uma análise exploratória de dados para entender a correlação entre as especificações técnicas e o preço.
*   Identificar quais marcas (Apple, Samsung, Xiaomi, etc.) tendem a se posicionar em segmentos de preço mais altos ou mais baixos.
*   Treinar e comparar diferentes modelos de regressão (ex: Regressão Linear, Random Forest Regressor) para determinar qual oferece a previsão de preços mais precisa.
*   Gerar insights sobre quais características mais agregam valor a um smartphone.

## 2. Conjunto de Dados (Dataset)

*   **Nome:** Global Mobile Prices 2025 Extended (Nome do arquivo usado)
*   **Fonte:** Kaggle
*   **Link:** [https://www.kaggle.com/datasets/shahzadi786/world-smartphone-market-2025](https://www.kaggle.com/datasets/shahzadi786/world-smartphone-market-2025)
*   **Descrição:** O dataset contém uma simulação de 1000 modelos de smartphones a serem lançados em 2025, com suas respectivas especificações técnicas e preços de varejo em USD.

## 3. Divisão de Tarefas

*   **Fundação do Projeto - Leonardo Pereira Gonçalves:** Definição do problema, criação do repositório, estruturação de pastas, documentação inicial e carga/análise inicial dos dados.
*   **ETL (Extração, Transformação e Carga) - Henrique Murakami Silva:** Responsável pela limpeza e preparação dos dados para análise, seguindo as instruções no notebook `01-etl.ipynb`.
*   **Análise Exploratória e Visualizações - Kayque Soares:** Responsável por gerar gráficos e insights a partir dos dados limpos (notebook `02-analise-exploratoria.ipynb`).
*   **Modelagem e Machine Learning - Leonardo dos Santos Pereira:** Responsável por treinar e testar os modelos de previsão de preço (notebook `03-modelagem.ipynb`).
*   **Avaliação e Conclusão - [Nome do Colega 4]:** Responsável por avaliar a performance dos modelos, interpretar os resultados e redigir a conclusão do projeto (notebook `04-avaliacao-e-resultados.ipynb`).

## 4. Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/nizoelgp/Projeto-Pratico-PP-Mineracao-De-Dados.git
    ```
2.  **Instale as bibliotecas necessárias:**
    ```bash
    pip install pandas matplotlib seaborn scikit-learn jupyter
    ```
3.  **Para reproduzir a análise inicial**, acesse o notebook `01-etl.ipynb` compartilhado no Google Colab. As etapas seguintes continuarão a partir dele.
	[**Link para o NoteBook no Google Colab**](https://colab.research.google.com/drive/1uq-E_8EAg81pfCQ14dkUZi-Eq9gefpMQ?usp=sharing)

## 5. Documentação

O relatório acadêmico completo do projeto está sendo desenvolvido em LaTeX e pode ser encontrado na pasta `/docs`.

*   **Para ler a versão mais recente**, acesse o arquivo [**`main.pdf`**](./docs/main.pdf) diretamente no GitHub.
*   **Para colaborar na edição do documento**, utilize nosso ambiente de trabalho no Overleaf: [**Link para o Projeto no Overleaf**](https://pt.overleaf.com/6542975238bxfsmkzkzqsr#d8878b)
