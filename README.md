# Derivative Hedging using Reinforcement Learning

## Files
- Generate_Data.ipynb: Gets real world stock data from yfinance, generates simulated call options data, outputs train and test datasets

- Environment.ipynb: Sets up derivative hedging environment

- Delta_Baseline.ipynb: Implements traditional delta hedging baseline model

- DQN.ipynb: Implements and trains DQN model

- DDPG.ipynb: Implements and trains DDPG model

- Model_Eval.ipynb: Loads trained models, and test them on unseen test dataset. Models are evaluated and compared against one another.

### How to run
Just run Model_Eval.ipynb. All outputs will be there.