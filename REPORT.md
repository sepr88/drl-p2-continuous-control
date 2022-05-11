[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"
[image2]: img/result.JPG "Graph"

# Report

## The Enviroment

For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.  

![Trained Agent][image1]

In this environment, a double-jointed arm can move to target locations. A reward of **`+0.1`** is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of **`33`** variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between **`-1`** and **`1`**.

The task is episodic, and in order to solve the environment, your agent must get an average score of **`+30`** over **`100`** consecutive episodes.

## Solution

The learning algorithm is implemented in the files `Continuous_Control.ipynb` and `ddpg_agent.py`. Once the agent solves the environment with an average score of **`+30`** over **`100`** consecutive episodes, the actor network and critic network are saved in the files `checkpoint_actor.pth` and `checkpoint_critic.pth`, respectively.

## Deep Deterministic Policy Gradients (DDPG)

## Results

Training finished in **`???`** episodes with an average score of **`???`** over the recent **`100`** consecutive episodes.

![Graph][image2]

## Future Improvements

