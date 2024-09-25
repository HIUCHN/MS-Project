This project proposes a Bayesian Belief Network (BBN) model to quantify money laundering risk in financial transactions. Using synthetic data, the model is developed at both transaction and account levels. The BBN structure is learned using the Bayesian Search algorithm, with parameters optimized via Expectation Maximization (EM).
The modelling framework was illustrated below:

Key findings include:

	- Transaction Model: Achieved an AUC of 0.98, highlighting key factors such as sender behavior and transaction amount in predicting fraud.
	- Account Model: Achieved an AUC of 0.64, with insights into account-level risk factors like degree centrality and balance volatility.
