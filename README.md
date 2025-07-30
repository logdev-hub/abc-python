# 📦 Curva ABC com Python - Estoque de Papelaria

Este projeto apresenta uma simulação completa da aplicação da **Curva ABC** para otimização de estoques, utilizando dados fictícios de uma papelaria. É ideal para estudantes, analistas, profissionais de logística e professores que desejam entender como **Python** pode ser uma ferramenta poderosa na **gestão de estoques**.

---

## 📋 Objetivo

O objetivo é classificar os produtos com base no valor total de vendas, seguindo o princípio da Curva ABC:

- **Classe A**: Itens mais relevantes (≈ 80% do valor)
- **Classe B**: Itens intermediários (≈ 15%)
- **Classe C**: Itens menos representativos (≈ 5%)

---

## 📂 Estrutura dos Dados

A base de dados contém os seguintes campos:

- `Produto`: nome do item
- `Qtd_vendida`: quantidade total vendida
- `Preco_unitario`: valor unitário de venda

---

## 🐍 Bibliotecas utilizadas

### `pandas`

- Utilizada para estruturar e manipular os dados em formato de tabela (DataFrame).
- Permite calcular o valor total por item (`Qtd_vendida * Preco_unitario`).
- Facilita a ordenação, cálculo de percentuais acumulados e classificação ABC.

### `matplotlib.pyplot`

- Usada para criação de gráficos simples e visuais.
- Permite criar gráficos de barras mostrando o faturamento por produto.

### `seaborn`

- Biblioteca complementar ao Matplotlib com foco em visualização estatística.
- Foi usada para colorir as barras conforme a **classe ABC**.

---

## 🔎 Etapas do Código

1. **Criação dos dados simulados**: dicionário contendo produtos, quantidades e preços.
2. **Cálculo do valor total**: `Qtd_vendida * Preco_unitario`.
3. **Ordenação decrescente**: para identificar os maiores contribuintes de faturamento.
4. **Cálculo do percentual acumulado**: para determinar a posição relativa de cada item.
5. **Classificação ABC**:
   - Até 80%: Classe A
   - 80–95%: Classe B
   - Acima de 95%: Classe C
6. **Visualização gráfica**: gráfico de barras colorido com base nas classes.

---

## 📊 Exemplo do gráfico gerado

- O gráfico mostra a contribuição de cada produto para o valor total de vendas.
- As cores representam a classe ABC, facilitando a leitura visual.

---

## ✅ Resultados

- Identificação clara dos produtos que merecem prioridade na reposição.
- Redução de capital parado com produtos de baixa movimentação.
- Suporte à tomada de decisão em pequenos negócios com base em dados.

---

## 🧠 Sugestões de uso

- Adapte os dados para sua realidade (planilhas, sistemas, etc).
- Use este projeto como base para aulas, treinamentos ou análises reais.
- Combine com OpenPyXL ou Dash para criar dashboards automatizados.

---

## 📅 Última atualização

30/07/2025

---

Desenvolvido por **logdev-hub** | 🚀 Contribuições são bem-vindas!
