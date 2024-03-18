![EasyRL4Rec Logo](assets/logo.jpg)

--------------------------------------------------------------------------------

# EasyRL4Rec

[![LICENSE](https://img.shields.io/badge/license-MIT-green)](https://github.com/chongminggao/EasyRL4Rec/blob/main/LICENSE)

EasyRL4Rec is a comprehensive and easy-to-use library designed specifically for Reinforcement Learning (RL)-based Recommender Systems (RSs).
This library provides lightweight and diverse RL environments based on five public datasets and includes core modules with rich options, simplifying model development. It provides unified evaluation standards focusing on long-term outcomes and offers tailored designs for state modeling and action representation for recommendation scenarios.
The main contributions and key features of this library can be summarized as follows

* **An Easy-to-use Framework.**

* **Unified Evaluation Standards**

* **Tailored Designs for Recommendation Scenarios**

  * customizable modules for state modeling and action representation.

* **Insightful Experiments for RL-based RSs**

We hope EasyRL4Rec can facilitate the model development and experimental process in the domain of RL-based RSs. More descriptions are available via this [paper](https://arxiv.org/pdf/2402.15164.pdf)

If this work helps you, please kindly cite our paper:
```tex
@misc{yu2024easyrl4rec,
      title={EasyRL4Rec: A User-Friendly Code Library for Reinforcement Learning Based Recommender Systems}, 
      author={Yuanqing Yu and Chongming Gao and Jiawei Chen and Heng Tang and Yuefeng Sun and Qian Chen and Weizhi Ma and Min Zhang},
      year={2024},
      eprint={2402.15164},
      archivePrefix={arXiv},
      primaryClass={cs.IR}
}
```



## Key Components

* **Lightweight Environment**.

  * bulit on five public datasets: Coat, MovieLens, Yahoo, KuaiRec, KuaiRand

* **StateTracker with rich options**.

  * Encompassing popular methods in sequential modeling: Average, GRU, Caser, SASRec, NextItNet

* **Comprehensive RL Policies**.

  * extend RL policies in [Tianshou](https://github.com/thu-ml/tianshou). 
  
  * include a mechanism to convert continuous actions to discrete items. 

* **Two Training Paradigms**.

  * Learning directly from offline logs.

  * Learning with a user model. 

* **Unified Evaluation**.

  * Offline Evaluation focusing on long-term outcomes.
  * Three modes:
    * FreeB: allow repeated recommendations, interactions are terminated by quit mechanism.
    * NX_0: prohibit repeated recommendations, interactions are terminated by quit mechanism.
    * NX_X: prohibit repeated recommendations, interactions are fixed as X rounds without quit mechanism.

<div style="text-align: center;">
<img src="assets/framework.png" alt="framework" width="50%" />
</div>
