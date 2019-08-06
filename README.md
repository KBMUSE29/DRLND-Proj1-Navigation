# **Project 1: Navigation**
## *Project Details:*
This project is intended to introduce students to Unity’s ML-Agents machine learning toolset and provide an opportunity to apply their knowledge of Deep Q-Learning networks to train a Reinforcement Learning (RL) agent.  The environment used for this project includes 37 discrete states and 4 actions which include moving the agent forward, backward, left, and right to collect yellow bananas while avoiding blue bananas.  The state space includes an array of ray casts that provide the agent information to determine banana color, direction, and distance. To solve the episodic task, the agent must get an average score of +13 over 100 consecutive episodes.

## Dependencies (for RTX 2080 Super GPU)
- https://github.com/udacity/deep-reinforcement-learning#dependencies
- PyTorch v1.1.0
- Python 3.7
- CUDA 10.0
- cuDNN 7.6.2 for CUDA 10.0
- Unity ML Agents

## Instructions
Clone https://github.com/udacity/deep-reinforcement-learning
1. Follow the instructions in the DRLND GitHub repository and setup the specified dependencies
2. Clone this repository
3. Copy all files located in this cloned repository into the following cloned deep-reinforcement-learning local directory "...\deep-reinforcement-learning\p1_navigation"
4. Unzip "Banana_Windows_x86_64.zip"
5. Update the file_name= directory on line 2 of section "2. Instantiate the Environment" to point to the local directory of the unzipped "Banana_Windows_x86_64" directory
6. Execute the code located in Navigation.ipynb after the "4. It's Your Turn!" heading
