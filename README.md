# DRL
PyTorch implementation of deep reinforcement learning algorithms

We have implemented and trained the agents with the IRL algorithms using the following environments.

- [OpenAI GYM Mountain car](https://gym.openai.com/envs/MountainCar-v0/)
- [Mujoco Hopper](https://gym.openai.com/envs/Hopper-v2/)

For reference, reviews of below papers related to IRL (in Korean) are located in [Let's do Inverse RL Guide](https://reinforcement-learning-kr.github.io/2019/01/22/0_lets-do-irl-guide/).

<a name="1"></a>

- [1] [AY. Ng, et al., "Algorithms for Inverse Reinforcement Learning", ICML 2000.](http://ai.stanford.edu/~ang/papers/icml00-irl.pdf) 

<a name="2"></a>

- [2] [P. Abbeel, et al., "Apprenticeship Learning via Inverse Reinforcement Learning", ICML 2004.](http://people.eecs.berkeley.edu/~russell/classes/cs294/s11/readings/Abbeel+Ng:2004.pdf)

<a name="3"></a>

- [3] [ND. Ratliff, et al., "Maximum Margin Planning", ICML 2006.](https://www.ri.cmu.edu/pub_files/pub4/ratliff_nathan_2006_1/ratliff_nathan_2006_1.pdf)

<a name="4"></a>

- [4] [BD. Ziebart, et al., "Maximum Entropy Inverse Reinforcement Learning", AAAI 2008.](http://www.aaai.org/Papers/AAAI/2008/AAAI08-227.pdf)

<a name="5"></a>

- [5] [J. Ho, et al., "Generative Adversarial Imitation Learning", NIPS 2016.](https://papers.nips.cc/paper/6391-generative-adversarial-imitation-learning.pdf)

<a name="6"></a>

- [6] [XB. Peng, et al., "Variational Discriminator Bottleneck. Improving Imitation Learning, Inverse RL, and GANs by Constraining Information Flow", ICLR 2019.](https://arxiv.org/pdf/1810.00821.pdf)

## Table of Contents

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->
<!-- code_chunk_output -->

- [Let's do Inverse RL](#lets-do-inverse-rl)
  - [Introduction](#introduction)
  - [Table of Contents](#table-of-contents)
  - [Mountain car](#mountain-car)
    - [1. Information](#1-information)
    - [2. Expert's demonstrations](#2-experts-demonstrations)
    - [3. Train & Test](#3-train--test)
      - [APP](#app)
      - [MaxEnt](#maxent)
    - [4. Trained Agent](#4-trained-agent)
  - [Mujoco Hopper](#mujoco-hopper)
    - [1. Installation](#1-installation)
    - [2. Expert's demonstrations](#2-experts-demonstrations-1)
    - [3. Train & Test](#3-train--test-1)
      - [GAIL](#gail)
      - [VAIL](#vail)
    - [4. Tensorboard](#4-tensorboard)
    - [5. Trained Agent](#5-trained-agent)
  - [Reference](#reference)
  - [Implementation team members](#implementation-team-members)

<!-- /code_chunk_output -->
