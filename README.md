# 🚀 Upper Confidence Bound (UCB) - Ad Selection Optimization

This repository demonstrates the implementation of the **Upper Confidence Bound (UCB)** algorithm using a dataset that simulates ad selections in a web-based environment.

---

## 📊 Problem Statement

We are presented with a dataset containing **10 different advertisements**, shown to users over **10,000 rounds**. Each round logs whether an ad was clicked (`1`) or not (`0`).

The goal is to optimize ad selection using the UCB algorithm, ensuring we show the best-performing ads more frequently over time.

---

## 📁 Dataset Description

- **Rows:** 10,000 (each row represents a round)
- **Columns:** 10 (each column represents one ad)
- **Values:**  
  - `1` → Ad was clicked  
  - `0` → Ad was not clicked

---

## 🧠 Algorithm Used

### Upper Confidence Bound (UCB)

The UCB algorithm is a type of reinforcement learning strategy used to solve the **multi-armed bandit problem**. It aims to find the balance between:

- **Exploration:** Trying out ads that haven’t been selected as often to gather more information.
- **Exploitation:** Choosing ads that are known to give high rewards based on previous results.

---

## 📓 Notebook Contents

The Jupyter notebook includes:

- Loading and previewing the dataset
- Implementing the UCB algorithm from scratch
- Tracking and visualizing the number of times each ad was selected
- Plotting the distribution of rewards

---

## 📈 Visualization

The notebook contains the following visual outputs:

- 📊 A histogram showing how many times each ad was selected
- 📈 A cumulative reward counter to show total performance over time

---

## 📦 Dependencies

The following Python libraries are required to run this project:

```bash
pip install numpy matplotlib pandas
