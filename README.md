# Projeto: Análise de Bullying Escolar com Base nos Dados de 2018

Este repositório apresenta um projeto de análise de dados para explorar e modelar informações relacionadas ao bullying escolar com base no dataset **Bullying\_2018.csv**. O projeto foi estruturado seguindo a metodologia **CRISP-DM** (Cross-Industry Standard Process for Data Mining), garantindo uma abordagem sistemática e replicável.

## Estrutura do Repositório

- **Documentação**:

  - Aplicação da metodologia **CRISP-DM**, abordando:
    1. **Entendimento do Negócio**: Contextualização do problema de bullying escolar.
    2. **Entendimento dos Dados**: Exploração inicial dos dados.
    3. **Preparação dos Dados**: Processamento e limpeza para modelagem.
    4. **Análises**: Visualizações e insights iniciais.
    5. **Modelagem**: Desenvolvimento e avaliação de modelos preditivos.
    6. **Avaliação**: Discussão sobre os resultados obtidos.

- **Arquivos do Projeto**:

  - `EDA.ipynb`: Análise Exploratória dos Dados (Exploratory Data Analysis).
  - `Wrangling.ipynb`: Limpeza e transformação dos dados.
  - `Model.ipynb`: Construção e avaliação dos modelos de aprendizado de máquina.

- **Dados**:

  - `data/raw`: Contém os dados brutos (“Bullying\_2018.csv”).
  - `data/processed`: Contém os dados processados para análise e modelagem.

- **Dashboard**:

  - Um dashboard interativo para exploração dos resultados.

## Tecnologias e Ferramentas

- **Linguagem**: Python.
- **Bibliotecas Principais**:
  - `pandas`, `numpy`: Manipulação e análise de dados.
  - `matplotlib`, `seaborn`, `plotly`: Visualização de dados.
  - `scikit-learn`: Modelagem preditiva.
  - `shap`: Explicabilidade de modelos.
- **Dashboard**: Desenvolvido com bibliotecas interativas como `Dash` ou `Streamlit` (especificar qual).

## Metodologia CRISP-DM

1. **Entendimento do Negócio**:

   - O objetivo é identificar fatores associados ao bullying escolar com base em variáveis como ambiente escolar, apoio familiar e comportamentos dos estudantes.

2. **Entendimento dos Dados**:

   - O dataset contém informações relacionadas à experiência de estudantes sobre bullying, incluindo variáveis demográficas, acadêmicas e emocionais.

3. **Preparação dos Dados**:

   - Limpeza de dados: tratamento de valores ausentes e outliers.
   - Codificação de variáveis categóricas (OneHotEncoder).
   - Escalonamento de variáveis numéricas (StandardScaler).

4. **Análises**:

   - Exploração visual de correlações entre variáveis.
   - Identificação de padrões e insights.

5. **Modelagem**:

   - Modelos testados:
     - Regressão Logística.
     - Métodos de balanceamento de classes (SMOTE e RandomUnderSampler).
   - Métricas de avaliação: AUC-ROC, F1-score, precisão e recall.

6. **Avaliação**:

   - Discussão sobre a performance dos modelos e insights gerados.

## Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu_usuario/bullying_2018_analysis.git

2. Instale as dependências:
    ```bash
    !pip install -r requirements.txt

3. Execute os notebooks:

Certifique-se de que os dados estão no diretório correto (data/raw).
Abra os arquivos .ipynb no Jupyter Notebook ou JupyterLab.

4. Visualize o dashboard:

Siga as instruções no diretório dashboard para rodar a aplicação localmente.


## Resultados
- Insights relevantes sobre fatores associados ao bullying.
- Modelo preditivo com explicações visuais (é importante mencionar algum destaque, como interpretabilidade ou impacto das variáveis).
- Visualizações interativas para stakeholders.

## Contribuições
- São bem-vindas sugestões, relatórios de problemas e solicitações de funcionalidades. Para contribuir:

1. Crie um fork do repositório.
2. Implemente as alterações.
3. Envie um pull request.

## Licença
Este projeto está licenciado sob a Licença MIT.

## Autores:
Ana Carolina Szczepanski Oliveira, Claisa Lubke, Elis Regina Weiss, Hanna
Câmara da Justa, Iris Brandao Pires Linhares, Isabella Stersa de Oliveira, Larissa das
Chagas Brum, Lidiane Vicente
