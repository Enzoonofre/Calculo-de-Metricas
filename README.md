# 🌍 Avaliação de Modelos de Classificação

## 📌 Descrição do Projeto
Este projeto tem como objetivo calcular as principais métricas para avaliação de modelos de classificação, como:
- **Acurácia**
- **Sensibilidade (Recall)**
- **Especificidade**
- **Precisão**
- **F1-score**
- **Curva ROC**

Os valores utilizados para o cálculo dessas métricas foram extraídos de um projeto anterior de **Processamento de Linguagem Natural (PLN)**, que participei em um **desafio do Kaggle** 🏆. Nesse desafio, desenvolvi um modelo para classificar **tweets** e determinar se eles estavam relacionados a um desastre natural 🌪️ ou não. Para isso, utilizei um conjunto de dados contendo mensagens do Twitter rotuladas com `1` (relacionado a desastres) ou `0` (não relacionado). A partir dos resultados desse modelo, extrai os valores de **Verdadeiro Positivo (VP), Falso Positivo (FP), Verdadeiro Negativo (VN) e Falso Negativo (FN)** para calcular as métricas descritas neste projeto.

---

## 🛠️ Tecnologias Utilizadas
- **Python**
- **Bibliotecas:** `scikit-learn`, `matplotlib`, `pandas`

---

## 🚀 Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/Enzoonofre/Calculo-de-Metricas.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd Calculo-de-Metricas
   ```
3. Execute o código principal:
   ```bash
   python matriz_de_confusão.py
   ```

---

## 📊 Resultados
O projeto gera os seguintes resultados:
- **Matriz de Confusão:** Exibe a quantidade de acertos e erros do modelo.
- **Métricas de Avaliação:** Acurácia, Recall, Precisão, Especificidade e F1-score.
- **Curva ROC:** Gráfico da performance do modelo comparando Taxa de Verdadeiros Positivos (TPR) e Taxa de Falsos Positivos (FPR).

---

## 📌 Exemplo de Saída
### 🎯 Matriz de Confusão
```
[[368  70]
 [ 99 225]]
```
### 📊 Métricas Calculadas
```
Acurácia: 0.77
Recall: 0.84
Especificidade: 0.69
Precisão: 0.78
F1-score: 0.81
```
### 📈 Curva ROC
O projeto plota a curva ROC para avaliar o desempenho do classificador graficamente.

---

## 👤 Autor
- [Enzo Onofre](https://github.com/Enzoonofre)

Se tiver alguma dúvida ou sugestão, fique à vontade para abrir uma **issue** ou contribuir com este projeto! 🚀

