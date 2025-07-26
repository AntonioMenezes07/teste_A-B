# Testes A/B com Python

Este projeto apresenta a resolução de **cinco exercícios de Teste A/B** aplicados em contextos reais de negócios, utilizando **Python** e testes estatísticos para avaliar hipóteses. Os testes são aplicados para tomada de decisão baseada em dados.

---

## 🔍 Objetivo

Demonstrar, por meio de exemplos práticos, como realizar **Testes A/B** para comparar proporções e médias entre dois grupos, avaliando a significância estatística de alterações em produtos, preços e campanhas.

---

## 📂 Estrutura

O projeto contém 5 exercícios resolvidos com código Python e explicações estatísticas.

### ✔️ Exercício 1 — Teste A/B para Avaliação de Design de Site
> Uma empresa de e-commerce deseja saber se um novo design de sua página de produto aumenta a taxa de cliques (CTR).  
> 🔹 Visitantes com design antigo: 1.000 → 150 cliques  
> 🔹 Visitantes com novo design: 1.000 → 180 cliques

**Hipótese:** O novo design aumenta a CTR?  

---

### 💰 Exercício 2 — Teste A/B para Preços
> Uma empresa SaaS quer avaliar o impacto de um aumento no preço da assinatura mensal de R$20 para R$25.  
> 🔹 Preço antigo: 500 visitantes → 200 conversões  
> 🔹 Preço novo: 500 visitantes → 180 conversões

**Hipótese:** O novo preço traz mais receita, mesmo com menor taxa de conversão?  

---

### ✉️ Exercício 3 — Teste A/B para Email Marketing
> Uma empresa de varejo testou duas versões de um e-mail promocional.  
> 🔹 Versão A: 2.000 envios → 20% abertura  
> 🔹 Versão B: 2.500 envios → 22% abertura

**Hipótese:** A versão B teve um desempenho significativamente melhor?  

---

### 🕒 Exercício 4 — Teste A/B para Tempo no Site
> Uma plataforma de notícias quer saber se uma funcionalidade de sugestões de artigos aumenta o tempo médio no site.  
> 🔹 Com sugestão: 1.500 usuários → média 5,2 min (dp = 1,5)  
> 🔹 Sem sugestão: 1.700 usuários → média 5,0 min (dp = 1,4)

**Hipótese:** O novo recurso aumenta significativamente o tempo médio?  

---

### 👋 Exercício 5 — Teste A/B para Taxa de Rejeição
> Uma empresa de software quer saber se um tutorial introdutório reduz o abandono no primeiro uso.  
> 🔹 Com tutorial: 1.200 usuários → 400 abandonos  
> 🔹 Sem tutorial: 1.100 usuários → 500 abandonos

**Hipótese:** O tutorial reduz significativamente a taxa de rejeição?  

---

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Bibliotecas:
  - `scipy.stats`
  - `statsmodels`
  - `numpy`
  - `matplotlib` (opcional, para gráficos)

---

## 📊 Resultados

Cada exercício apresenta:
- Formulação das hipóteses nula e alternativa
- Cálculo do p-valor
- Conclusão estatística com base no nível de significância (geralmente 5%)
