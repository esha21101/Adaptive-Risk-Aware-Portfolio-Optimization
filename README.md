# Adaptive-Risk-Aware-Portfolio-Optimization

Adaptive Risk-Aware Portfolio Optimization
Reinforcement learning (RL)-based investment strategies have been widely adopted in portfolio management (PM) in recent years. However, most RL-based approaches primarily focus on maximizing returns while neglecting the risks associated with underlying trading strategies. This can lead to significant losses, especially in highly volatile markets.

To address this issue, this project introduces a risk-aware PM framework that integrates RL with barrier functions (BF) to balance the trade-off between high returns and controlled risk exposure. While RL aggressively searches for profitable trading strategies, the BF-based risk controller continuously monitors market conditions and dynamically adjusts the investment portfolio to mitigate potential losses, particularly during downtrend markets.

Additionally, two adaptive mechanisms are incorporated to dynamically adjust the impact of risk controllers, allowing the framework to adapt flexibly to both uptrend and downtrend markets. Empirical results demonstrate the effectiveness of this approach compared to traditional RL-based strategies on real-world datasets. This work also opens new avenues for future research in risk-aware portfolio management.

Requirements
Ensure you are using Python 3.x, then install the required dependencies by running:

bash
Copy
Edit
python -m pip install -r requirements.txt
Usage
Configure algorithms and trading settings in config.py. After setup, start training by running:

bash
Copy
Edit
python entrance.py
Acknowledgements
This project builds upon the following implementations:

Compared Algorithm Implementation: PGPortfolio

Trading Environment: FinRL

TD3 Implementation: Baselines3

Financial Indicator Implementation: TA-Lib

Second-order Cone Programming Solver: CVXOPT

We appreciate the contributions of these works, as they have been instrumental in the development of this project.

Disclaimer
This implementation is for research purposes only. Please note that financial markets inherently carry risks.

For any inquiries, feel free to contact: esha21101@iiitnr.edu.in
