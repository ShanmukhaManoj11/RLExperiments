# **Qlearning cartpole agent**

<img src="./env_image.png"/>

This is a Q-Table approach solving the cartpole balancing problem. The envrionment provides discrete action space with 2 possible actions 0 (moves the cart to left) and 1 (moves the cart to right). The observations space is 4 dimensional (x, x_dot, theta, theta_dot) and continuous. 

For the Q-Table approach, the observation space is discretized. 

**Next steps:**

Replace the Q-Table with a nerual network that learns the Q-function for the state-action pairs