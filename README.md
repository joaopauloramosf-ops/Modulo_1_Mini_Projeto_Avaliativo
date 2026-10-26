# Trabalho_26.10

# Análise de Dados de Varejo (Python & Pandas)

Este repositório contém o desenvolvimento de um projeto prático de análise de dados aplicado ao setor varejista, dividindo-se em sprints focadas em limpeza, transformação, estatística descritiva, agrupamentos e visualização de tendências temporais.

## 🚀 Etapas do Projeto (Sprints)
- **Sprint 1:** Importação e inspeção inicial da base de dados (`pandas`).
- **Sprint 2:** Limpeza e tratamento de strings (`.str`), datas (`datetime`) e tipagem com remoção de inconsistências (`#N/D`).
- **Sprint 4:** Estatística descritiva focada na coluna de número de filhos (`CL_FHL`).
- **Agrupamentos:** Análise cruzada por gênero, categorias de produtos e segmentação comportamental por faixa de filhos (comparações de volume e médias).
- **Visualização e Sazonalidade:** Gráficos de tendência temporal dos top 5 produtos de cada categoria utilizando `Seaborn` e `Matplotlib`.

## 📈 Principais Insights e Tendências Anuais
Com base na análise gráfica dos produtos ao longo do tempo, foi possível identificar um **padrão sazonal marcante** no comportamento de consumo:
1. **Dinâmica Sazonal:** Observa-se uma clara oscilação no volume de compras ao longo do ano, com um pico de alta no final do inverno, seguido de uma retração temporária, um **forte disparo nas vendas no início do verão** (atingindo os patamares máximos entre abril e junho) e uma posterior desaceleração progressiva até a chegada do inverno rigoroso.
2. **Consistência entre Categorias:** O comportamento sazonal se repete de forma transversal entre as diferentes categorias de produtos (como Bebidas, Alimentos e Higiene), indicando que fatores macroambientais ou sazonais influenciam fortemente o poder de compra e o fluxo do varejo analisado.
3. **Qualidade dos Dados:** Identificou-se a necessidade de tratamento rigoroso de registros corrompidos na base (como a categoria `#N/D`), garantindo a integridade dos agrupamentos e métricas apresentadas.

## 🛠️ Tecnologias Utilizadas
- Pandas / NumPy
- Matplotlib / Seaborn
- Python - Google Colab / GitHub


