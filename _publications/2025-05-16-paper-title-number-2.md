---
title: "Gradient-Adaptive Policy Optimization: Towards Multi-Objective Alignment of Large Language Models"
collection: publications
category: conferences
permalink: /publication/2025-05-16-paper-title-number-2
excerpt: '**Chengao Li**, Hanyu Zhang, Yunkun Xu, Hongyan Xue, Xiang Ao*, and Qing He*.'
date: 2025-05-16
venue: 'Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025)'
# slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://lca010725.github.io/files/ACL2025_paper.pdf'
citation: 'Chengao Li, Hanyu Zhang, Yunkun Xu, Hongyan Xue, Xiang Ao, and Qing He. 2025. Gradient-Adaptive Policy Optimization: Towards Multi-Objective Alignment of Large Language Models. In Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers), pages 11214–11232, Vienna, Austria. Association for Computational Linguistics.'
---

`Abstract` As large language models (LLMs) are widely deployed across various domains, the ability to control their generated outputs has become more critical. This control involves aligning LLMs outputs with human values and ethical principles or
customizing LLMs on specific topics or styles for individual users. Existing controlled generation methods either require significant computational resources and extensive trial-and-error or provide coarse-grained control. In this paper, we
propose Generation with Concept Activation Vector (GCAV),a lightweight model control framework that ensures accurate control without requiring resource-extensive fine-tuning. Specifically, GCAV first trains a concept activation vector for specified concepts to be controlled, such as toxicity. During inference, GCAV steers the concept vector in LLMs, for example, by removing the toxicity concept vector from the activation layers. Control experiments from different perspectives, including toxicity reduction, sentiment control, linguistic style, and topic control, demonstrate that our framework achieves state-of-the-art performance with granular control, allowing for fine-grained adjustments of both the steering layers and the steering magnitudes for individual samples.
