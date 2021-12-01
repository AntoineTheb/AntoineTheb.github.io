---
title: "Track-to-Learn: A general framework for tractography with deep reinforcement learning"
collection: publications
permalink: /publication/2021-01-01-Track-to-Learn-A-general-framework-for-tractography-with-deep-reinforcement-learning
date: 2021-01-01
venue: 'Medical Image Analysis'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S1361841521001390'
citation: ' Antoine Théberge,  Christian Desrosiers,  Maxime Descoteaux,  Pierre-Marc Jodoin, &quot;Track-to-Learn: A general framework for tractography with deep reinforcement learning.&quot; Medical Image Analysis, 2021.'
---

Diffusion MRI tractography is currently the only non-invasive tool able to assess the white-matter structural connectivity of a brain. Since its inception, it has been widely documented that tractography is prone to producing erroneous tracks while missing true positive connections. Recently, supervised learning algorithms have been proposed to learn the tracking procedure implicitly from data, without relying on anatomical priors. However, these methods rely on curated streamlines that are very hard to obtain. To remove the need for such data but still leverage the expressiveness of neural networks, we introduce Track-To-Learn: A general framework to pose tractography as a deep reinforcement learning problem. Deep reinforcement learning is a type of machine learning that does not depend on ground-truth data but rather on the concept of “reward”. We implement and train algorithms to maximize returns from a reward function based on the alignment of streamlines with principal directions extracted from diffusion data. We show competitive results on known data and little loss of performance when generalizing to new, unseen data, compared to prior machine learning-based tractography algorithms. To the best of our knowledge, this is the first successful use of deep reinforcement learning for tractography.



[Access paper here](https://www.sciencedirect.com/science/article/pii/S1361841521001390){:target="_blank"}
