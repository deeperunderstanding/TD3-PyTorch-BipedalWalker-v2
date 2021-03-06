# TD3-BipedalWalker-v2-PyTorch

PyTorch implementation of [Twin Delayed DDPG](https://arxiv.org/abs/1802.09477) (TD3) for the [Bipedal Walker v2](http://gym.openai.com/envs/BipedalWalker-v2/) and [Lunar Lander Continuous v2](http://gym.openai.com/envs/LunarLanderContinuous-v2/) environment of OpenAI gym.

- To test a preTrained network : run `test.py`

- To train a new network : run `train.py`

## Dependencies
Trained and tested on:
```
Python 3.6
PyTorch 0.4.1
NumPy 1.15.3
gym 0.10.8
Pillow 5.3.0
```

## Results

### BipedalWalker-v2


Solved in 800 episodes:

(The results are not very consistent)

![Alt Text](https://github.com/nikhilbarhate99/TD3-BipedalWalker-v2-PyTorch/blob/master/gif/GIF-ONE.gif)

------------------------------------------------------------------------------------------------------

### LunarLanderContinuous-v2


Solved in 1500 episodes:

![Alt Text](https://github.com/nikhilbarhate99/TD3-PyTorch-BipedalWalker-v2/blob/master/gif/GIF-TWO.gif)

## References

- Official [TD3 paper](https://arxiv.org/abs/1802.09477) and [code](https://github.com/sfujim/TD3)


- [OpenAI SpinningUp in Deep RL](https://spinningup.openai.com/en/latest/algorithms/td3.html)

