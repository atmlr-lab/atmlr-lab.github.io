---
title: "Improving Attribution Methods by Learning Submodular Functions"
authors: "Piyushi Manupriya, Tarun Ram Menta, SakethaNath Jagarlapudi, Vineeth N Balasubramanian"
venue: "AISTATS 2022"
date: 2022-01-01
picurl: "http://example.com"
codeurl: "https://github.com/Piyushi-0/SEA-NN"
pdfurl: "https://arxiv.org/pdf/2104.09073.pdf" 
layout: paper
--- 
This work explores the novel idea of learning a submodular scoring function to improve the specificity/selectivity of existing feature attribution methods. Submodular scores are natural for attribution as they are known to accurately model the principle of diminishing returns. A new formulation for learning a deep submodular set function that is consistent with the real-valued attribution maps obtained by existing attribution methods is proposed. The final attribution value of a feature is then defined as the marginal gain in the induced submodular score of the feature in the context of other highly attributed features, thus decreasing the attribution of redundant yet discriminatory features. Experiments on multiple datasets illustrate that the proposed attribution method achieves higher specificity along with good discriminative power. The implementation of our method is publicly available at this [https URL](https://github.com/Piyushi-0/SEA-NN).

