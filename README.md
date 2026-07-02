# Análise de Dados do Airbnb - Rio de Janeiro 🏠📊

Este projeto realiza o carregamento, a unificação (merge), a limpeza e o tratamento de dados de aluguéis por temporada na cidade do Rio de Janeiro, utilizando dados do Airbnb. O objetivo principal é estruturar os dados para análises futuras e identificar distribuições e potenciais *outliers* de preços.

## 📋 Estrutura do Projeto

O projeto utiliza dois conjuntos de dados principais:
* **`listings_cleaned.csv`**: Contém informações detalhadas sobre as acomodações (bairro, tipo de quarto, número de hóspedes, banheiros, quartos, camas e preço).
* **`reviews.csv`**: Contém métricas de avaliações das acomodações (número de avaliações e a nota média de pontuação).

## 🚀 Etapas Executadas no Notebook

1. **Importação das Bibliotecas**: Utilização do `pandas` para manipulação de dados, `numpy` para suporte matemático e `matplotlib` para visualizações gráficas.
2. **Carregamento de Dados**: Leitura dos arquivos CSV e inspeção inicial das primeiras linhas.
3. **Unificação dos Dados (Merge)**: Junção das tabelas de acomodações e avaliações através da coluna identificadora única `id`.
4. **Limpeza e Tratamento**: 
   * Verificação e confirmação de ausência de valores nulos (`NaN`).
   * Verificação e confirmação de ausência de linhas duplicadas.
5. **Análise de Outliers**: Plotagem de gráfico estatístico do tipo **Boxplot** para avaliar a dispersão e a presença de valores discrepantes na coluna de preços (`price`).

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook / Google Colab**
