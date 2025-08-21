# Análise de Dados Eleitorais - Votação para Vereador (2016-2024)

## 📖 Visão Geral do Projeto

Este projeto realiza uma análise detalhada da evolução dos votos de um candidato específico ao cargo de vereador ao longo de três eleições consecutivas: 2016, 2020 e 2024. O objetivo é transformar dados brutos de votação em visualizações claras que permitam entender tanto o desempenho geral quanto a distribuição geográfica dos votos por bairro.

O script utiliza Python e bibliotecas populares de Data Science para processar, agregar e visualizar os dados.

---

## ✨ Funcionalidades

O projeto é dividido nas seguintes etapas:

1.  **Carga de Dados**: Leitura dos dados de votação de arquivos Excel (`.xlsx`) para cada ano eleitoral.
2.  **Análise de Desempenho Geral**:
    * Cálculo do total de votos recebidos pelo candidato em cada uma das três eleições.
    * Geração de gráficos de área e de barras para visualizar a tendência de votação ao longo do tempo.
3.  **Análise Geográfica por Bairro**:
    * Limpeza e preparação de um arquivo auxiliar para mapear os locais de votação aos seus respectivos bairros.
    * Cruzamento dos dados de votação com os dados geográficos.
    * Cálculo do total de votos por bairro para cada ano.
    * Geração de gráficos de barras horizontais, mostrando os bairros com maior concentração de votos em 2016, 2020 e 2024.
4.  **Análise Comparativa**:
    * Consolidação dos resultados anuais em um único DataFrame.
    * Criação de um gráfico de barras agrupado que compara o desempenho do candidato nos diferentes bairros ao longo das três eleições.

---

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **Pandas**: Para manipulação e análise dos DataFrames.
* **Matplotlib**: Para a criação dos gráficos estáticos (barras e área).
* **Seaborn**: Para a criação de visualizações estatísticas mais elaboradas e com melhor estética.
* **Openpyxl**: Como motor para o Pandas ler os arquivos `.xlsx`.
