# 🚢 Titanic — Machine Learning from Disaster

Este projeto tem como objetivo analisar o conjunto de dados **Titanic: Machine Learning from Disaster** (Kaggle) e desenvolver **modelos preditivos de sobrevivência** baseados em informações dos passageiros.  

O estudo segue as etapas clássicas de um fluxo de *machine learning supervisionado*, envolvendo **limpeza dos dados**, **engenharia de atributos**, **modelagem preditiva** e **avaliação de desempenho**.

---

## 📊 1. Limpeza e Pré-Processamento

Nesta etapa foi realizado o **tratamento e preparação dos dados** para que pudessem ser utilizados pelos algoritmos de aprendizado de máquina.  

As principais ações incluídas foram:

- Remoção de colunas com grande número de valores ausentes, como `Cabin`.
- Tratamento de valores faltantes em `Age` e `Embarked`.
- Conversão de variáveis categóricas (`Sex`, `Embarked`) em formato numérico.
- Padronização de variáveis contínuas para melhorar a estabilidade dos modelos.

Essas etapas garantem que o conjunto de dados esteja limpo e consistente.

---

## ⚙️ 2. Engenharia de Features

O notebook realiza **criação e transformação de variáveis** para aumentar a capacidade preditiva dos modelos.

Principais transformações:

- Criação de novas variáveis derivadas, como **FamilySize** (baseada em `SibSp` + `Parch` + 1).
- Conversão da variável `Survived` em formato binário (0 = não sobreviveu, 1 = sobreviveu).
- Ajuste de variáveis numéricas e categóricas para melhor adequação aos modelos supervisionados.

Essas transformações permitem extrair **padrões ocultos** e gerar uma base de dados mais representativa.

---

## 🤖 3. Modelagem Preditiva

Foram aplicados e comparados diversos **algoritmos de classificação supervisionada**, entre eles:

- **Logistic Regression**  
- **Decision Tree**  
- **Random Forest**  
- **Gradient Boosting**  
- **SVM (Support Vector Machine)**  

Os modelos foram avaliados com base em métricas de **acurácia** e **validação cruzada**, com o objetivo de identificar qual técnica apresentou melhor desempenho.

---

## 📈 4. Avaliação dos Modelos

A análise comparativa permitiu observar diferenças significativas entre os algoritmos.  
Modelos baseados em *ensemble learning* (como Random Forest e Gradient Boosting) mostraram **maior capacidade de generalização** e desempenho mais robusto frente aos demais.

Gráficos e relatórios de métricas foram utilizados para visualizar o desempenho e compreender os fatores mais influentes na sobrevivência dos passageiros.

---

## 🧩 5. Conclusão

O projeto demonstra a aplicação prática de **técnicas de aprendizado supervisionado** na resolução de um problema clássico de classificação.  

Com base nos resultados, observa-se que características como **sexo, idade e classe social** foram as mais determinantes para a sobrevivência no desastre.  
O estudo reforça a importância do **pré-processamento de dados** e da **engenharia de features** na construção de modelos preditivos eficientes.

---

## 🛠️ Tecnologias Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 📚 Fonte dos Dados

Conjunto de dados disponível no Kaggle:  
[Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
