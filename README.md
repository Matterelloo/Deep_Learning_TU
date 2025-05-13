### Setup

To set up the environment and install the required dependencies, follow these steps:

1. Create a virtual environment (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## The project
- [ ] **DQN Implementation**:
    - [x] Implement the Q-Network architecture (typically a multi-layer perceptron for simple environments).
    - [x] Implement the experience replay buffer.
    - [x] Implement the target network update mechanism.
    - [x] Implement the ϵ-greedy action selection strategy.
    - [ ] Implement the DQN loss function and training loop.

- [ ] **Training**:
    - [ ] Train the DQN agent in the chosen environment.
    - [ ] Monitor training progress (e.g., episode rewards, loss).
    - [ ] Evaluate the trained agent’s performance (e.g., average score over multiple episodes).
    - [ ] Experiment with hyperparameters (e.g., learning rate, replay buffer size, ϵ decay rate, network architecture).

- **Expected Deliverables**:
    - Produce a project report.
    - Deliver a group presentation.
    - Submit well-commented source code.
