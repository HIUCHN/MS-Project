This project proposes a Bayesian Belief Network (BBN) model to quantify money laundering risk in financial transactions. Using synthetic data, the model is developed at both transaction and account levels. The BBN structure is learned using the Bayesian Search algorithm, with parameters optimized via Expectation Maximization (EM).
The modelling framework was illustrated below:
![Modelling Framework](https://github.com/user-attachments/assets/fa6363a5-94ce-4419-8da6-734ad314f734)


Key findings include:

- Transaction Model: Achieved an AUC of 0.98, highlighting key factors such as sender behavior and transaction amount in predicting fraud.
 ![image](https://github.com/user-attachments/assets/03a2633a-7a4f-407f-835d-5c04fdde8384)

- Account Model: Achieved an AUC of 0.64, with insights into account-level risk factors like degree centrality and balance volatility.
![image](https://github.com/user-attachments/assets/64a5480e-b301-4e66-b921-9d290f4eda87)
