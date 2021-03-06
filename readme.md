# Deep Q Learning Plays 4x4 and 5x5 Frozen Lake (Not Slippery)  
![GitHub](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)  ![GitHub](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=Keras&logoColor=white)  
In this example, reinforcement learning method (Deep Q Learning) makes its effort to learn 4x4 and 5x5 Frozen Lake.  
Model created by Keras.  
The 4x4 and 5x5 game environments are like the following:  
16 states  
<p align="center">
  <img src="https://github.com/hamedmokazemi/QLearning_FrozenLake_1/blob/main/images/FrozenLake.png" alt="Sublime's custom image"/>
</p>  

25 states  
<p align="center">
  <img src="https://github.com/hamedmokazemi/QLearning_FrozenLake_1/blob/main/images/FrozenLake2.png" alt="Sublime's custom image"/>
</p>  
  
Or:
  
SFFF  
FHFH  
FFFH  
HFFG  
  
SFFHF  
HFHFF  
HFFFH  
HHHFH  
HFFFG  
  
S: starting point, safe  
F: frozen surface, safe  
H: hole, fall to your doom  
G: goal, where the frisbee is located  
  
  
The agent should start from start position (state: 0), and reach the goal (state: 15 or 24) by walking in the frozen areas. If the agent reach the goal, it gets a reward (1.0).  
  
It should be noted that the action numbers indicate the following directions:  
Action: Direction  
0:  Left  
1:  Down  
2:  Right  
3:  Up  
  
  
Network model for 4x4:
  
<p align="center">
  <img src="https://github.com/hamedmokazemi/DeepQLearning_FrozenLake_1/blob/main/images/dqn.png" alt="Sublime's custom image"/>
</p>  
  
  Network model for 5x5:
  
<p align="center">
  <img src="https://github.com/hamedmokazemi/DeepQLearning_FrozenLake_1/blob/main/images/dqn2.png" alt="Sublime's custom image"/>
</p>  
  
The final results:  
4x4  
<p align="center">
  <img src="https://github.com/hamedmokazemi/DeepQLearning_FrozenLake_1/blob/main/images/dqn-result1.png" alt="Sublime's custom image"/>
</p>  
  
5x5   
<p align="center">
  <img src="https://github.com/hamedmokazemi/DeepQLearning_FrozenLake_1/blob/main/images/dqn-result2.PNG" alt="Sublime's custom image"/>
</p>
