# Projeto de Machine Learning: Previsão de Sobrevivência no Titanic

Este projeto tem como objetivo prever a sobrevivência de passageiros do Titanic utilizando técnicas de Machine Learning.

## 📌 Visão Geral

O naufrágio do Titanic é um dos desastres marítimos mais conhecidos da história. Neste projeto, analisamos os dados dos passageiros para entender quais fatores contribuíram para a sobrevivência e construímos um modelo preditivo para estimar a probabilidade de sobrevivência com base nas características dos passageiros.

## 🛠️ Tecnologias Utilizadas

- Python 3
- Jupyter Notebook
- Bibliotecas:
  - Pandas, NumPy, Matplotlib, Seaborn
  - Scikit-learn
  - XGBoost

## 📊 Métricas do Modelo

O melhor modelo (XGBoost otimizado) alcançou:

- Acurácia: 83.2%
- Precisão: 81.5%
- Recall: 74.2%
- F1-score: 77.7%
- AUC-ROC: 88.1%

## 📂 Estrutura do Projeto

1. **Análise Exploratória de Dados (EDA)**: Análise detalhada dos dados e geração de insights.
2. **Pré-processamento**: Limpeza, tratamento de valores ausentes e engenharia de features.
3. **Modelagem**: Implementação e comparação de vários algoritmos de ML.
4. **Otimização**: Ajuste de hiperparâmetros para melhorar o desempenho.
5. **Avaliação**: Análise detalhada dos resultados e importância das features.

## 📝 Como Executar

1. Clone o repositório
2. Instale as dependências: `pip install -r requirements.txt`
3. Execute o Jupyter Notebook: `jupyter notebook Titanic_Survival_Prediction.ipynb`

## 📚 Referências

- Dataset: [Titanic Dataset from DataScienceDojo](https://github.com/datasciencedojo/datasets)
- Scikit-learn Documentation
- XGBoost Documentation
