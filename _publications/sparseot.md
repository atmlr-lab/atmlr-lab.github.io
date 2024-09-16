---
title: "Submodular Framework for Structured-Sparse Optimal Transport"
authors: "Piyushi Manupriya, Pratik Jawanpuria, Karthik S. Gurumoorthy, SakethaNath Jagarlapudi, Bamdev Mishra"
venue: "ICML 2024"
date: 2024-05-01
picurl: "http://example.com"
codeurl: "http://github.com/atmlr-lab/sparse-uot"
pdfurl: "https://arxiv.org/pdf/2406.04914" 
layout: paper
--- 
Unbalanced optimal transport (UOT) has recently gained much attention due to its flexible framework for handling un-normalized measures and its robustness properties. In this work, we explore learning (structured) sparse transport plans in the UOT setting, i.e., transport plans have an upper bound on the number of non-sparse entries in each column (structured sparse pattern) or in the whole plan (general sparse pattern). We propose novel sparsity-constrained UOT formulations building on the recently explored maximum mean discrepancy based UOT. We show that the proposed optimization problem is equivalent to the maximization of a weakly submodular function over a uniform matroid or a partition matroid. We develop efficient gradient-based discrete greedy algorithms and provide the corresponding theoretical guarantees. Empirically, we observe that our proposed greedy algorithms select a diverse support set and we illustrate the efficacy of the proposed approach in various applications.
