---
title: "A Practical Algorithm for Multiplayer Bandits
when Arm Means Vary Among Players"
collection: publications
link: https://arxiv.org/abs/1902.01239
permalink: /publication/elim-etc
date: 2019-06-06
excerpt: ''
pubtype: 'conference'
category: 'multiagent'
venue: 'AISTATS 2020'
author: 'E. Boursier, E. Kaufmann, A. Mehrabian and V. Perchet'
---
We study a multiplayer stochastic multi-armed bandit problem in which players cannot communicate, and if two or more players pull the same arm, a collision occurs and the involved players receive zero reward. 
We consider the challenging heterogeneous setting, in which different arms may have different means for different players, and propose a new, efficient algorithm that combines the idea of leveraging forced collisions for implicit communication and that of performing matching eliminations. We give a finite-time analysis of our algorithm, bounding its regret by $O((\log T)^{1+\kappa})$ for any fixed $\kappa>0$. 
If the optimal assignment of players to arms is unique, we further show that it attains the optimal $O(\log(T))$ regret, solving an open question raised at NeurIPS 2018.

[Download paper](http://eboursier.github.io/files/elim-etc.pdf) / [citation](http://eboursier.github.io/files/elim-etc.bib)

[arXiv link](https://arxiv.org/abs/1902.01239)
