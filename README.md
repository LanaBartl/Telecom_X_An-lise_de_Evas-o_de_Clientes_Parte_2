# Telecom_X_An-lise_de_Evasão_de_Clientes_Parte_2


# 📊 Análise de Evasão de Clientes

Projeto de **Machine Learning em Python** focado na análise e previsão da **evasão de clientes (churn)**.

O objetivo foi identificar os fatores que mais influenciam o cancelamento de clientes e propor **estratégias de retenção baseadas em dados**.

---

# 🚀 Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# 📂 Objetivo do Projeto

Este projeto busca:

* Identificar **variáveis que influenciam a evasão de clientes**
* Avaliar **modelos de Machine Learning para prever churn**
* Propor **estratégias de retenção baseadas em análise de dados**

---

# 🤖 Modelos Avaliados

Foram avaliados dois modelos principais de Machine Learning.

## Regressão Logística

A **Regressão Logística** apresentou o melhor desempenho geral:

* **Acurácia:** ~80%
* Melhor equilíbrio entre **precisão e recall**
* Melhor **F1-score** para a classe de cancelamento
* **Alta interpretabilidade**, facilitando a análise dos fatores que influenciam o churn

## Random Forest

O modelo **Random Forest** também apresentou bons resultados, porém com **recall inferior para a classe de cancelamento**, o que é um ponto crítico quando o objetivo é prever evasão.

---

# 📈 Principais Fatores que Influenciam a Evasão

A análise dos coeficientes da **Regressão Logística** e da importância das variáveis no **Random Forest** revelou os principais fatores associados ao cancelamento.

## Fatores que aumentam a evasão

* Contrato **Month-to-month**
* Internet do tipo **Fiber optic**
* Pagamento via **Electronic check**
* **Fatura digital**
* Ausência de serviços como **segurança online**
* **Alto valor total acumulado**
* **Baixo tempo de contrato**

## Fatores que reduzem a evasão

* **Maior tempo de permanência na empresa** (principal fator)
* **Contratos de dois anos**
* Presença de **suporte técnico**
* Métodos automáticos de pagamento (**cartão ou transferência**)

O **tempo de contrato** foi a variável mais relevante no modelo, indicando que **clientes novos possuem maior risco de cancelamento**.

---

# 🧠 Interpretação Estratégica

Os resultados indicam que a evasão está fortemente relacionada a:

* **Baixa fidelização contratual**
* **Pouco tempo de relacionamento com a empresa**

Clientes com contratos mensais possuem maior flexibilidade para cancelar, o que aumenta o risco de churn. Além disso, clientes nos primeiros meses ainda não desenvolveram um vínculo com a empresa.

---

# 💡 Estratégias de Retenção Propostas

Com base nos resultados obtidos, recomenda-se:

### 1️⃣ Incentivar contratos de longo prazo

Oferecer descontos ou benefícios para clientes que migrarem de **contratos mensais para contratos anuais ou bianuais**.

### 2️⃣ Foco nos primeiros meses do cliente

Criar campanhas de acompanhamento nos **primeiros 3 a 6 meses**, período de maior risco de cancelamento.

### 3️⃣ Incentivar métodos automáticos de pagamento

Estimular pagamentos via **cartão ou débito automático**, reduzindo cancelamentos associados ao *Electronic check*.

### 4️⃣ Oferecer suporte técnico como benefício estratégico

Clientes que possuem suporte técnico apresentam **menor probabilidade de evasão**.

### 5️⃣ Monitoramento contínuo com modelo preditivo

Utilizar a **Regressão Logística** para identificar clientes com **alto risco de churn** e agir preventivamente.

---

# 📊 Conclusão

O projeto demonstrou que é possível **prever a evasão de clientes com bom nível de precisão utilizando técnicas de Machine Learning**.

A **Regressão Logística** se mostrou o modelo mais adequado, pois combina:

* bom desempenho preditivo
* alta interpretabilidade

Isso permite não apenas prever cancelamentos, mas também **compreender os fatores que influenciam essa decisão**, auxiliando na criação de estratégias eficazes de retenção.

---

# 👩‍💻 Autor

**Lana Bartl**

🔗 LinkedIn
👉 [https://www.linkedin.com/in/lanabartl/](https://www.linkedin.com/in/lanabartl/)

---
