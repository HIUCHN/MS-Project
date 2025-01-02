This project proposes a Bayesian Belief Network (BBN) model to quantify money laundering risk in financial transactions. Using synthetic data, the model is developed at both transaction and account levels. Python was utilized to clean, EDA, and feature engineer to prepare data for modelling. The BBN structure is learned using the Bayesian Search algorithm, with parameters optimized via Expectation Maximization (EM) in Genie Software, which is a specialized application for modelling Bayesian Belief Network.
The modelling framework was illustrated below:
![image](https://github.com/user-attachments/assets/8304250e-5943-4887-858c-e96f61fd1944)


The modelling process give a structure a graph model that illustrates the relationship and the impact of features in relevant to target variable (Fraud). These two figures below showed structure of transaction - based model and account - based model.

- Structure of transaction - based model
![image](https://github.com/user-attachments/assets/9dadaefa-2486-45b5-a728-9cf9df2de4e7)

- Structure of account - based model
![image](https://github.com/user-attachments/assets/1455f6b9-5631-4441-a6c7-4b5e8c4d9523)

Running model on test dataset and probabilistic inference, key findings include:

- Transaction Model: Achieved an AUC of 0.98, highlighting key factors such as sender behavior and transaction amount in predicting fraud.
![image](https://github.com/user-attachments/assets/e0919604-bd25-43f2-8929-818db9ee5dc0)
![image](https://github.com/user-attachments/assets/8b476f89-cf06-4988-9985-295251b014fb)

- Account Model: Achieved an AUC of 0.64, with insights into account-level risk factors like degree centrality and balance volatility.
![image](https://github.com/user-attachments/assets/26338301-a158-4357-888f-83faf7db384e)
![image](https://github.com/user-attachments/assets/e79e2d75-9ad7-4296-9dbd-3ae4cf927161)


