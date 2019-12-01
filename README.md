
# Udacity Deep Reinforcement Learning Nanodegree - Project 1 (Navigation)

## Description

This project aims the develpment of a training routine for an agent to navigate a square world collecting bananas.
A reward of +1 is given if the collected banana is yellow, otherwise a reward of -1 is assigned. The more yellow bananas and less non-yellow bananas, the better.

The state space has 37 dimensions, comprising the agent's velocity and its perception of objects on forward direction.
The action space is discrete, comprised of 4 possible movements:
- **`0`** - forward.
- **`1`** - backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic and the solution is achieved when the agent gets an average score of +13 for 100 consecutive episodes.

## Steps

1. Install the following python libraries:
- [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md) (v0.4.0)
- PyTorch (v0.4.0)
- NumPy
- Matplotlib

2. The OS chosen for the development was Ubuntu, for which there are two possible environment files available for download:
- [with visual feedback](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
- [without visual feedback](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip)

3. Download and uncompress the compatible environment file

4. Run the `Navigation.ipynb` notebook to train and evaluate the agent.

