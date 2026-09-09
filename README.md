# Demonstration code for the "Building a complete RL system" lecture

## Introduction
This code demonstrates our implementation of SARSA for the [Taxi-v4](https://gymnasium.farama.org/environments/toy_text/taxi/) environment and serves as additional information to go alongside the "Building a complete RL system" lecture.
The lecture is delivered as part of the CE7457 Reinforcement Learning course at Nanyang Technological University.

## Dependencies
This project uses [uv](https://docs.astral.sh/uv/) to manage Python and the dependencies ([Gymnasium](https://gymnasium.farama.org/), [Matplotlib](https://matplotlib.org/) and [NumPy](https://numpy.org/)). Install uv, then from this directory run

    uv sync

which creates a `.venv/` with everything needed. Run the scripts with `uv run`, for example

    uv run train_sarsa.py

## Jupyter Notebook
**We recommend going through the jupyter notebook file of this demonstration in your own time!** This includes further information and explanations to understand this demonstration and learn more about good practises in RL evaluation.
You can directly view the notebook [here](https://github.com/ntu-agents/rl-system-demo/blob/main/rl_demo.ipynb) or run it yourself with

    uv run jupyter lab rl_demo.ipynb

## Code
All code is written in Python3 and provided as separate scripts and all-together in one Jupyter notebook available [here](https://github.com/ntu-agents/rl-system-demo/blob/main/rl_demo.ipynb) with further explanations.

## Contact
This lecture is delivered by

- Eason Yu
- Ziyuan Liu

For any questions, please post on the NTULearn discussion forum or ask us at the tutorial sessions.
