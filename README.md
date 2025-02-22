# 📊 Análise Exploratória de Dados (EDA) - Vendas e Lucro  

## 📌 Objetivo  
Realizar uma **Análise Exploratória de Dados (EDA)** sobre um conjunto de dados de vendas, identificando padrões, tendências e insights relevantes para o negócio.  

## 🛠️ **Etapas da Análise**  

### 1️⃣ **Tratamento e Preparação dos Dados**  
- Remoção de valores nulos e inconsistências.  
- Conversão de tipos de dados (exemplo: datas).  
- Criação de novas variáveis relevantes para a análise (exemplo: tempo de entrega).  

### 2️⃣ **Análise Exploratória e Estatísticas Descritivas**  
- Identificação de distribuições dos dados.  
- Cálculo de métricas como média, mediana e desvio padrão.  
- Agrupamentos para entender padrões de vendas e lucros.  

### 3️⃣ **Visualizações Informativas**  
Utilizamos **Matplotlib e Seaborn** para gerar gráficos como:  
- Histograma da distribuição de vendas e lucro.  
- Gráfico de dispersão entre desconto e lucro.  
- Evolução do faturamento ao longo do tempo.  
- Comparação de lucro entre diferentes regiões.  

## 🔍 **Principais Insights Obtidos**  

1️⃣ **Impacto do Desconto no Lucro**  
   - Conforme os descontos aumentam (de 0% até cerca de 30%), o lucro tende a reduzir.  
   - Há diversas ocorrências de lucros negativos em descontos altos, sugerindo que grandes descontos podem gerar prejuízos.  

2️⃣ **Dias da Semana com Menor e Maior Volume de Vendas**  
   - **Terça, quarta e quinta-feira** são os dias com menos vendas.  
   - **Segunda e sexta-feira** são os dias mais movimentados em termos de vendas.  

3️⃣ **Crescimento Exponencial do Negócio**  
   - O faturamento e o volume de pedidos aumentaram de forma acelerada ao longo dos anos, indicando um crescimento exponencial.  

4️⃣ **Regiões com Diferentes Margens de Lucro**  
   - A **região central** apresenta uma margem de lucro média negativa de **-10.41%**, o que sugere possíveis problemas operacionais ou estratégia de preços inadequada.  

5️⃣ **Análise de Faturamento por Região**  
   - As regiões **Central** e **South** são as que menos faturam.  
   - A região **West** é a que mais fatura, perdendo apenas para **East** no ano de 2015.  

6️⃣ **Principais Categorias que Geram Lucro**  
   - A maior parte do lucro da empresa vem das categorias **Material de Escritório** e **Tecnologia**.  

## 📌 **Próximos Passos**  
- Explorar mais a relação entre descontos e fidelização de clientes.  
- Analisar sazonalidade nas vendas (por mês e trimestre).  
- Avaliar o impacto da entrega no tempo no lucro por região.  

## 🛠️ **Tecnologias Utilizadas**  
- **Pandas** para manipulação de dados.  
- **Matplotlib e Seaborn** para visualização.  
- **NumPy e Scipy** para estatísticas descritivas.  

--- 

# Integração com IA Generativa para Análise de Modelos

## 📌 Objetivo
Este projeto usa um modelo Gradient Boosting para prever lucros e integra um **LLM** (GPT-4) para gerar insights automáticos.

## 📊 Metodologia
1. **Treinamento do modelo** → Gradient Boosting com ajuste de hiperparâmetros.
2. **Cálculo de métricas** → MAE, MSE, RMSE e R².
3. **Integração com IA** → Envio dos dados para um modelo GPT-4 via API OpenAI.
4. **Geração de insights** → Análise dos resultados e recomendações.

## 🏆 Resultados Obtidos
- **R²: 0.86** → O modelo captura bem os padrões de lucro.
- **Insight gerado pela IA:**  
  "Seu modelo está performando bem. Para melhorias, tente engenharia de features ou otimização via GridSearchCV."

## 🚀 Próximos Passos
- Testar novos modelos (XGBoost, Random Forest)
- Refinar hiperparâmetros com GridSearchCV
- Adicionar mais features relevantes
