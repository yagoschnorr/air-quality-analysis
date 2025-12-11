# Análise de Qualidade do Ar - Beijing Changping

Projeto de Modelagem Estatística desenvolvido para análise de dados de poluição atmosférica em Beijing, China, utilizando técnicas de Machine Learning e análise estatística.

**Autores:** Yago Patrick Schnorr Pinto e Gabriel Costa de Miranda  
**Instituição:** CESUPA - Centro Universitário do Estado do Pará  
**Disciplina:** Modelagem Estatística - CC4  

---

## 📌 Sobre o Projeto

Este projeto aplica técnicas de aprendizado de máquina e análise estatística para:
- Prever níveis de concentração de PM2.5 (material particulado fino)
- Classificar a qualidade do ar em categorias de risco
- Identificar fatores que influenciam a poluição atmosférica
- Avaliar o impacto de condições meteorológicas na dispersão de poluentes

### Dataset
**Fonte:** [UCI Machine Learning Repository - Beijing Multi-Site Air-Quality Data](https://archive.ics.uci.edu/dataset/501/beijing+multi+site+air+quality+data)  
**Período analisado:** Ano de 2016  
**Estação:** Changping, Beijing, China  
**Registros:** 8.459 (após limpeza)

---

## 🚀 Como Executar

### Pré-requisitos
- Python 3.10
- Jupyter Notebook

### Passos

1. **Clone o repositório:**
```bash
git clone https://github.com/yagoschnorr/air-quality-analysis.git
cd air-quality-analysis
```

2. **Instale as dependências:**
```bash
pip install -r requirements.txt
```

3. **Execute o notebook:**
```bash
jupyter notebook analysis.ipynb
```

4. **Execute as células sequencialmente** (Run All ou célula por célula)

---

## 📊 Metodologia

### 1. Análise Exploratória (EDA)
- Mapas de calor de correlação
- Histogramas e distribuições
- Gráficos de dispersão
- Detecção de outliers

### 2. Testes Estatísticos
- **Teste t de Welch:** Comparação de médias entre grupos
- **Teste Qui-Quadrado:** Associação entre variáveis categóricas
- **Correlação de Pearson:** Significância estatística das correlações

### 3. Modelos de Regressão
- Regressão Linear Simples
- Regressão Linear Múltipla
- Regressão Polinomial

### 4. Modelos de Classificação
- Naive Bayes
- Regressão Logística

## 📁 Estrutura do Projeto

```
air-quality-analysis/
│
├── analysis.ipynb              # Notebook principal com toda a análise
├── requirements.txt            # Dependências do projeto
├── LICENSE                     # Licença MIT
├── README.md                   # Este arquivo
│
└── data/
    └── PRSA_Data_Changping_20130301-20170228.csv
```

## 🛠️ Tecnologias Utilizadas

- **Python 3.10+**
- **Pandas & NumPy** - Manipulação de dados
- **Matplotlib & Seaborn** - Visualização
- **Scikit-learn** - Machine Learning
- **Statsmodels** - Análise estatística
- **SciPy** - Testes estatísticos
- **PyCaret** - AutoML

## 📄 Licença

Este projeto está sob a licença MIT.