This project proposes a Bayesian Belief Network (BBN) model to quantify money laundering risk in financial transactions. Using synthetic data, the model is developed at both transaction and account levels. Python was utilized to clean, EDA, and feature engineer to prepare data for modelling. The BBN structure is learned using the Bayesian Search algorithm, with parameters optimized via Expectation Maximization (EM) in Genie Software, which is a specialized application for modelling Bayesian Belief Network.
The modelling framework was illustrated below:
![Modelling Framework](https://github.com/user-attachments/assets/fa6363a5-94ce-4419-8da6-734ad314f734)

Structure of transaction - based model
![image](https://github.com/user-attachments/assets/9dadaefa-2486-45b5-a728-9cf9df2de4e7)



Structure of account - based model
![image](https://github.com/user-attachments/assets/1455f6b9-5631-4441-a6c7-4b5e8c4d9523)


Key findings include:

- Transaction Model: Achieved an AUC of 0.98, highlighting key factors such as sender behavior and transaction amount in predicting fraud.
![image](https://github.com/user-attachments/assets/03a2633a-7a4f-407f-835d-5c04fdde8384)
![image](https://github.com/user-attachments/assets/2a94b7e3-12de-493e-b6f8-e9e21757cfeb)


- Account Model: Achieved an AUC of 0.64, with insights into account-level risk factors like degree centrality and balance volatility.
![image](https://github.com/user-attachments/assets/64a5480e-b301-4e66-b921-9d290f4eda87)
![image](https://github.com/user-attachments/assets/28c61004-4b33-4cae-a381-5394d0432255)

