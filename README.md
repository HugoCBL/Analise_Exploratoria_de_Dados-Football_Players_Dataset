# 📊 Análise Exploratória de Dados – Football Players Dataset

Este repositório contém uma Análise Exploratória de Dados (EDA) realizada sobre um conjunto de dados de jogadores de futebol. O objetivo é investigar padrões, relações entre variáveis, distribuições, outliers, correlações e reduzir dimensionalidade utilizando UMAP.

---

## 📁 **Conteúdo do Projeto**

* **Carregamento e limpeza do dataset**
* **Análise inicial (head, dimensões, tipos, valores ausentes)**
* **Estatísticas descritivas das variáveis numéricas**
* **Análise detalhada das variáveis categóricas**
* **Análise da variável-alvo (Preferred Foot)**
* **Identificação e visualização de outliers**
* **Correlação entre atributos (heatmap)**
* **Scatterplots e Pairplots para relacionamentos entre features**
* **Projeção UMAP (redução de dimensionalidade)**
* **Interpretação dos resultados gráficos**

---

## 🛠️ **Tecnologias Utilizadas**

* **Python 3**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **UMAP-learn**

---

## 📂 **Arquivos Principais**

* `FootballPlayersDataset.csv` — Dataset utilizado
* `Analise_Exploratoria_de_Dados-Football_Players_Dataset.ipynb` — Código completo da análise
* `README.md` — Este arquivo

---

## 🔍 **Principais Insights**

* O dataset contém informações detalhadas de mais de 490 jogadores, com atributos físicos, técnicos e estatísticos.
* A variável-alvo analisada foi **Preferred_Foot (pé preferido)**.
* Há **desbalanceamento**: cerca de 78% destros e 22% canhotos.
* Variáveis como **Overall**, **BallControl**, **Reactions** e **Composure** apresentam forte correlação.
* A coluna de valor de mercado (**Value_Num**) possui muitos outliers superiores — esperado devido a poucos atletas altamente valorizados.
* O UMAP mostrou agrupamentos baseados em características estatísticas dos jogadores, ainda que o target não forme clusters bem separados (o que é natural, já que “pé preferido” não depende de habilidade técnica).

---

## 📉 **Exemplos de Visualizações Produzidas**

* Gráficos de barras para variáveis categóricas
* Gráfico de pizza para distribuição da classe
* Boxplots para outliers
* Heatmap de correlação
* Scatterplots e Pairplots
* Projeção UMAP em 2D colorida pelo pé preferido

---

## ▶️ **Como Executar**

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/seurepositorio.git
cd seurepositorio
```

2. Instale as dependências:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn umap-learn
```

3. Abra o notebook:

```bash
jupyter notebook
```
