# 📊 Ad Selection using Thompson Sampling (Multi-Armed Bandit)

This project implements the **Thompson Sampling** algorithm to solve the Multi-Armed Bandit problem for selecting the most effective advertisement out of multiple choices.

## 🚀 What is Thompson Sampling?

Thompson Sampling is a probabilistic algorithm used to solve the exploration-exploitation trade-off in reinforcement learning. It selects ads based on the highest **beta distribution sample**, updating the probability after each reward feedback.

## 🧠 Algorithms Used

- ✅ **Thompson Sampling**
- (Optional: ✅ Upper Confidence Bound - UCB)

## 📂 Files

- `facebook ads  predicition using reinforcement learning.ipynb` - Main script for Thompson Sampling logic.
- `Facebookads.xlsx` - A dataset containing binary rewards (1 = click, 0 = no click) for different ads.


## 📈 How it works

1. The algorithm simulates a series of ad selections (like 10,000 rounds).
2. In each round:
   - It draws a random sample from a beta distribution for each ad.
   - Selects the ad with the highest sample.
   - Updates the success or failure count based on the reward received.
3. The total reward is tracked to evaluate effectiveness.

## 🛠 Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `matplotlib` *(for optional plotting)*

Install dependencies:

```bash
pip install pandas matplotlib
