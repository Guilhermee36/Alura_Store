# 🌟 Análise de Eficiência - Alura Store

## 📀 Objetivo

Este projeto foi desenvolvido como parte do **Challenge de Formação em Data Science** da Alura em parceria com a **Oracle Next Education (ONE)**. O objetivo é auxiliar o Sr. João, proprietário da rede Alura Store, a tomar uma decisão estratégica sobre qual de suas 4 lojas vender, com base em uma análise detalhada de dados operacionais e comerciais. A análise inclui:

* Comparativo de faturamento total
* Análise de vendas por categoria
* Média de avaliações dos clientes
* Custo médio de frete por loja
* Destaques de produtos mais e menos vendidos

---

## 🔍 Métricas Analisadas

| Métrica              | Descrição                        | 
| -------------------- | -------------------------------- | 
| Faturamento Total    | Soma de todas as vendas por loja |
| Vendas por Categoria | Comparativo por tipo de produto  |
| Avaliações Médias    | Satisfação geral dos clientes    | 
| Frete Médio          | Custo logístico por loja         |

---

## 📊 Resumo dos Indicadores por Loja

| Loja   | 💰 Faturamento   | ⭐ Avaliação Média | 🚚 Frete Médio | 🍎 Categoria + Vendida | 🌾 Categoria - Vendida |
| ------ | ---------------- | ----------------- | -------------- | ---------------------- | ---------------------- |
| Loja 1 | R\$ 1.534.509,12 | 3.98              | R\$ 34,69      | Móveis (465)           | Utilidades (171)       |
| Loja 2 | R\$ 1.488.459,06 | 4.04              | R\$ 33,62      | Móveis (442)           | Utilidades (181)       |
| Loja 3 | R\$ 1.464.025,03 | 4.05              | R\$ 33,07      | Móveis (499)           | Instrumentos (177)     |
| Loja 4 | R\$ 1.384.497,58 | 4.00              | R\$ 31,28      | Móveis (480)           | Instrumentos (170)     |

---

## 🏢 Análise por Loja

### Loja 1

* 💰 Maior faturamento absoluto
* ❌ Menor avaliação entre as lojas (3.98)
* 🚚 Frete mais caro (R\$ 34,69)
* ✅ Destaque em volume de vendas

### Loja 2

* ⚖️ Equilíbrio entre todos os indicadores
* ⭐ Boa avaliação (4.04)
* 🚚 Frete abaixo da média

### Loja 3

* ⭐ Melhor avaliação (4.05)
* 🚚 Frete eficiente (R\$ 33,07)
* 💼 Melhor performance em categoria móveis

### Loja 4

* 💰 Pior faturamento (R\$ 1.384.497,58)
* 🚚 Melhor frete (R\$ 31,28), mas sem impacto positivo no desempenho
* ❌ Produtos menos vendidos em diversas categorias

---

## 🎖️ Ranking Geral

| Posição | Loja   | Destaque Principal                                      |
| ------- | ------ | ------------------------------------------------------- |
| 🥇 1º   | Loja 3 | Melhor avaliação, boa logística e volume alto em móveis |
| 🥈 2º   | Loja 2 | Equilíbrio entre faturamento, nota e frete              |
| 🥉 3º   | Loja 1 | Maior faturamento, mas fraca em avaliação e frete       |
| ❌ 4º    | Loja 4 | Pior desempenho geral, sem diferencial competitivo      |

---

## ✅ Conclusão e Recomendado

Recomendamos que o Sr. João **venda a Loja 4**.

Apesar de ter o frete mais baixo, ela possui:

* O **menor faturamento** absoluto
* **Produtos com baixo giro** e desempenho fraco em todas as categorias
* Avaliação apenas mediana, sem diferencial competitivo

Essa loja representa a **menor eficiência comercial e operacional** da rede.

---

## 🛠️ Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge\&logo=pandas\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge\&logo=Matplotlib\&logoColor=black)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge\&logo=googlecolab\&color=525252)

---

## 🚀 Como Executar no Colab

1. Acesse o notebook via Google Colab
2. Clique em `Arquivo` > `Salvar uma cópia no Drive`
3. Execute as células na ordem
4. Visualize os gráficos e interprete os resultados conforme o relatório

---

## 👨‍💼 Autor

| Nome     | Guilherme Marques                                 |
| -------- | ------------------------------------------------- |
| Linkedin | [@Guilherme Marques](www.linkedin.com/in/guilhermemarques-dev)      |
| Email    | [gmarques.js@gmail.com](mailto:gmarques.js@email.com)               |
