# PredictaShop

**Maquina de previsão de comportamento do consumidor em e-commerce (Olist)**

## Descrição

PredictaShop é uma aplicação de machine learning desenvolvida com Streamlit que prevê o comportamento de consumidores em plataformas de e-commerce, utilizando dados do dataset Olist.

## Requisitos

- Python >=3.12,<3.13
- Dependências conforme especificado em `pyproject.toml`

## Instalação

### Com UV (recomendado)

```bash
uv pip install -e .
```

### Com pip padrão

```bash
pip install -r requirements.txt
```

## Execução

Para iniciar a aplicação Streamlit:

```bash
streamlit run streamlit_app.py
```

## Dependências Principais

- **streamlit** - Framework web para ML
- **pandas** - Manipulação de dados
- **scikit-learn** - Algoritmos de ML
- **xgboost** - Gradient boosting
- **lightgbm** - Light gradient boosting
- **shap** - Interpretabilidade de modelos
- **matplotlib** & **plotly** - Visualizações

## Licença

Apache License 2.0
