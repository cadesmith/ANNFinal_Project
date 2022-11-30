# Reinforcement Learning for Asteroids game ([play](https://freeasteroids.org/))

Group members: Cade, Quan, and Carrington

## Plan:
1. Game src code: Use Gym for [game environment](https://www.gymlibrary.dev/environments/atari/asteroids/)
1. Reward function
1. Create [Q-model on Keras](https://keras.io/examples/rl/deep_q_network_breakout/)
1. If q-model ineffective / easy to implement:
1. modify amount of layers and etc.
2. Try different models and compare effectiveness with Q-model

Note: full_action_space=False (to fit with action space of Asteroids game): env.action_space=Discrete(14). How to get value from Discrete class?

## Instruction:
After publicized our repo:
1. Create a file on Colab. Run the followings:
    ```
    !git clone https://github.com/cadesmith/AsteroidsML.git
    ```
