---
title: "First-Order Algorithms for Communication Efficient Distributed Learning"
date: 2019-10-06
authors: ["Sarit Khirirat"]
publication_types: ["1"]
abstract: "Technological developments in devices and storages have made large volumes of data collections more accessible than ever. This transformation leads to optimization problems with massive data in both volume and dimension. In response to this trend, the popularity of optimization on high performance computing architectures has increased unprecedentedly. These scalable optimization solvers can achieve high efficiency by splitting computational loads among multiple machines. However, these methods also incur large communication overhead. To solve optimization problems with millions of parameters, communication between machines has been reported to consume up to 80% of the training time. To alleviate this communication bottleneck, many optimization algorithms with data compression techniques have been studied. In practice, they have been reported to significantly save communication costs while exhibiting almost comparable convergence as the full-precision algorithms. To understand this intuition, we develop theory and techniques in this thesis to design communication-efficient optimization algorithms.

In the first part, we analyze the convergence of optimization algorithms with direct compression. First, we outline definitions of compression techniques which cover many compressors of practical interest. Then, we provide the unified analysis framework of optimization algorithms with compressors which can be either deterministic or randomized. In particular, we show how the tuning parameters of compressed optimization algorithms must be chosen to guarantee performance. Our results show explicit dependency on compression accuracy and delay effect due to asynchrony of algorithms. This allows us to characterize the trade-off between iteration and communication complexity under gradient compression.

In the second part, we study how error compensation schemes can improve the performance of compressed optimization algorithms. Even though convergence guarantees of optimization algorithms with error compensation have been established, there is very limited theoretical support which guarantees improved solution accuracy. We therefore develop theoretical explanations, which show that error compensation guarantees arbitrarily high solution accuracy from compressed information. In particular, error compensation helps remove accumulated compression errors, thus improving solution accuracy especially for ill-conditioned problems. We also provide strong convergence analysis of error compensation on parallel stochastic gradient descent across multiple machines. In particular, the error-compensated algorithms, unlike direct compression, result in significant reduction in the compression error.

Applications of the algorithms in this thesis to real-world problems with benchmark data sets validate our theoretical results."
featured: true
publication: "*Licentiate Thesis:: Stockholm: KTH Royal Institute of Technology, 2019. , p. 106*"
---

