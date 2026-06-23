# Telco Customer Churn Prediction

> https://www.kaggle.com/datasets/blastchar/telco-customer-churn

     Autora do Notebook: Isabella Heder 

Este projeto tem como objetivo analisar e prever o churn de clientes em uma empresa de telecomunicações (Telco). Através de análise exploratória, engenharia de atributos e modelos de machine learning, foram identificados os principais fatores que influenciam o cancelamento e propostas estratégias de retenção.

### **Objetivo**
Criar modelos analíticos que permitam:
- Identificar clientes com risco de churn
- Entender os principais fatores que influenciam o cancelamento
- Apoiar a definição de programas de retenção mais eficientes e personalizados


### Dataset
- Dataset público da IBM colocado no Kaggle (link do início)
- Cada linha representa um cliente  
- Contém informações sobre:
  - Serviços contratados  
  - Dados demográficos  
  - Informações de conta  
  - Indicador de churn  

https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113

## Resultados:

Melhor modelo: Gradient Boosting Classifier

<img width="539" height="432" alt="34d7bda4-84ca-472b-9736-0279b8e32f7e" src="https://github.com/user-attachments/assets/9bc84d13-89b8-43b2-95b7-3fa7c533cd09" />

              precision    recall  f1-score   support

           0       0.91      0.71      0.80      1033
           1       0.50      0.79      0.61       374

    accuracy                            0.74      1407
    macro avg       0.70      0.75      0.71      1407
    weighted avg    0.80      0.74      0.75      1407
