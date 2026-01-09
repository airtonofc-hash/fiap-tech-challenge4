# FIAP Tech Challenge 4 - Predição de Obesidade

## 📋 Descrição
Projeto de machine learning para predição de obesidade utilizando dados comportamentais e demográficos. Desenvolvido como parte do Tech Challenge 4 da FIAP.

## 🎯 Objetivo
Desenvolver modelos de classificação para predizer obesidade com base em características como idade, gênero, hábitos alimentares, atividade física e outros fatores comportamentais.

## 🔗 Links
- **Aplicação Streamlit**: https://fiap-tech-challenge4-kybsnv8jz5ng8nsizhkpae.streamlit.app/
- **Painel Analítico**: https://fiap-tech-challenge4-kybsnv8jz5ng8nsizhkpae.streamlit.app/
- **Repositório**: https://github.com/airtonofc-hash/fiap-tech-challenge4

## 📁 Estrutura do Projeto
```
tech4/
├── DATASETS/                    # Dados para análise
│   ├── dados_machine_learning.csv
│   └── Engenharia de feature e pré processamento.xlsx
├── MACHINE LEARNING/            # Notebooks e modelos
│   ├── notebook.ipynb
│   └── requirements.txt
├── MATERIAL REFERÊNCIA/         # Documentação de apoio
│   ├── dicionario_obesity_fiap.pdf
│   ├── Obesity.csv
│   └── POSTECH - Tech Challenge - Fase 4 -  Data Analytics_.pdf
├── POWER BI/                    # Dashboard analítico
│   └── Tech Challenge 4 BI.v1.pbix
└── STREAMLIT/                   # Aplicação web
    ├── streamlit_app.py
    └── Links + Código APP Streamlit.txt
```

## 🤖 Modelos Implementados
- **Random Forest**: Ensemble de árvores de decisão
- **Gradient Boosting**: Boosting sequencial para classificação
- **SVM**: Support Vector Machine com kernel RBF

## 🎥 Video Apresentação
https://youtu.be/Yl8-UBK6ja0

ele tem que estar no readme. se der pra colocar ele com player otimo

## 📊 Features Utilizadas
- Gênero
- Idade
- Histórico familiar
- Frequência de consumo de alimentos calóricos
- Frequência de consumo de vegetais
- Número de refeições
- Consumo de lanches entre refeições
- Tabagismo
- Consumo de água (CH2O)
- Monitoramento de calorias
- Frequência de atividade física
- Tempo diário de uso de dispositivos eletrônicos
- Consumo de álcool
- Tipo de transporte

## 🚀 Como Executar

### Pré-requisitos
```bash
python >= 3.8
```

### Instalação
```bash
cd "MACHINE LEARNING"
pip install -r requirements.txt
```

### Executar Streamlit
```bash
cd STREAMLIT
streamlit run streamlit_app.py
```

## 📈 Funcionalidades da Aplicação
- Upload de datasets personalizados
- Visualização dos dados
- Treinamento de múltiplos modelos
- Comparação de performance
- Matrizes de confusão
- Relatórios de classificação

## 🛠️ Tecnologias
- **Python**: Linguagem principal
- **Streamlit**: Interface web
- **Scikit-learn**: Modelos de ML
- **Pandas**: Manipulação de dados
- **Matplotlib/Seaborn**: Visualizações
- **Power BI**: Dashboard analítico

## 📋 Dependências
```
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=1.0.0
streamlit
```
