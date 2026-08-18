# Consistência de Índices de Vegetação sob Diferentes Altitudes de Voo (VANT)

Rotinas de análise estatística da consistência pixel a pixel dos índices NDVI, RDVI e OSAVI obtidos por VANT multiespectral em três altitudes de voo (40, 80 e 120 m) em talhões comerciais de cana-de-açúcar.

## Funcionalidades
- Estatísticas descritivas por talhão/altitude/índice (média, CV, percentis)
- Métricas de concordância entre pares de altitudes (R², RMSE, MAE, viés)
- ANOVA e teste de Tukey HSD para efeitos de altitude e talhão
- Heatmaps, boxplots e mapas de diferença espacial

## Stack
`Python` · `pandas` · `numpy` · `seaborn` · `matplotlib` · Google Colab

## Contexto
Pipeline vinculado a manuscrito científico submetido sobre o efeito da altitude de voo na consistência espacial de índices de vegetação em cana-de-açúcar.
