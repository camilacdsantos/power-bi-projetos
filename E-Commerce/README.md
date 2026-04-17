# 📊 Análise de Performance E-Commerce | Olist Brasil

## 📌 Sobre o projeto

Este projeto tem como objetivo analisar o desempenho de um e-commerce utilizando o dataset público da Olist, explorando métricas de vendas, eficiência logística, comportamento de clientes e satisfação.

O dashboard foi desenvolvido no Power BI com foco em gerar insights acionáveis para tomada de decisão, estruturado em múltiplas visões analíticas.

---

## 🎯 Objetivos da análise

* Avaliar a performance de vendas e receita
* Analisar eficiência logística (tempo de entrega e atrasos)
* Entender o comportamento dos clientes
* Explorar padrões de pagamento
* Medir o nível de satisfação dos clientes

---

## 📈 Principais KPIs

* Receita Total
* Total de Pedidos
* Ticket Médio
* Tempo Médio de Entrega
* % de Pedidos em Atraso
* Nota Média de Avaliação

---

## 🧱 Modelagem de Dados

O modelo foi estruturado em formato **Star Schema**, garantindo consistência e performance nas análises:

* **Fato principal:** pedidos
* **Fato secundária:** itens de pedido (receita)
* **Dimensões:** clientes, produtos
* **Tabelas auxiliares:** pagamentos e avaliações

---

## 📊 Estrutura do Dashboard

### 🔹 Visão Executiva

Visão consolidada com os principais indicadores de performance e tendências de receita.

### 🔹 Vendas & Receita

Análise detalhada de faturamento por categoria, forma de pagamento e evolução ao longo do tempo.

### 🔹 Logística

Avaliação de tempo de entrega, atrasos e desempenho por região e categoria.

### 🔹 Clientes & Satisfação

Análise de comportamento do cliente e distribuição de avaliações.

---

## 🔍 Principais Insights

* A receita está concentrada em poucas categorias de produtos
* Atrasos logísticos variam significativamente por região
* Categorias com maior atraso tendem a apresentar menor avaliação média
* O frete impacta significativamente o valor total em determinadas categorias

---

## 🛠️ Tecnologias Utilizadas

* Power BI
* Power Query (ETL e transformação de dados)
* DAX (criação de métricas e KPIs)
* Modelagem dimensional (Star Schema)

---

## 📂 Arquivos do Projeto

* `dashboard.pbix` → arquivo do Power BI
* `dashboard.pdf` → versão estática para visualização
* `/images` → capturas do dashboard

---

## 📸 Preview do Dashboard

*(Adicione aqui imagens das páginas do dashboard)*

---

## 🚀 Sobre o Projeto

Este projeto foi desenvolvido com foco em boas práticas de BI, incluindo modelagem adequada, separação de granularidade e construção de métricas confiáveis para análise de negócio.

---
