# RL Agent for Dynamic Vehicle Routing & Resource Allocation

## Overview

This project uses Reinforcement Learning (PPO) to solve Dynamic Vehicle Routing and Resource Allocation problems under stochastic customer demand and strict delivery time-window constraints.

The system simulates real-world logistics operations where delivery vehicles must optimize routing decisions in real time while minimizing route duration, delivery delays, and total travel distance.

---

## Tech Stack

- Python
- PyTorch
- Stable-Baselines3 (PPO)
- Gymnasium
- Google OR-Tools
- MLflow
- Docker
- NumPy
- Pandas
- Matplotlib

---

## Features

- Custom Gymnasium routing environment
- PPO-based Reinforcement Learning agent
- Dynamic delivery routing optimization
- Stochastic customer demand simulation
- Delivery time-window constraints
- OR-Tools optimization benchmark
- Offline evaluation framework
- MLflow experiment tracking
- Dockerized training pipeline

---

## Problem Statement

Traditional vehicle routing systems struggle in dynamic environments where customer requests continuously change.

This project explores how Reinforcement Learning can improve:

- Real-time dispatch decisions
- Resource allocation
- Route optimization
- On-time delivery performance
- Logistics efficiency

---

## Reinforcement Learning Pipeline

```text
Environment → PPO Agent → Actions → Rewards → Policy Optimization
```

---

## Evaluation Metrics

The RL agent is evaluated using:

| Metric | Description |
|---|---|
| Average Delivery Time | Mean route completion time |
| On-Time Delivery % | Deliveries completed within deadline |
| Total Distance | Overall route distance |
| Fuel Cost | Estimated operational cost |

---

## Benchmark Comparison

The RL agent is benchmarked against:

- Nearest Neighbor Heuristic
- Google OR-Tools MILP Solver

---

## Results

- RL agent achieved lower average route duration
- Improved delivery efficiency
- Reduced total travel distance
- Better adaptability under stochastic demand

---

## Repository Structure

```bash
RL-Agent-for-Dynamic-Vehicle-Routing-Resource-Allocation/
│
├── env/
├── agents/
├── baselines/
├── configs/
├── experiments/
├── docker/
├── notebooks/
├── results/
│
├── train.py
├── evaluate.py
├── requirements.txt
└── README.md
```

---

## Future Improvements

- Multi-agent Reinforcement Learning
- Graph Neural Networks (GNNs)
- Real-time traffic simulation
- Cloud deployment
- FastAPI inference API
- Streamlit dashboard

---

## Author

Vishal Singh Mourya

MBA Data Science | Reinforcement Learning | Optimization | Machine Learning
