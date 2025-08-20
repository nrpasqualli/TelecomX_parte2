
# 📊 Análise de Evasão de Clientes (Churn) – TelecomX

Este notebook realiza uma análise exploratória de dados (EDA) sobre a base de clientes da **TelecomX**, com o objetivo de identificar padrões relacionados à **evasão de clientes (churn)** e gerar **insights estratégicos** para ações de retenção.

---

## 📂 Conjunto de Dados

O dataset utilizado é o **TelecomX\_Data.json**, que contém informações sobre clientes de uma empresa de telecomunicações, abrangendo:

* Dados demográficos;
* Serviços contratados;
* Informações de cobrança e pagamento;
* Status de cancelamento (**Churn**).

---

## 🔎 Etapas da Análise

### 1. Extração e Limpeza

* Carregamento do dataset (JSON via URL);
* Normalização de estruturas aninhadas;
* Padronização dos nomes das colunas;
* Tratamento de valores ausentes e inconsistentes.

### 2. Transformação de Dados

* Conversão de tipos de variáveis;
* Criação de novas métricas (ex.: cobrança diária).

### 3. Análise Exploratória (EDA)

* Comparação entre clientes idosos e não idosos quanto a permanência e cobranças;
* Distribuição de churn por gênero;
* Impacto de pacotes de serviços completos vs. incompletos no cancelamento;
* Associação entre métodos de pagamento e churn;
* Análise das distribuições de **Meses de Permanência** e **Cobrança Total** entre clientes ativos e cancelados;
* Identificação dos grupos mais propensos ao churn.

### 4. Visualizações

* Gráficos de barras, histogramas e distribuições para ilustrar os principais achados.

---

## 📄 Relatório Final

* Consolidação das descobertas;
* Conclusões sobre fatores críticos associados à evasão;
* Recomendações estratégicas para retenção.

---

## 📌 Principais Descobertas

* **Permanência curta** e **pacotes de serviços incompletos** são fortemente associados ao churn;
* O método de pagamento **Electronic check** apresenta maior índice de cancelamentos;
* Variáveis demográficas isoladas (gênero e status de idoso) têm impacto limitado, quando comparadas ao **tempo de permanência** e ao **tipo de pacote contratado**;
* O grupo mais vulnerável ao churn é o de clientes com **pacotes de serviços incompletos**.

---

## ⚙️ Como Executar o Notebook

1. Abra em um ambiente Python (ex.: **Jupyter Notebook** ou **Google Colab**).
2. Instale as bibliotecas necessárias:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Execute as células sequencialmente para reproduzir a análise.
4. Garanta que o arquivo **TelecomX\_Data.json** esteja acessível (neste projeto, ele é carregado diretamente via URL).

---

## 📑 Relatório Detalhado

A seção **📄 Relatório Final** dentro do notebook apresenta uma análise aprofundada, com **insights acionáveis** para apoiar a definição de estratégias de retenção de clientes.

---

