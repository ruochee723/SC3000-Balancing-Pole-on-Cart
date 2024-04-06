# SC3000-Balancing-Pole-on-Cart

This is the repository for our SC3000 (Artificial Intelligence) assignment. The goal is to develop a Reinforcement Learning (RL) agent that is able to balance an upright pole on a cart only by pushing the cart left or right. The trained agent should know which way to push based on the cart's position and velocity, and the pole's angle and angular velocity.

## Getting Started

Follow the commands to set up your environment.

```bash
git clone git@github.com:ruochee723/SC3000-Balancing-Pole-on-Cart.git
cd SC3000-Balancing-Pole-on-Cart
conda create --name SC3000 python=3.9
conda activate SC3000
pip install -r requirements.txt
```

## Preview Our Code

You can visit [here](https://ruochee723.github.io/SC3000-Balancing-Pole-on-Cart/) to preview our code.

## Contributions

| Name | Contributions |
|:----:|:-------------:|
| [pufanyi](pufanyi.github.io) | Q-Learning Agent, Deep Q-Learning Agent|
| [Soo Ying Xi](https://github.com/niyaojiayou) | Q-Learning Agent, Deep Q-Learning Agent |
| [Ting Ruo Chee](https://github.com/ruochee723/) | Q-Learning Agent, Deep Q-Learning Agent |

## References

1. Paszke, A., & Towers, M. (n.d.). Reinforcement Learning (DQN) Tutorial. PyTorch. https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html
2. Lillicrap, T. P., Hunt, J. J., Pritzel, A., Heess, N., Erez, T., Tassa, Y., Silver, D., & Wierstra, D. (2016). Continuous Control With Deep Reinforcement Learning. ICLR 2016. https://arxiv.org/pdf/1509.02971.pdf
3. Mnih, V., Kavukcuoglu, K., Silver, D., Graves, A., Antonoglou, I., Wierstra, D., & Riedmiller, M. (2013). Playing Atari with Deep Reinforcement Learning. https://arxiv.org/pdf/1312.5602.pdf
4. Nakkiran, P., Kaplun, G., Bansal, Y., Yang, T., Barak, B., & Sutskever, I. (2019). Deep Double Descent: Where Bigger Models and More Data Hurt. ArXiv.org. https://arxiv.org/abs/1912.02292
