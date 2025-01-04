---
title: "How to Make Private Distributed Cardinality Estimation Practical, and Get Differential Privacy for Free [Usenix Security ’21]"
date: 2021-06-21
time: 2PM
presenter: "changyu-dong"
youtube: "6LeyOF4iiQ8"
zoom-link: "https://newcastleuniversity.zoom.us/j/83265933720?pwd%3DZjVuTnUycEJJYk9Ra2tvNkk3R2x4QT09"
zoom-id: 
zoom-password: 
---

Secure computation is a promising privacy enhancing technology, but it is often not scalable enough for data intensive applications. On the other hand, the use of sketches has gained popularity in data mining, because sketches often give rise to highly efficient and scalable sub-linear algorithms. It is natural to ask: what if we put secure computation and sketches together? We investigated the question and the findings are interesting: we can get security, we can get scalability, and somewhat unexpectedly, we can also get differential privacy — for free. Our study started from building a secure computation protocol based on the Flajolet-Martin (FM) sketches, for solving the Private Distributed Cardinality Estimation (PDCE) problem, which is a fundamental problem with applications ranging from crowd tracking to network monitoring. The state of art protocol for PDCE is computationally expensive and not scalable enough to cope with big data applications, which prompted us to design a better protocol. Our further analysis revealed that if the cardinality to be estimated is large enough, our protocol can achieve (\epsilon,\delta)-differential privacy automatically, without requiring any additional manipulation of the output. The result signifies a new approach for achieving differential privacy that departs from the mainstream approach (i.e. adding noise to the result). Free differential privacy can be achieved because of two reasons: secure computation minimizes information leakage, and the intrinsic estimation variance of the FM sketch makes the output of our protocol uncertain. We further show that the result is not just theoretical: the minimal cardinality for differential privacy to hold is only 10^2−10^4 for typical parameters.
