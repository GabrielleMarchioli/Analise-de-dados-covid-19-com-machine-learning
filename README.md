# Projeto de Análise de Dados - COVID-19

Este projeto tem como objetivo realizar uma análise de dados relacionados à pandemia de COVID-19. Utilizando a linguagem de programação Python e bibliotecas populares como Pandas, Plotly, e Statsmodels, foram explorados e visualizados diversos aspectos dos dados para entender melhor a evolução da doença.

## Conteúdo do Projeto

1. **Carregamento dos Dados:**
   - Utilização da biblioteca Pandas para carregar os dados de um arquivo CSV hospedado no GitHub.

2. **Análise Exploratória de Dados (EDA):**
   - Visualização das primeiras linhas do DataFrame.
   - Informações sobre o DataFrame (tipos de dados, contagem de valores não nulos, etc.).
   - Estatísticas descritivas sobre as colunas numéricas.
   - Alteração de nomes de colunas para facilitar referências futuras.
   - Filtro e criação de um subconjunto de dados específico para o Brasil.

3. **Visualizações Gráficas:**
   - Gráfico de linha mostrando a evolução dos casos confirmados no Brasil ao longo do tempo.
   - Gráfico de linha exibindo o número de novos casos por dia.
   - Gráfico de linha representando o número de mortes diárias.

4. **Taxa Média de Crescimento:**
   - Cálculo da taxa média de crescimento dos casos confirmados de COVID-19 no Brasil.

5. **Séries Temporais:**
   - Decomposição das séries temporais dos novos casos confirmados e casos confirmados totais para entender tendências, sazonalidades e resíduos.
   - Utilização de modelos AUTO-ARIMA para prever futuros casos confirmados.

6. **Forecasting com Prophet:**
   - Aplicação do modelo Prophet para prever casos confirmados no futuro.
   - Visualização da previsão em comparação com os dados observados.

8. **Conclusão:**
   - Este projeto proporcionou uma visão abrangente da evolução da pandemia de COVID-19 no Brasil, utilizando análise de dados e técnicas de visualização. Ao explorar os conjuntos de dados e aplicar modelos estatísticos, conseguimos extrair informações valiosas sobre a propagação da doença.

## Como Executar o Código

1. Clone o repositório.
2. Instale as dependências: `pip install -r requirements.txt`.
3. Execute o código em um ambiente Python compatível.


