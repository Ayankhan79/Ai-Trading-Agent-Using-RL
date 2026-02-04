AI Stock Trading Agent — Project Summary

This project builds an AI-powered stock trading system using Reinforcement Learning (Deep Q-Networks) that learns when to buy, sell, or hold a stock based on historical market data.
Instead of using fixed trading rules, the agent improves through experience by interacting with a simulated trading environment and maximizing profit as a reward.


🚀 What the System Does :- 
• Downloads real stock price data (Apple – AAPL) using Yahoo Finance
• Creates useful indicators (SMA 5, SMA 20, daily returns)
• Simulates a stock trading environment with cash and holdings
• Trains a Deep Q-Network to evaluate actions
• Uses experience replay and epsilon-greedy exploration
• Learns profitable trading behavior over many episodes
• Evaluates final performance using portfolio profit


🧠 Core Technologies & Concepts Area	Used

Data:	Yahoo Finance, Pandas, NumPy | AI Model: Deep Q-Network (PyTorch) | Learning:	Reinforcement Learning | Strategy:	Buy / Sell / Hold |
Optimization:	Adam + MSE Loss | Exploration:	Epsilon-greedy | Memory:	Replay Buffer(deque)


📊 How Learning Works (in simple terms)
AI sees market indicators
Chooses an action (buy/sell/hold)
Market updates portfolio
Profit at the end becomes reward
Neural network learns better decisions
Process repeats many times


✅ Result
After training over multiple episodes, the agent learns a trading strategy that can produce profit over historical data.

Note: Data should be split into Training and Testing and then performed this action above for more real time accuracy for real world application.
So that Data is not Introduced to AI model and let it be fair test
