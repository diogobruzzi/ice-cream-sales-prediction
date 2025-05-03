# ice-cream-sales-prediction

# Prevendo Vendas de Sorvete com Machine Learning 🍦📊

## 📌 Visão Geral
Projeto para prever vendas de sorvete baseado na temperatura usando ML.

## 🛠️ Tecnologias
- Python 3.8+
- Scikit-learn
- MLflow
- Flask (para API)

## 📊 Dataset
Dados sintéticos gerados com:
- Temperaturas diárias (média 25°C)
- Vendas calculadas como `temp * 30 + ruído`

## 🚀 Como Usar
1. Clone o repositório
2. Instale as dependências: `pip install -r requirements.txt`
3. Rode o notebook de exploração
4. Treine o modelo: `python src/train_model.py`
5. Inicie a API: `python src/predict.py`

## 📈 Resultados
O modelo linear alcançou:
- R²: 0.85
- MSE: 2200

## 🌟 Melhorias Futuras
- Coletar dados reais
- Testar outros algoritmos
- Deploy em cloud (AWS/GCP)
