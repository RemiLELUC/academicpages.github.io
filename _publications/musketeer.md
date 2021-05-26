---
title: "SGD with Coordinate Sampling: Theory and Practice (preprint)"
collection: publications
permalink: /publication/csgd
excerpt: "With F.Portier. ([PDF](https://arxiv.org/pdf/2105.11818.pdf))"
# date: '2019-11-19'
# authors: "R.Leluc, F.Portier"
---
<p align="justify">
While classical forms of stochastic gradient descent algorithm treat the different coordinates in the same way,
a framework allowing for adaptive (non uniform) coordinate sampling is developed to leverage structure in data.
In a non-convex setting and including zeroth order gradient estimate, almost sure convergence as well as
non-asymptotic bounds are established. Within the proposed framework, we develop an algorithm, MUSKETEER,
based on a reinforcement strategy: after collecting information on the noisy gradients, it samples the most
promising coordinate (all for one); then it moves along the one direction yielding an important decrease of
the objective (one for all). Numerical experiments on both synthetic and real data examples confirm
the effectiveness of MUSKETEER in large scale problems.
