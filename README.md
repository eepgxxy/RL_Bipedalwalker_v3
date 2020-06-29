# RL_Bipedalwalker_v3
Using reinforcement learning algorithm TD3 from PARL to solve Bipedalwalker-v3 based on gym box2d environment.

Bipedalwalker-v3 is one of the environments from [gym box2d](https://gym.openai.com/envs/#box2d).
The goal is to train a Bipedalwalker robot from knowing nothing about the environment to walk.


This repository includes the user-friendly jupyter notebook version of the solution.
The code is written using [PaddlePaddle](https://github.com/PaddlePaddle). The TD3 algorithm from [PARL](https://github.com/PaddlePaddle/PARL) is being used. 

After training for about 3000 episodes, the current best evaluation reward is about 100 per episode.
The current result is not as good as the claimed 300+. Further training with different hyper parameters are needed. 

![train rewards](https://github.com/eepgxxy/RL_Bipedalwalker_v3/blob/master/train.png)

![eval rewards](https://github.com/eepgxxy/RL_Bipedalwalker_v3/blob/master/eval.png)
