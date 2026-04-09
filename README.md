# MVP: Análise de Dados e Boas Práticas - Dataset Fogo Cruzado

## 📌 Descrição do Projeto
Este projeto integra o MVP da disciplina de **Análise de Dados e Boas Práticas**. A pesquisa consiste em uma Análise Exploratória de Dados (EDA) fundamentada no dataset público do **Fogo Cruzado**, monitorando a violência armada nas regiões metropolitanas do Rio de Janeiro, Bahia e Pernambuco entre 2016 e 2022.

O objetivo central é identificar padrões demográficos e geográficos que permitam validar hipóteses sobre o impacto social da violência e preparar os dados para futuros modelos de classificação e predição.

## 🚀 Hipóteses Investigadas

1. **Padrão Geracional:** Existe uma concentração estatística da violência armada na faixa etária correspondente aos jovens adultos (confirmada pela mediana de 28 anos e intervalo interquartil entre 22 e 38 anos).

2. **Concentração Territorial:** A violência armada manifesta-se de forma clusterizada em polos de alta densidade urbana, apresentando baixíssima dispersão geográfica (conforme validado pelos boxplots de latitude e longitude).

3. **Sazonalidade Temporal:** A ocorrência de tiroteios segue um padrão não aleatório, com ciclos de repetição que coincidem com a rotina de mobilidade urbana e dinâmica funcional das metrópoles.
   
## 📊 Principais Insights da Análise Exploratória

### 1. Análise de Idade (Quartis e Mediana)
A análise estatística da variável `age` revelou uma concentração severa na juventude:
* **1º Quartil (25%):** 22 anos.
* **Mediana (50%):** 28 anos.
* **3º Quartil (75%):** 38 anos.
* **Insight:** 50% das vítimas registradas têm entre 22 e 38 anos, confirmando o alto impacto social em populações jovens.

### 2. Dispersão Geográfica (Latitude e Longitude)
O uso de **Boxplots** permitiu validar a integridade espacial dos dados:
* **Latitude:** Mediana de **-12.92**, com o 1º Quartil em **-13.07** (marcando a densidade na Bahia) e o 3º Quartil em **-12.63**.
* **Longitude:** Mediana de **-38.47**, reforçando a concentração em eixos metropolitanos litorâneos.
* **Validação:** A baixa dispersão (bigodes curtos nos gráficos) confirma que os dados são robustos e adequados para modelos preditivos territorializados.

<img width="1368" height="521" alt="image" src="https://github.com/user-attachments/assets/f79a6d41-c4c4-401b-838c-48739f874b08" />


## 🛠️ Tecnologias e Ferramentas
* **Linguagem:** Python 3.x
* **Ambiente:** Google Colab
* **Bibliotecas Principais:**
  * `Pandas`: Limpeza e estruturação dos dados.
  * `Seaborn` & `Matplotlib`: Visualizações estatísticas e gráficas.
  * `Numpy`: Processamento matemático.

## 📂 Organização do Repositório
* `notebook/`: Contém o arquivo `FogoCruzado.ipynb` com o código-fonte completo.
* `reports/`: Versão em PDF do relatório final (MVP.pdf).
* `README.md`: Documentação e guia do projeto.

## 🔗 Acesso ao Projeto
O desenvolvimento completo, incluindo o tratamento de dados e geração de gráficos, pode ser visualizado diretamente no Google Colab:
👉 [Acessar Notebook no Google Colab](https://colab.research.google.com/github/rgomesa2025/MVP_Analise_Dados_E_Boas_Praticas_Rosangela/blob/main/notebook/FogoCruzado.ipynb)
