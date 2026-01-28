# Análise de Churn de Clientes

## 📌 Contexto
Este projeto tem como objetivo analisar a incidência de churn de clientes em uma plataforma SaaS, identificando padrões e fatores associados à evasão, com foco em comportamento de uso, características contratuais e perfil das empresas.

O churn é definido como a não renovação do contrato após atraso no pagamento.

---

## 🎯 Objetivo
Identificar os principais fatores associados ao churn de clientes e propor ações práticas que possam auxiliar a empresa a reduzir a evasão, especialmente nos estágios iniciais do relacionamento com o cliente.

---

## 🗂️ Dados
A análise foi realizada a partir de dados internos da empresa, incluindo:
- Dados cadastrais dos clientes
- Informações contratuais
- Dados de uso da plataforma (frequência e engajamento)

> Observação: Os dados utilizados foram anonimizados e utilizados exclusivamente para fins educacionais.

---

## 🔍 Metodologia
O projeto seguiu as seguintes etapas:
1. Entendimento do problema de negócio
2. Análise exploratória dos dados (EDA)
3. Identificação de padrões associados ao churn
4. Formulação de hipóteses
5. Proposição de recomendações práticas orientadas a negócio
6. Sugestão de evolução com modelos de Machine Learning

---

## 📊 Principais Insights
- O churn está fortemente concentrado nos primeiros períodos de contrato.
- Clientes com baixo engajamento apresentam maior risco de evasão.
- Empresas de menor porte tendem a churnar mais do que empresas maiores.
- Contratos mensais apresentam taxas de churn significativamente maiores do que contratos de maior duração.

---

## 🎯 Recomendações
Com base nos achados, foram sugeridas ações como:
- Redução de fricções no processo de adoção da plataforma
- Investimento em onboarding e conteúdo educativo
- Estratégias para incentivo à contratação de planos anuais
- Uso de modelos de Machine Learning para segmentação e priorização de clientes com maior risco de churn

---

## 📁 Estrutura do Repositório
- `churn_analysis.ipynb`: notebook principal com toda a análise (EDA, insights e recomendações)
- `customer_churn_with_months.csv`: base de dados utilizada na análise
- `requirements.txt`: dependências do projeto
- `README.md`: descrição do projeto e principais conclusões
- `LICENSE`: licença do repositório
- `.gitignore`: arquivos e pastas ignorados pelo Git

---

## 🚀 Próximos Passos
- Desenvolvimento de modelos preditivos de churn
- Monitoramento do impacto das ações sugeridas