# 📊 Value-Based Reinforcement Learning: V-Value & Q-Value Calculation

## 🔍 Overview
This notebook explores **V-value and Q-value calculations** in reinforcement learning by implementing dynamic programming techniques on an **(n_row × n_col) grid environment**. The goal is to verify the relationship between **V(s)** and **Q(s, a)** using Bellman equations.

## 🎯 Objectives
- Compute **V-values** (state values) and **Q-values** (state-action values).
- Understand how Bellman equations connect V-values and Q-values.
- Determine the optimal action for each state based on Q-values.

## 🛠 Dependencies & Installation
Ensure you have the required libraries installed:
```bash
pip install gymnasium numpy matplotlib
```

## 🔑 Key Components
### 1️⃣ Understanding V-Value & Q-Value
- **V(s):** Measures the expected return from state `s`.
- **Q(s, a):** Represents the expected return of taking action `a` in state `s`.
- **Bellman Equations:** Mathematical foundation for computing V-values and Q-values.

### 2️⃣ Implementation of Value-Based RL
- **Grid Environment Setup** ➝ Custom environment using `gymnasium`.
- **Dynamic Programming Techniques** ➝ Iterative computation of V-values & Q-values.
- **Policy Evaluation & Improvement** ➝ Selecting optimal actions using learned Q-values.

### 3️⃣ Performance Analysis
- **Comparison of V(s) & Q(s, a)** ➝ Validate theoretical equivalence.
- **Visualization of Value Functions** ➝ Plot state values for interpretability.
- **Optimal Policy Extraction** ➝ Determine the best action for each state.

## 📂 Metadata Files
- **Generated metadata files** store computed V-values and Q-values.
- These files facilitate debugging and allow further analysis of learned policies.

## 🚀 Execution Steps
1. Install dependencies and set up the grid environment.
2. Implement Bellman updates for V-values and Q-values.
3. Evaluate the results and extract the optimal policy.
4. Use stored metadata files for additional experiments.

## ⚠️ Notes
- This implementation is **Gymnasium-based**, ensuring compatibility with RL environments.
- **Policy improvement relies on correctly computed Q-values**.
- Ensure all cells are executed before submission to maintain reproducibility.


