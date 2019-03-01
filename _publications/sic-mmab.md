---
title: "SIC - MMAB: Synchronisation Involves Communication
in Multiplayer Multi-Armed Bandits"
collection: publications
permalink: /publication/sic-mmab
date: 2018-09-21
pubtype: 'preprint'
venue: 'COLT'
---
Motivated by cognitive radio networks, we consider the stochastic multiplayer multi-armed
bandit problem, where several players pull arms simultaneously and collisions occur if one of
them is pulled by several players at the same stage. We construct a decentralized algorithm
that achieves the same performance as a centralized one as long as players are synchronized and
observe their collisions. We actually achieve this result by constructing a communication protocol
between players that deliberately enforces collisions, allowing them to share their information at
a negligible cost.
Under a weaker assumption on the feedback, i.e., collisions are not observed, we still maintain
some communication between players but at the cost of some extra multiplicative term in the
regret.
Finally, we prove that the logarithmic growth of the regret is still achievable in the dynamic
case where players are not synchronized with each other, thus preventing communication.


[Download paper](http://eboursier.github.io/files/sic-mmab.pdf) / [citation](http://eboursier.github.io/files/sic-mmab.bib)
