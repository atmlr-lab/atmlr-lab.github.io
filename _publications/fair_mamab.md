---
title: "Multi-agent Multi-armed Bandits with Minimum Reward Guarantee Fairness"
authors: "Piyushi Manupriya, Himanshu, SakethaNath Jagarlapudi, Ganesh Ghalme"
venue: "AAMAS 2025"
date: 2024-12-20
picurl: "http://example.com"
codeurl: "http://github.com/Piyushi-0/Fair-MAMAB"
pdfurl: "https://arxiv.org/pdf/2502.15240" 
layout: paper
---
We investigate the problem of maximizing social welfare while ensuring fairness in a multi-agent multi-armed bandit (MA-MAB) setting. In this problem, a centralized decision-maker takes actions over time, generating random rewards for various agents. Our goal is to maximize the sum of expected cumulative rewards,  a.k.a. social welfare, while ensuring that each agent receives an expected reward that is at least a constant fraction of the maximum possible expected reward.

Our proposed algorithm, {\sc RewardFairUCB}, leverages the Upper Confidence Bound (UCB) technique to achieve sublinear regret bounds for both fairness and social welfare. The fairness regret measures the positive difference between the minimum reward guarantee and the expected reward of a given policy, whereas the social welfare regret measures the difference between the social welfare of the optimal fair policy and that of the given policy.

We show that {\sc RewardFairUCB} algorithm achieves  instance-independent social welfare regret guarantees of $\tilde{O}(T^{1/2})$ and a fairness regret upper bound of $\tilde{O}(T^{3/4})$. We also give the  lower bound of  $\Omega(\sqrt{T})$ for both social welfare and fairness regret. We evaluate { \sc RewardFairUCB}'s performance against various baseline and heuristic algorithms using simulated data and real world data, highlighting trade-offs between fairness and social welfare regrets.
