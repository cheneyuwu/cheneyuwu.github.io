---
layout: post
image: /images/rl_shaping.png
categories: Research
---
<!-- title -->
**Shaping Rewards for Combined Reinforcement and Imitation Learning using Generative Models**<br/>
<!-- authors -->
**Yuchen Wu**, [Melissa Mozifian](https://mila.quebec/en/person/melissa-mozifian/), [Florian Shkurti](http://www.cs.toronto.edu/~florian/)<br/>
<!-- venu, date -->
2019<br/>
<!-- archive, code, slides -->
[pdf](http://www.cs.toronto.edu/~florian/rl_with_shaping/RLfD_via_Shaping.pdf) / [code](https://github.com/cheneyuwu/TD3fD-through-Shaping-using-Generative-Models)

<!-- abstract -->
The potential benefits of model-free reinforcement learning to real robotics systems are limited by its uninformed exploration that leads to slow convergence, lack of data-efficiency, and unnecessary interactions with the environment. To address these drawbacks we propose a method that combines reinforcement and imitation learning by shaping the reward function with a state-and-action-dependent potential that is trained from demonstration data. We show that this accelerates policy learning by specifying high-value areas of the state and action space that are worth exploring first.