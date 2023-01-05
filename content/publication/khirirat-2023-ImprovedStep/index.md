---
title: "Improved Step-Size Schedules for Proximal Noisy Gradient Methods"
date: 2023-01-01
authors: ["Sarit Khirirat"]
publication_types: ["1"]
abstract: "Noisy gradient algorithms have emerged as one of the most popular algorithms for distributed optimization with massive data. Choosing proper step-size schedules is an important task to tune in the algorithms for good performance. For the algorithms to attain fast convergence and high accuracy, it is intuitive to use large step-sizes in the initial iterations when the gradient noise is typically small compared to the algorithm-steps, and reduce the step-sizes as the algorithm progresses. This intuition has been confirmed in theory and practice for stochastic gradient descent. However, similar results are lacking for other methods using approximate gradients. This paper shows that the diminishing step-size strategies can  indeed be applied for a broad class of noisy gradient algorithms. Our analysis framework is based on two classes of systems that characterize the impact of the step-sizes on the convergence performance  of many algorithms. Our results show that such step-size schedules enable  these  algorithms to enjoy the optimal rate. We exemplify our results on stochastic compression algorithms. Our experiments validate fast convergence of these algorithms with the step decay schedules."
featured: true
publication: "*IEEE Transactions on Signal Processing (Accepted) 2023*"
---

