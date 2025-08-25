# Relatorio-de-Vendas-Global

Este projeto foi desenvolvido para atender a uma demanda da gerência: **ter um resumo executivo claro e rápido dos últimos números de vendas**.  
O relatório responde a três perguntas-chave de negócio:

1️⃣ **Qual mês e ano tiveram mais lucro?**  
2️⃣ **Onde a empresa está tendo mais sucesso (por país/região)?**  
3️⃣ **Em qual produto e segmento a empresa deve continuar investindo?**

## 🚀 Visão Geral do Projeto

- **Ferramenta**: Microsoft Power BI  
- **Período analisado**: 2013–2014  
- **Fonte de dados**: *Financials* (dataset de exemplo do Power BI)  
- **Objetivo**: Fornecer insights rápidos para apoiar a tomada de decisão estratégica da gerência.  

O dashboard foi construído trazendo **KPIs**, mapas e comparações de produtos/segmentos.

---
## 🧮 Medidas DAX Utilizadas

```DAX

Total Units Sold = SUM(financials[Units Sold])

```
```
Calendar = CALENDAR(DATE(2013,01,01), DATE(2014,12,31))

```

## Resultado Final

<img width="1146" height="636" alt="image" src="https://github.com/user-attachments/assets/cd96df49-93b9-4007-befe-02807fb2b64b" />

1️⃣ Qual mês e ano tiveram mais lucro? : **Dezembro de 2014** 

2️⃣ Onde a empresa está tendo mais sucesso (por país/região)?: **Na Europa, especificamente, na França e na Alemanha**  

3️⃣ Em qual produto e segmento a empresa deve continuar investindo?: **A empresa deve continuar investindo no produto Paseo e ter como alvo os segmentos Pequenas Empresas e Governo**
