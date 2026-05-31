# 🚀 FECAF Telecom - Business Intelligence & Governança de Dados

Projeto desenvolvido pela **Ômega Consultoria** para a FECAF Telecom com foco em Governança de Dados, Business Intelligence, FinOps e Monitoramento Operacional.

---

## 📖 Sobre o Projeto

A FECAF Telecom possuía grandes volumes de dados financeiros e operacionais distribuídos entre diferentes fontes.

O desafio da Ômega Consultoria foi transformar esses dados em informações estratégicas através de:

- Limpeza e tratamento dos dados;
- Aplicação de regras de negócio;
- Governança de dados;
- Modelagem analítica no BigQuery;
- Desenvolvimento de dashboards executivos no Looker Studio.

---

## 🏗 Arquitetura da Solução

Dados Brutos
↓
Tratamento e Limpeza
↓
BigQuery
↓
Views Analíticas
↓
Looker Studio
↓
Tomada de Decisão

---

## 🧹 Governança e Qualidade dos Dados

Durante o projeto foram aplicadas diversas regras de negócio:

### Financeiro

- Receita Líquida = Receita Bruta - Descontos
- Validação de descontos aplicados
- Segmentação B2B e B2C
- Consolidação do faturamento por região

### Operacional

- SLA padrão ≤ 24h
- SLA crítico > 24h
- Baixa administrativa > 72h
- Monitoramento de consumo de fibra óptica
- Controle operacional dos chamados

---

# 📊 Dashboard 1 — FinOps & MRR

Painel executivo responsável pelo acompanhamento financeiro da operação.

### Indicadores

✅ Total Faturado

✅ Receita Líquida

✅ Total de Descontos

✅ Evolução Mensal da Receita

✅ Receita por Segmento

✅ Receita por Bairro

✅ Status dos Clientes

### Principais Insights

- Monitoramento da saúde financeira da empresa.
- Análise da evolução da receita ao longo do tempo.
- Identificação dos segmentos mais lucrativos.
- Comparação de desempenho por região.

---

# 🛠 Dashboard 2 — NOC & Field Services

Painel operacional para monitoramento da rede e dos atendimentos.

### Indicadores

✅ Total de Chamados

✅ Fibra Consumida

✅ SLA Crítico (>24h)

✅ Monitoramento de SLA

✅ Produtividade por Cargo

✅ Concentração de Incidentes por Bairro

✅ Top 10 Tipos de Chamado

### Principais Insights

- Controle dos níveis de serviço (SLA).
- Identificação dos bairros com maior volume de incidentes.
- Monitoramento da produtividade operacional.
- Apoio ao planejamento de equipes técnicas.

---

## 🛠 Tecnologias Utilizadas

- Google BigQuery
- SQL
- Looker Studio
- GitHub

---

## 👨‍💼 Consultoria

### Ômega Consultoria

Projeto desenvolvido como solução de Business Intelligence para a FECAF Telecom.

Equipe:

- Fabia Lima
- Icaro Oliveira
- Rhafael Marques
  

---

## 🎓 Projeto Acadêmico

Trabalho desenvolvido para a disciplina de Business Intelligence e Governança de Dados, aplicando conceitos de:

- ETL
- Data Warehouse
- Governança de Dados
- FinOps
- ITIL
- COBIT
- Business Intelligence
