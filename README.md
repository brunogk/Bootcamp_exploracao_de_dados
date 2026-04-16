# Bootcamp_exploracao_de_dados
# 📊 Análise de Dados – Performance de Plataforma e Teste A/B

## 📌 Objetivo
Este projeto tem como objetivo analisar o comportamento de usuários em diferentes plataformas e avaliar estratégias de negócio por meio de um teste A/B, além de investigar relações entre variáveis e prever receita.

## 🔍 Perguntas de Negócio
- Qual plataforma apresenta melhor desempenho?
- O grupo B é superior ao grupo A?
- Existe relação entre comportamento do usuário e receita?
- É possível prever receita com modelos de regressão?

## 🧠 Metodologia

### 1. Exploração de Dados (EDA)
- Identificação de variáveis categóricas e numéricas
- Análise de distribuição (plataforma, grupos)
- Criação de faixas de receita (quartis)

### 2. Análise de Relações
- Tabelas de contingência
- Análise de dispersão:
  - interações vs conversões
  - conversões vs receita
- Correlação entre variáveis

### 3. Teste A/B
- Comparação entre Grupo A e Grupo B
- Métricas:
  - média de conversões
  - média de receita

### 4. Modelagem
- Regressão Linear:
  - Receita ~ Conversões
  - Receita ~ Conversões + Interações
- Avaliação com R² e MSE

## 📈 Principais Insights
- A plataforma **app** apresentou maior performance
- O **Grupo B** superou o Grupo A em conversões e receita
- Forte correlação entre **conversões e receita**
- Conversões são o principal driver de valor

## 💡 Recomendações
- Priorizar investimentos na plataforma app
- Expandir a estratégia do Grupo B
- Focar na otimização da taxa de conversão
- Utilizar modelos preditivos para suporte à decisão

## 🛠️ Tecnologias Utilizadas
- Python (Pandas, NumPy)
- Matplotlib / Seaborn
- Scikit-learn

## 📊 Conclusão
O projeto demonstra como técnicas de análise de dados podem ser aplicadas para gerar insights estratégicos e apoiar decisões de negócio baseadas em evidências.
