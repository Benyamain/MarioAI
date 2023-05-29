# MarioAI

In my Mario reinforcement learning project, I set up the game using the Gym environment. To optimize the learning process, I applied a grayscale filter to the frames, which helped focus on essential visual features while reducing unnecessary information.

Additionally, I implemented frame stacking, capturing moments when Mario made an action. This technique allowed the model to consider the sequential nature of the game and better understand the dynamics of Mario's movements.

For the reinforcement learning algorithm, I utilized the CNNPolicy variant of Proximal Policy Optimization (PPO).

During the training process, the model reached an impressive milestone of 4 million steps. This indicates the extensive exploration and learning undertaken by the model to improve its performance in the game.

The training phase for the model lasted approximately 5 and a half days. This duration demonstrates the computational resources and time required to train a model that can achieve a high level of proficiency in complex games like Mario.

You can find the demo [here]()!
