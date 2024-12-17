
# Previsão de Preços de Carros Usados  

Este projeto utiliza **modelos de regressão** para prever o preço de carros usados com base em um conjunto de dados detalhado. A análise inclui o uso de diferentes modelos de machine learning para identificar os fatores mais importantes que influenciam os preços de veículos no mercado.  


## Business Understanding  

Uma empresa automobilística pretende expandir suas operações para o mercado dos Estados Unidos, estabelecendo uma unidade de fabricação local e produzindo veículos diretamente no país. O objetivo estratégico é competir com as montadoras americanas e europeias no mercado automotivo dos EUA.  

Para isso, ela contratou uma empresa de consultoria especializada no setor automotivo para analisar os fatores que influenciam os preços dos automóveis no mercado americano. Essa análise é crucial, uma vez que os determinantes de preço no mercado dos EUA podem diferir significativamente daqueles do mercado em que a empresa atualmente opera.  

A empresa deseja compreender:  

- **Quais variáveis são determinantes para a previsão do preço de um automóvel.**  
- **A relevância e impacto dessas variáveis na precificação.**  

Com base em extensivas pesquisas de mercado, a consultoria compilou um robusto conjunto de dados que abrange diversos modelos de carros disponíveis no mercado americano.  


### Objetivo  

Fornecer à empresa automobilística uma análise baseada em dados que identifique as principais variáveis que influenciam o preço dos carros no mercado. Essa análise servirá para:  

1. **Apoiar a tomada de decisões estratégicas** sobre a entrada no mercado.  
2. **Definir características competitivas dos produtos** que atendam às expectativas do público-alvo local.  
3. **Estabelecer estratégias de precificação** adequadas.  
4. **Posicionar a marca de forma competitiva** no mercado automotivo em que a empresa deseja operar.  

O objetivo final é garantir que a referida empresa tome decisões informadas e maximize suas chances de sucesso no mercado.  

---

## Conteúdo do Projeto  

1. **Conjunto de Dados**:  
   - Fonte: `CarPrice_Assignment.csv` (dados de características de carros e seus respectivos preços).  
   - Total de registros: **205 linhas**  
   - Total de variáveis: **26 colunas** incluindo `car_ID`, `CarName`, `enginesize`, `horsepower`, e `price`.  

2. **Modelos Utilizados**:  
   - Regressão Linear  
   - Decision Tree Regressor  
   - Random Forest Regressor  
   - AdaBoost Regressor  
   - Gradient Boosting Regressor  

3. **Métricas de Avaliação**:   
   - **R² Score**: Métrica de explicação da variabilidade dos dados.  

4. **Resultados**:  
   - Comparação entre os modelos e suas respectivas performances.  
   - Identificação dos fatores mais relevantes para o preço dos veículos.  


## Estrutura do Repositório  

- **`CarPrice.ipynb`**: Notebook principal contendo o pipeline de análise e modelos de machine learning.  
- **`CarPrice_Assignment.csv`**: Conjunto de dados utilizado para treinar e avaliar os modelos.  
- **`README.md`**: Documentação do projeto (este arquivo).  

## Exemplos de Resultados  

- **Gráficos de Correlação**: Identificação das variáveis mais correlacionadas ao preço.  
- **Visualizações**: Comparação de erros dos modelos em gráficos de barras e scatter plots.  

---

## Próximos Passos  

- Implementar tuning de hiperparâmetros para os modelos.  
- Adicionar novos dados para aprimorar a performance dos modelos.  


