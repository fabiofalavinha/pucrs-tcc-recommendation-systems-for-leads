# Modelos de Qualificação de Leads

Este repositório contém os arquivos e modelos utilizados para a qualificação de leads usando diferentes algoritmos de machine learning. Os dados utilizados são fictícios e foram gerados especificamente para este estudo. O repositório inclui:

- **Leads.csv**: Arquivo CSV contendo os dados fictícios dos leads.
- **LogisticRegressionModel.ipynb**: Notebook Jupyter com a implementação e avaliação do modelo de Regressão Logística.
- **DecisionTreeModel.ipynb**: Notebook Jupyter com a implementação e avaliação do modelo de Árvores de Decisão.
- **RandomForestModel.ipynb**: Notebook Jupyter com a implementação e avaliação do modelo de Floresta Aleatória.
- **GradientBoostingModel.ipynb**: Notebook Jupyter com a implementação e avaliação do modelo de Gradient Boosting.
- **SVMModel.ipynb**: Notebook Jupyter com a implementação e avaliação do modelo de Support Vector Machine (SVM).
- **requirements.txt**: Arquivo de requisitos com todas as bibliotecas necessárias para executar os modelos.

## Instruções de Uso

1. Clone este repositório:

```
git clone <URL-do-repositório>
```

2. Navegue até o diretório do repositório:

```
cd lead-qualification-models
```

3. Instale as dependências:

```
pip install -r requirements.txt
```

4. Abra os notebooks Jupyter para visualizar e executar os modelos:

```
jupyter notebook
```

## Modelos Incluídos

- **Regressão Logística**: Utilizado para prever a probabilidade de um lead se converter em um cliente com base em atributos específicos.
- **Árvores de Decisão**: Modelo de aprendizado supervisionado que divide os dados em subconjuntos baseados em valores de atributos.
- **Floresta Aleatória**: Conjunto de árvores de decisão que melhora a precisão da classificação ao reduzir o sobreajuste.
- **Gradient Boosting**: Técnica de ensemble que combina vários modelos fracos para formar um modelo forte.
- **SVM (Support Vector Machine)**: Modelo de classificação que encontra o hiperplano que maximiza a margem entre diferentes classes.

## Dados

Os dados fictícios dos leads foram gerados utilizando a biblioteca Faker e incluem múltiplos pontos de dados como e-mail, domínio do e-mail, país, número de funcionários, cargo, setor, engajamento com conteúdo, histórico de compras e interações anteriores.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias e correções.
