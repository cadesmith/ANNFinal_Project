# Reinforcement Learning for Cartpole game

Group members: Cade, Quan, and Carrington ([Blogpost on Medium](https://medium.com/@cp108/understanding-reinforcement-learning-with-a-sarsa-based-model-b62dffe28a42))

## Plan:
1. Game src code: Use Gym for [game environment](https://www.gymlibrary.dev/environments/classic_control/cart_pole/)
1. Reward function
1. Create [Q-model on Keras](https://keras.io/examples/rl/deep_q_network_breakout/)
1. If q-model ineffective / easy to implement:
1. modify amount of layers and etc.
2. Try different models and compare effectiveness with Q-model

Note: full_action_space=False (to fit with action space of Asteroids game): env.action_space=Discrete(14). How to get value from Discrete class?



---
Files:
* `SARSA_Greedy.ipynb`: SARSA algorithm with Keras framework (uncomment: `!pip install ...`)
* `SARSA.ipynb`: SARSA algorithm from scratch. (install `gym` before running notebook)
* `./README_files/`: gifs of our models
* `./models/`, `Notes.md`, `asteroids.ipynb`, `blog_post.md`, `requirements.txt`, `sarsa_blog.md`: unimportant files
