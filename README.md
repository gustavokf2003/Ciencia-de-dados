# Ciência de Dados

**Repositório da disciplina INE5687-08238 (20251) — Projeto em Ciência de Dados**

---

## Estrutura do Repositório

```
/
├── *.ipynb           # Jupyter Notebooks com as atividades
├── data/             # Dados de treino e teste pré-processados
└── analysis/         # Análise exploratória dos novos conjuntos
```

- Os notebooks estão na raiz do repositório.
- A pasta `data` contém os dados já pré-processados.
- A pasta `analysis` contém análises exploratórias.

---

## Como Utilizar

Você pode rodar apenas a parte de **modelagem e avaliação** utilizando os dados já processados.

> ⚠️ **Atenção:** O processamento dos dados gera DataFrames muito grandes. Recomenda-se utilizar computação em nuvem para processar tudo. 

---

## Ordem Recomendada de Processamento

1. **Geração de dados de não acidentes**
2. **Preencher registros com dados da ANTT**
3. **Preencher registros com dados da OPEN-METEO**
4. **Interpolação de tráfego**
5. **Preencher registros com dados do DNIT**

---
