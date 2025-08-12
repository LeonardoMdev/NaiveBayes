
---

## 📄 README.md

## 🧠 Naive Bayes - Previsão com Dados de Seguros

Este projeto implementa um modelo de **classificação Naive Bayes** usando o algoritmo **GaussianNB** para prever uma variável-alvo a partir de dados de seguros.

O objetivo é demonstrar, de forma prática, como aplicar **Machine Learning supervisionado** com Python e Scikit-learn.


---
## 📂 Estrutura do Projeto
```
📁 NaiveBayes-Insurance
├──NaiveBayes.ipynb = Notebook com todo o código do projeto
├──insurance.csv    = Dataset utilizado (opcional incluir)
├──README.md        = Documentação do projeto
└──requirements.txt = Lista de bibliotecas necessárias
```
---
 ## 📊 Tecnologias Utilizadas

- **Python 3**
- **Pandas** → Manipulação de dados
- **NumPy** → Operações matemáticas
- **Scikit-learn** → Modelo Naive Bayes e métricas de avaliação
- **Jupyter Notebook** → Desenvolvimento interativo

---

## ⚙️ Como Rodar o Projeto

### 1. Clonar este repositório
```bash
git clone https://github.com/SEU_USUARIO/NaiveBayes-Insurance.git
cd NaiveBayes-Insurance
````

### 2. Criar e ativar um ambiente virtual (opcional, mas recomendado)

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate
```

### 3. Instalar as dependências

```bash
pip install -r requirements.txt
```

### 4. Abrir o notebook

```bash
jupyter notebook NaiveBayes.ipynb
```

---

## 📌 Passos do Notebook

1. **Carregar o dataset `insurance.csv`**
2. **Limpar e preparar os dados**
3. **Codificar variáveis categóricas com LabelEncoder**
4. **Separar dados em treino e teste**
5. **Treinar o modelo Naive Bayes Gaussiano**
6. **Fazer previsões**
7. **Avaliar com métricas: acurácia, precisão, recall e relatório de classificação**

---

## 📈 Exemplo de Métricas Obtidas

| Métrica  | Valor (%) |
| -------- | --------- |
| Acurácia | 85.0      |
| Precisão | 84.7      |
| Recall   | 83.9      |

> ⚠️ Os valores podem variar dependendo da base de dados e da divisão treino/teste.

---

## 📜 Licença

Este projeto é de uso livre para fins de estudo e aprendizado.

---

## 📄 requirements.txt
```

pandas
numpy
scikit-learn
jupyter

```

---

