# Projeto 2 — Regressão Logística Univariada

Modelos de regressão logística treinados com uma característica por vez, avaliação via curva ROC e AUC. Melhor AUC obtido: 0.618 (contra 0.316 de um modelo aleatório).

**Livro:** *Projetos de Ciência de Dados com Python* — Stephen Klosterman (Novatec Editora, 2020)

## Conteúdo

- `projeto.ipynb` — notebook completo, já executado (com todas as saídas e gráficos)
- `Data/` — datasets usados (UCI Credit Card: 5.333 registros, 23 variáveis)

## Como executar

```bash
pip install pandas scikit-learn numpy matplotlib seaborn xlrd
jupyter notebook projeto.ipynb
```

Para as visualizações de árvores (Projeto 5), instale o binário Graphviz (`dot`).
