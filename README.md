# S3A — Previsão de Tempestades Geomagnéticas

Projeto de Machine Learning da Global Solution FIAP 2026. O objetivo é prever se um dia vai ter tempestade geomagnética com base em dados históricos de índices K e A da NOAA. A solução se conecta ao projeto S3A, uma rede de mini-droids sísmicos que dependem de janelas de comunicação estáveis entre a Terra e sondas espaciais.

## Como rodar

### 1. Requisitos

- Python 3.9+
- Dataset `daily_solar_data.csv` na raiz do projeto (baixar em: https://www.kaggle.com/datasets/erevear/space-weather-solar-geomagnetic-indices?select=daily_solar_data.csv)

### 2. Instalar dependências

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 3. Executar o notebook

```bash
jupyter notebook S3A_SpaceWeather_ML.ipynb
```

Ou rodar tudo via terminal:

```bash
jupyter nbconvert --to notebook --execute S3A_SpaceWeather_ML.ipynb --output S3A_SpaceWeather_ML.ipynb
```

## Integrantes

| Nome | RM |
|---|---|
| Matheus Cantiere | RM558479 |
| Marco Antonio Gonçalves | RM556818 |
| Guilherme Barbiero | RM555185 |
| Vinicius Castro | RM556137 |
| Camila Mie Takara | RM555418 |
