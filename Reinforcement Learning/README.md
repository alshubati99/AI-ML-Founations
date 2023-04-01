# Reinforcement Learning Foundations
# [*Course Certificate*](https://www.linkedin.com/learning/certificates/c508f14c5bca9da932384b7b72f22d5cd61e10baa02ace3666b962e581349d71)

### [1] Getting Started with Reinforcement Learning:
- *Agent*: main property. 
- *State*: position the agent is in.
- *Environment*: what agent explore. 
- *Action*: what the agent does.
- *Reward*: What agen't gain. 
- *Policy*: stratigy.
- *Goal*: agent's mission.
- *Correct Action*: Positive reward.
- *Wrong Action*: Negitive reward.
- *Episodes*: series of actions before recieving a reward. 
- *MDP*: Markov Decision Process:
    - States.
    - Actions.
    - Rewards.
    - Missions.
- *Bellman Eqaution*:
    1. State Value Function:
        - Expected value of reward in a particular state.
    2. Action Value Function:
        - Expected value of the reward in a particular state given that the agent has taken an initial action.
    > in both cases we need to reach the optimal path.

### [2] Reinforcement Learning Algorithms:
- *MCM*: Monte Carlo Method
- *Q-Table*. 
- *TDM*: Temporal Difference Methods. 
- Deep Reinforcement Learning: using neutral networks to map states and actions to reward.
- Inverse Reinforcement Learning: learning by imitation. 
- Multi-Agent Reinforcement Learning: Multiple reinforcement learning agents learning at the same time. 

### [3] Monte Carlo Method: 
- Q-Table:
    - columns: states. 
    - rows: actions. 
- Exploration: understands as much as possible.
- Exploitation: Learns as much as possible. 
- Optimal Policies.
- More exploration = better rewards.
- strategy: initially = exploration then expliotation. 
- Monte Carlo Prediction:
    - Uses Bellman Equation. 
- Monte Carlo Control.
- *Greedy Policies*: selects best action. 
- *Incremental Mean*; updates the policy after each episodes. 
- *Constant Alpha*: used to update teh policy after every episode. 

### [4] Temporal Difference Methods:
- Has a low variance but baised. 
1. *SARSA*: State, Action, Reward, State, Action.
2. *SARSAMAX* (Q-learning): 
    - same policy of SARSA but it updates policy according to Greedy policy. 
3. *Expected SARSA*: 
    - Use same policy as SARSA (unpolicy).

### [5] Modified Forms of Reinforcement: 
- How it works.
- How agent learns.
- How actions values are stored.
- Deep learning helps the development of reinforecement learning using the neural networks. 
- Imitation Learning: imitate the human behavior. 
> The survey of Reinforecement Learning.</br>
> RL: a form of machine learning. 
