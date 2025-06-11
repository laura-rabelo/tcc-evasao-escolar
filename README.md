# Predição da Evasão Escolar com Machine Learning

Este repositório apresenta o projeto de TCC da estudante **Laura Rabelo de Carvalho Ferreira**, desenvolvido no IFSP - Campus Campinas, com foco na caracterização e predição da evasão escolar no Brasil utilizando técnicas estatísticas e modelos de aprendizado de máquina.

---

## Objetivo

Desenvolver modelos preditivos de Inteligência Artificial para estimar a taxa de abandono escolar, com base em fatores socioeconômicos, regionais e institucionais, abrangendo dados de 2013 a 2023.

---

## Técnicas Utilizadas

- Análise Estatística: Descritiva, Inferencial e Séries Temporais
- Machine Learning:
  - Random Forest (melhor modelo: MAE = 0.69 | R² = 0.86)
  - Gradient Boosting
  - Regressão Linear
  - K-Nearest Neighbors (KNN)
  - Support Vector Machines (SVM)
  - Redes Neurais Artificiais (ANN/MLP)
  - XGBoost
- Visualização de Dados: Matplotlib, Seaborn
- Plataforma: Google Colab

---

## Estrutura do Repositório

```
evasao-escolar-ml/
├── Trabalho_Final.ipynb         # Notebook com todo o processo do TCC
├── TCC EXEL.csv                 # Base de dados consolidada (INEP 2013–2023)
└── README.md                    # Este arquivo
```




---

## Principais Resultados

- A evasão escolar é mais acentuada no Ensino Médio da rede pública (6,82%)
- Fatores como renda média e tipo de escola influenciam fortemente a evasão
- Modelos baseados em árvores (Random Forest, Gradient Boosting) obtiveram melhor desempenho
- Tendência de crescimento na evasão até 2028, especialmente em contextos públicos

---

## Métricas Avaliadas

- MAE (Erro Médio Absoluto)
- RMSE (Raiz do Erro Quadrático Médio)
- R² (Coeficiente de Determinação)
- Acurácia, Precisão, Recall, F1-score
- Matriz de Confusão (em classificações)

---

## Como Executar

1. Abra o `Trabalho_Final.ipynb` no Google Colab
2. Faça upload da base `TCC EXEL.csv`
3. Execute célula por célula para:
   - Ver a análise estatística
   - Treinar os modelos
   - Visualizar os gráficos e previsões

---

## Autora

**Laura Rabelo de Carvalho Ferreira**  
IFSP - Campus Campinas  
laurarabelocferreira@gmail.com  
24 anos | Interesse em dados, educação e análise estatística

---

## Referências

- Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (INEP)
- ARAÚJO et al. (2025), SANTOS (2020), BAGGI e LOPES (2011)
- Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

---

## Licença

Projeto acadêmico - uso livre para fins educacionais e de pesquisa.
