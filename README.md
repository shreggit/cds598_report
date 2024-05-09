## Installation Requirements
Please ensure the following packages are installed:
- `luxai2021`
- `stable_baselines3`
- `torch`

You can install these packages using pip:
```bash
pip install luxai2021 stable_baselines3 torch
```
## PPO Folder Contents
- PPO Training Notebook: Use this Jupyter notebook to train the agent. It will also save the trained model upon completion.
- `PPO/PPO Training.ipynb`
- Agent Policy File: This script contains the agents policy. Note that it will be overwritten each time the PPO Training notebook is run.
- `PPO/agent_policy.py`
- Saved Model: After running the training for 12 million timesteps, the model is saved in this directory.
- `PPO/rl_model_1_12000000_steps.zip`
- Main.py: Use this script to run the model against other competitors. The script references the agent policy and model file, which can be modified as required.
- `PPO/main.py`

## IL Midterm Folder Contents
- Agent Policy
- `Imitation Learning Midterm/agent.py`
- Trained Model
- `Imitation Learning Midterm/model_il.pth`

## IL Final Folder Contents
- File to train the model
- `Imitation Learning Final/train.py`
- Agent Policy
- `Imitation Learning Final/agent.py`
