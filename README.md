# RL-Maze-Solver

This repository contains the implementation and report for the first coursework of the Reinforcement Learning (RL) module at Imperial College London. The project focuses on solving a Maze environment modeled as a Markov Decision Process (MDP) using various RL techniques.

## Coursework Overview

The coursework involves implementing and evaluating agents using:

1. **Dynamic Programming**: Solving the maze with full knowledge of the transition matrix and reward function.
2. **Monte Carlo Methods**: Learning the optimal policy through episodic sampling without knowledge of the environment dynamics.
3. **Temporal Difference Learning**: Using bootstrapping techniques to approximate value functions and policies.

The Maze environment consists of absorbing states with varying rewards, obstacles, and stochastic transitions.

## Project Structure

- **`Coursework1.ipynb`**: The main Jupyter Notebook containing the implementation and experiments for the coursework tasks.
- **`coursework1.py`**: The Python script exported from the notebook for submission and auto-marking.
- **`coursework1_report.pdf`**: The report containing detailed explanations, results, and analysis.

## Features

- **Dynamic Programming Agent**: Implements policy evaluation and improvement to solve the Maze environment.
- **Monte Carlo Agent**: Uses first-visit MC control to find an optimal policy by sampling episodes.
- **Temporal Difference Agent**: Implements TD learning (SARSA/Q-learning) for incremental policy optimization.
- **Visualization**: Generates policy and value function visualizations for analysis.
- **Learning Curves**: Plots the learning performance of agents across multiple training runs.

## Requirements

The following Python packages are required to run the notebook:

- `numpy`
- `matplotlib`
- `seaborn`
- `jupyter`

To install dependencies, run:

```bash
pip install -r requirements.txt
```

## Running the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/RL-Maze-Solver.git
   cd RL-Maze-Solver
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Coursework1.ipynb
   ```

3. Run the notebook cells sequentially to:
   - Define the environment.
   - Implement the agents.
   - Visualize results.

## Results

- **Dynamic Programming**: Achieved optimal policies and value functions with known environment dynamics.
- **Monte Carlo Methods**: Successfully learned policies through episodic sampling.
- **Temporal Difference Learning**: Efficiently approximated policies using TD techniques.

Detailed results and analyses are available in the `coursework1_report.pdf`.

## License

This project is for academic purposes and follows the coursework submission guidelines of Imperial College London. Please do not directly reuse the code for academic submissions without proper attribution.
