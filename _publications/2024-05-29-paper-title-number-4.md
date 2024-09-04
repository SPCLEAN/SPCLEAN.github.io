---
title: "A numerical algorithm with linear complexity for Multi-marginal Optimal Transport with L1 Cost"
collection: publications
permalink: /publication/2024-05-29-paper-title-number-4
excerpt: 'Numerically solving multi-marginal optimal transport (MMOT) problems is computationally prohibitive, even for moderate-scale instances involving l larger than 4 marginals with support sizes of N larger than 1000.'
date: 2024-05-29
venue: 'Submitted to CSIAM Transactions on Applied Mathmatics'
paperurl: 'https://arxiv.org/pdf/2405.19246'
citation: 'C. Chen, J. Chen, B. Luo, S. Jin and H. Wu. &quot; A numerical algorithm with linear complexity for Multi-marginal Optimal Transport with L1 Cost.&quot; <i>arXiv preprint arXiv:2405.19246 (2024)</i>.'
---

Numerically solving multi-marginal optimal transport (MMOT) problems is computationally prohibitive, even for moderate-scale instances involving l≥4 marginals with support sizes of N≥1000. The cost in MMOT is represented as a tensor with Nl elements. Even accessing each element once incurs a significant computational burden. In fact, many algorithms require direct computation of tensor-vector products, leading to a computational complexity of O(Nl) or beyond. In this paper, inspired by our previous work [Comm. Math. Sci., 20 (2022), pp. 2053 - 2057], we observe that the costly tensor-vector products in the Sinkhorn Algorithm can be computed with a recursive process by separating summations and dynamic programming. Based on this idea, we propose a fast tensor-vector product algorithm to solve the MMOT problem with L1 cost, achieving a miraculous reduction in the computational cost of the entropy regularized solution to O(N). Numerical experiment results confirm such high performance of this novel method which can be several orders of magnitude faster than the original Sinkhorn algorithm.
