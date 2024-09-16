---
title: "Statistical Optimal Transport posed as Learning Kernel Embedding"
authors: "SakethaNath Jagarlapudi, Pratik Jawanpuria"
venue: "NeurIPS 2020"
date: 2020-09-01
picurl: "http://example.com"
codeurl: "http://github.com/atmlr-lab/"
pdfurl: "https://arxiv.org/pdf/2002.03179.pdf" 
layout: paper
--- 
The objective in statistical Optimal Transport (OT) is to consistently estimate the optimal transport plan/map solely using samples from the given source and target marginal distributions. This work takes the novel approach of posing statistical OT as that of learning the transport plan's kernel mean embedding from sample based estimates of marginal embeddings. The proposed estimator controls overfitting by employing maximum mean discrepancy based regularization, which is complementary to ϕ-divergence (entropy) based regularization popularly employed in existing estimators. A key result is that, under very mild conditions, ϵ-optimal recovery of the transport plan as well as the Barycentric-projection based transport map is possible with a sample complexity that is completely dimension-free. Moreover, the implicit smoothing in the kernel mean embeddings enables out-of-sample estimation. An appropriate representer theorem is proved leading to a kernelized convex formulation for the estimator, which can then be potentially used to perform OT even in non-standard domains. Empirical results illustrate the efficacy of the proposed approach.
