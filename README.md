
# IsaacGym-RL-Humanoid

This project is focused on training humanoid robots using reinforcement learning techniques within NVIDIA's Isaac Gym environment. The primary algorithm used is Proximal Policy Optimization (PPO), which is well-suited for environments with continuous action spaces.

## Current Status

Please note that this project is a work in progress. Development has been paused due to the deprecation of Isaac Sim, which has now transitioned to Isaac Lab. As a result, further updates and enhancements are currently on hold.

## Installation and Setup

1. **Python Environment**: Create a Python virtual environment using Python 3.6, 3.7, or 3.8 (3.8 is recommended).

2. **Install Dependencies**: Install the necessary Python packages, including PyTorch and other dependencies specified in the project.

3. **Isaac Gym Installation**: Download and set up Isaac Gym Preview 4 from NVIDIA's developer portal.

4. **Run an Example**: Navigate to the `examples` directory and execute a sample script to verify the setup.

## Running the Project

To train a humanoid model, use the following command:

```bash
python gpugym/scripts/train.py --task=pbrs:humanoid
```

For playing a trained policy, use:

```bash
python gpugym/scripts/play.py --task=pbrs:humanoid
```

## Note

As the project is currently on hold, please be aware that some features may not be fully functional or up-to-date with the latest developments in Isaac Lab.
```
