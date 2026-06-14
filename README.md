# Trabalho Final — EAE1106 Métodos Empíricos

## Descrição
Análise empírica da relação entre gasto público em educação e desemprego
utilizando dados do Banco Mundial (2015–2021) para 217 países.

## Dados
Fonte: [World Bank Open Data](https://data.worldbank.org/)

Indicadores utilizados:
- GDP per capita (NY.GDP.PCAP.KD)
- GDP (NY.GDP.MKTP.KD)
- Gasto com educação % PIB (SE.XPD.TOTL.GD.ZS)
- Gasto com educação % gasto do governo (SE.XPD.TOTL.GB.ZS)
- Gasto por aluno ensino médio % PIB per capita (SE.XPD.SECO.PC.ZS)
- Desemprego total (SL.UEM.TOTL.ZS)
- Desemprego com educação básica (SL.UEM.BASC.ZS)
- Desemprego com educação intermediária (SL.UEM.INTM.ZS)
- Desemprego com educação avançada (SL.UEM.ADVN.ZS)

## Estrutura

    EAE1106/
    ├── dados/
    │   ├── original/      # dataset bruto do Banco Mundial
    │   └── secundario/    # datasets gerados pela limpeza
    ├── resultados/        # gráficos e tabelas
    └── Trabalho_Final_EAE1106.ipynb
## Requisitos
```
pandas
numpy
matplotlib
seaborn
statsmodels
scipy
pathlib
```

## Autors
Ana Sofia Paiossin Quelhas, 16853892
Ana Paula Maia Monteiro, 15439696
Marcos Konishi Maruyama, 16818206
Sérgio Barbaresco Figaro, 12538990
