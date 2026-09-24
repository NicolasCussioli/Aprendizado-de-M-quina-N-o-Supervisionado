# Atividade 1 — Segmentação de clientes

Notebook da atividade de aprendizado não supervisionado. Usei a base [Online Retail da UCI](https://archive.ics.uci.edu/dataset/352/online+retail) para agrupar clientes pelo tempo desde a última compra, número de compras e valor gasto (RFM).

## Como rodar

1. Abra [`Atividade1_Segmentacao_Clientes_COLAB.ipynb`](Atividade1_Segmentacao_Clientes_COLAB.ipynb) no Google Colab.
2. Clique em **Ambiente de execução → Executar tudo**.

O próprio notebook instala as bibliotecas e baixa a base. Não é preciso enviar o arquivo de dados. A leitura do Excel pode levar alguns minutos na primeira execução.

## O que está no notebook

- Limpeza dos dados e cálculo de RFM por cliente.
- Comparação de K-Means, agrupamento hierárquico e DBSCAN.
- Métricas de avaliação e gráficos dos grupos, incluindo PCA e um painel interativo.
- Um resumo dos resultados no final.

**Fonte dos dados:** Chen, D. (2015). *Online Retail*. UCI Machine Learning Repository. [DOI: 10.24432/C5BW33](https://doi.org/10.24432/C5BW33). Os valores monetários estão em libras esterlinas (£).
