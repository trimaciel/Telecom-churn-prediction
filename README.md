# 📊 Telecom Churn Prediction

Projeto criado para desenvolver modelos preditivos capazes de prever quais clientes têm maior chance de cancelar seus serviços em uma operadora de telecomunicações.

---

## 🧠 Objetivo

Identificar os principais fatores que levam clientes a cancelarem seus contratos, utilizando dados históricos e algoritmos de machine learning. Com isso, a empresa pode antecipar cancelamentos e adotar ações de retenção.

---

## 🗂️ Índice

- [Descrição do Projeto](#descrição-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Executar](#como-executar)
- [Modelos Treinados](#modelos-treinados)
- [Resultados e Insights](#resultados-e-insights)
- [Recomendações Estratégicas](#recomendações-estratégicas)
- [Conclusão Final](#conclusão-final)
- [Licença](#licença)

---

## 📝 Descrição do Projeto

Este projeto é a **segunda parte** do desafio Telecom X.  
Aqui, o foco está na **modelagem preditiva de churn**. A primeira parte tratou da extração, tratamento e análise exploratória dos dados.

### 🔁 Etapas realizadas:

1. **Carregamento dos dados tratados**
2. **Remoção de colunas irrelevantes (como IDs e total gasto)**
3. **Codificação com One-Hot Encoding**
4. **Balanceamento de classes com SMOTE**
5. **Normalização dos dados para modelos sensíveis à escala**
6. **Divisão em treino (70%) e teste (30%)**
7. **Treinamento de modelos (Logistic Regression, Random Forest, Decision Tree)**
8. **Avaliação com métricas e curva ROC**
9. **Análise da importância das variáveis**
10. **Geração de conclusões e recomendações estratégicas**

---

## 🚀 Tecnologias Utilizadas

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Google Colab
- Git e GitHub

---

## 🧪 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/trimaciel/Telecom-churn-prediction.git
```

2. Instale as dependências:
```bash
pip install -r requisitos.txt
```

3. Execute os notebooks no Google Colab ou localmente:
   - `telecom_modelagem.ipynb` (modelos e gráficos)
   - `conclusao_final.md` (relatório analítico final)

---

## 🤖 Modelos Treinados

- **Regressão Logística**
- **Árvore de Decisão (max_depth=4)** ✅ modelo escolhido
- **Random Forest**

Cada modelo foi avaliado com:
- Acurácia
- Precision, Recall, F1-score
- Matriz de Confusão
- Curva ROC e AUC

---

## 📈 Resultados e Insights

- **Modelo mais equilibrado:** Árvore de Decisão com `max_depth=4`
- **Acurácia final:** ~75%
- Variáveis com maior impacto na evasão:
  - Tipo de contrato (mensal = mais churn)
  - Forma de pagamento (cheque eletrônico)
  - Gasto mensal elevado
  - Pouco tempo de contrato
  - Ausência de suporte técnico e segurança online

---

## 🎯 Recomendações Estratégicas

- Oferecer **benefícios para contratos longos** (anual/bienal)
- Incentivar o uso de **pagamento automático**
- **Monitorar clientes com menor tenure** (tempo de contrato)
- Promover serviços de **segurança online e suporte técnico**
- Ações de retenção para usuários de **fibra óptica com churn elevado**

---

## 📄 Conclusão Final

Para mais detalhes sobre os insights, métricas dos modelos e recomendações, veja o arquivo:

📄 [conclusao_final.md](conclusao_final.md)


---

## 👩‍💻 Desenvolvedora

| [@trimaciel](https://github.com/trimaciel) |
|-------------------------------------------|
| Analista de Dados & Cientista em formação |


