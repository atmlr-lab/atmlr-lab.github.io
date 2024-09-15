---
title: "Consistent Optimal Transport with Empirical Conditional Measures"
authors: "Piyushi Manupriya, Rachit Keerti Das, Sayantan Biswas, SakethaNath Jagarlapudi"
venue: "AISTATS 2024"
date: 2024-01-20
picurl: "http://example.com"
codeurl: "http://github.com/atmlr-lab/COT"
pdfurl: "https://arxiv.org/pdf/2305.15901.pdf" 
layout: default
--- 
Given samples from two joint distributions, we consider the problem of Optimal Transportation (OT) between them when conditioned on a common variable. We focus on the general setting where the conditioned variable may be continuous, and the marginals of this variable in the two joint distributions may not be the same. In such settings, standard OT variants cannot be employed, and novel estimation techniques are necessary. Since the main challenge is that the conditional distributions are not explicitly available, the key idea in our OT formulation is to employ kernelized-least-squares terms computed over the joint samples, which implicitly match the transport plan's marginals with the empirical conditionals. Under mild conditions, we prove that our estimated transport plans, as a function of the conditioned variable, are asymptotically optimal. For finite samples, we show that the deviation in terms of our regularized objective is bounded by O(1/m1/4), where m is the number of samples. We also discuss how the conditional transport plan could be modelled using explicit probabilistic models as well as using implicit generative ones. We empirically verify the consistency of our estimator on synthetic datasets, where the optimal plan is analytically known. When employed in applications like prompt learning for few-shot classification and conditional-generation in the context of predicting cell responses to treatment, our methodology improves upon state-of-the-art methods.
