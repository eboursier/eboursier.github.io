---
title: "Selfish Robustness and Equilibria in Multi-Player Bandits"
collection: publications
link: https://arxiv.org/abs/2002.01197
permalink: /publication/selfish-multiplayer
date: 2020-02-05
excerpt: ''
pubtype: 'conference'
category: 'multiplayer_bandit'
venue: 'COLT 2020'
author: 'E. Boursier and V. Perchet'
---
Motivated by cognitive radios, stochastic multi-player multi-armed bandits gained a lot of interest recently. In this class of problems, several players simultaneously pull arms and encounter a collision -- with 0 reward -- if some of them pull the same arm at the same time. While the cooperative case where players maximize the collective reward (obediently following some fixed protocol) has been mostly considered, robustness to malicious players is a crucial and challenging concern. Existing approaches consider only the case of adversarial jammers whose objective is to blindly minimize the collective reward.
We shall consider instead the more natural class of selfish players whose incentives are to maximize their individual rewards, potentially at the expense of the social welfare. We provide the first algorithm robust to selfish players (a.k.a. Nash equilibrium) with a logarithmic regret, when the arm reward is observed. When collisions are also observed, Grim Trigger type of strategies enable some implicit communication-based algorithms and we construct robust algorithms in two different settings: in the homogeneous case (with a regret comparable to the centralized optimal one) and in the heterogeneous case (for an adapted and relevant notion of regret). We also provide impossibility results when only the reward is observed or when arm means vary arbitrarily among players. 
