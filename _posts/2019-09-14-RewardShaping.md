---
layout: post
image: /images/rlshaping.jpg
categories: Research
---
<!-- title -->
**Shaping Rewards for Combined Reinforcement and Imitation Learning using Generative Models**\
<!-- authors -->
**Yuchen Wu**, [Melissa Mozifian](https://mila.quebec/en/person/melissa-mozifian/), [Florian Shkurti](http://www.cs.toronto.edu/~florian/)\
<!-- venu, date -->
2019\
<!-- archive, code, slides -->
[pdf](http://www.cs.toronto.edu/~florian/rl_with_shaping/RLfD_via_Shaping.pdf) / [code](https://github.com/cheneyuwu/TD3fD-through-Shaping-using-Generative-Models)

<!-- abstract -->
The potential benefits of model-free reinforcement learning to real robotics systems are limited by its uninformed exploration that leads to slow convergence, lack of data-efficiency, and unnecessary interactions with the environment. To address these drawbacks we propose a method that combines reinforcement and imitation learning by shaping the reward function with a state-and-action-dependent potential that is trained from demonstration data. We show that this accelerates policy learning by specifying high-value areas of the state and action space that are worth exploring first. Unlike the majority of existing methods that assume optimal demonstrations and incorporate the demonstration data as hard constraints on policy optimization, we instead incorporate demonstration data as \textit{advice} in the form of a reward shaping potential trained as a generative model of states and actions. In particular, we use normalizing flows and Generative Adversarial Networks to represent these potentials. We show that, unlike existing approaches that incorporate demonstrations as hard constraints, our approach is unbiased even in the case of sub-optimal and noisy demonstrations. We present an extensive range of simulations, as well as experiments on the Franka Emika 7DOF arm, to demonstrate the practicality of our method.