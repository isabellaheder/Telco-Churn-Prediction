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

<img width="539" height="432" alt="a4080bfb-c5c1-4d4b-ad77-c1204c50e741" src="https://github.com/user-attachments/assets/99920606-db49-4c5e-b196-a9e47be90721" />


              precision    recall  f1-score   support

           0       0.80      0.72      0.76       374
           1       0.75      0.82      0.78       374

    accuracy                           0.77       748
    macro avg       0.78      0.77     0.77       748
    weighted avg    0.78      0.77     0.77       748
