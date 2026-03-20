# 📊 Customer Intelligence: Segmentação RFM e Cohort

## 📝 Sobre o Projeto
Este projeto utiliza dados transacionais de uma operação de varejo para extrair inteligência sobre o comportamento dos clientes. O objetivo principal é segmentar a base de consumidores para otimizar investimentos de marketing e entender a retenção de longo prazo (LTV).

A análise foi construída inteiramente no **Excel**, utilizando **Power Query** para a modelagem de dados e fórmulas avançadas para a lógica de segmentação.

---

## 🛠️ Tecnologias e Metodologias
* **Excel (Power Query):** ETL e tratamento de dados brutos provenientes de múltiplas tabelas.
* **Segmentação RFM:** Técnica baseada em Recência (R), Frequência (F) e Valor Monetário (M).
* **Análise de Cohort:** Estudo longitudinal de retenção mensal por safra de aquisição.
* **Estatística Descritiva:** Cálculo de métricas centrais e classificação por quartis.

---

## 📈 Principais Insights

### 1. Segmentação RFM
A base foi dividida em 11 segmentos estratégicos. Os destaques encontrados nos dados incluem:
* **Campeões:** Grupo de elite com um **ticket médio de R$ 7.210,18** e recência baixíssima (média de 29 dias). *Ação: Programa de fidelidade exclusivo.*
* **Clientes Fiéis:** Apresentam alta frequência (média de 8 compras), consolidando a base de receita.
* **Potencial / Promissor:** Clientes com boa frequência, mas que respondem melhor a ofertas de ticket mais baixo para aumentar o LTV.
* **Em Risco / Quase Dormentes:** Segmentos que não compram há meses, exigindo réguas de reativação imediatas.

### 2. Retenção (Cohort)
* **Taxa de Retenção Crítica:** A análise de Cohort revelou que a retenção média após 12 meses estabiliza em **7,7%**.
* **Janela de Engajamento:** Identificou-se que os primeiros 3 meses são cruciais; safras que recebem acompanhamento inicial tendem a apresentar maior sobrevida na base.

---

## 📂 Estrutura do Repositório
* `Analise_Segmentacao_RFM.xlsx`: Arquivo principal com Power Query, Cálculos e Dashboards.
* `/data`: Contém os CSVs originais (Customers, Orders, Location, Product).
* `/screenshots`: Imagens dos Dashboards e tabelas de Cohort.

---

## 💡 Aplicação de Negócio
1.  **Marketing Direto:** Segmentação de campanhas de e-mail e tráfego pago com base nas notas de RFM.
2.  **Customer Success:** Identificação precoce de Churn através da análise de Cohort.

---

## 👤 Autor
**Renato** – Analista de Dados
* [LinkedIn](https://www.linkedin.com/in/renato-junior-data-analyst/)
