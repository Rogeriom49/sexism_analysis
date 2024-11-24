# Classificação de Sexismo com Machine Learning  
Este projeto tem como objetivo explorar dados, realizar análises e desenvolver um modelo de machine learning para identificar e classificar conteúdos com teor sexista. Utilizamos técnicas de processamento de linguagem natural (NLP) e algoritmos de aprendizado de máquina para resolver o problema.

## 📋 Objetivo  
Criar um modelo preditivo que detecte e classifique automaticamente textos sexistas, auxiliando na moderação de conteúdo em plataformas digitais.

## 🛠️ Funcionalidades  
- **Exploração e Análise de Dados**: Entender padrões e características dos dados de entrada.  
- **Limpeza e Pré-processamento**: Tratamento dos dados textuais (remoção de ruído, tokenização, stemming, etc.).  
- **Desenvolvimento de Modelos**: Implementação de algoritmos de classificação como Naive Bayes, SVM, e Redes Neurais.  
- **Avaliação de Modelos**: Comparação do desempenho dos modelos utilizando métricas como acurácia, precisão, recall e F1-score.  

## 📂 Estrutura do Projeto  
```plaintext
├── datasets/                                  # Datasets utilizados para análise  
├── sexism_analysis_lstm.ipynb/                # Modelo LSTM
├── sexism_analysis_randomforest.ipynb/        # Modelo RandomForestClassifier
└── README.md                                  # Documentação do projeto  
```

## 📊 Dataset  
Os dados utilizados são provenientes de [https://www.kaggle.com/datasets/aadyasingh55/sexism-detection-in-english-texts].   

## 📈 Resultados  
Os modelos desenvolvidos obtiveram os seguintes resultados:  
| Modelo       | Acurácia | Precisão | Recall | F1-score |  
|--------------|----------|----------|--------|----------|  
| RandomForest | 83%      | 83%      | 98%    | 90%      |  
| LSTM         | 80%      | 88%      | 87%    | 87%      |  

## 🔧 Tecnologias Utilizadas  
- **Linguagem**: Python  
- **Bibliotecas principais**:  
  - `scikit-learn`  
  - `pandas`  
  - `numpy`  
  - `nltk`  
  - `matplotlib`  
  - `seaborn`
  - `TensorFlow`  

## 🤝 Contribuições  
Contribuições são bem-vindas! Para contribuir, abra uma *issue* ou envie um *pull request*.  

## 📝 Licença  
Este projeto está licenciado sob a [Licença MIT](LICENSE).  

---

Se precisar de ajuda para personalizar ou expandir, é só avisar! 😊
