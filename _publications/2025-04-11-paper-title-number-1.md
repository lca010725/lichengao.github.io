---
title: "Controlling large language models through concept activation vectors"
collection: publications
category: conferences
permalink: /publication/2025-04-11-paper-title-number-1
excerpt: 'Hanyu Zhang, Xiting Wang*, **Chengao Li**, Xiang Ao, Qing He*.'
date: 2025-04-11
venue: 'Proceedings of the 39th Annual AAAI Conference on Artificial Intelligence (AAAI 2025)'
# slidesurl: 'https://lichengao.github.io/files/slides1.pdf'
paperurl: 'https://lca010725.github.io/files/AAAI2025_paper.pdf'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
citation: 'Zhang, H., Wang, X., Li, C., Ao, X., & He, Q. (2025). Controlling Large Language Models Through Concept Activation Vectors. Proceedings of the AAAI Conference on Artificial Intelligence, 39(24), 25851-25859.'
---

`Abstract` As large language models (LLMs) are widely deployed across various domains, the ability to control their generated outputs has become more critical. This control involves aligning LLMs outputs with human values and ethical principles or
customizing LLMs on specific topics or styles for individual users. Existing controlled generation methods either require significant computational resources and extensive trial-and-error or provide coarse-grained control. In this paper, we
propose Generation with Concept Activation Vector (GCAV),a lightweight model control framework that ensures accurate control without requiring resource-extensive fine-tuning. Specifically, GCAV first trains a concept activation vector for specified concepts to be controlled, such as toxicity. During inference, GCAV steers the concept vector in LLMs, for example, by removing the toxicity concept vector from the activation layers. Control experiments from different perspectives, including toxicity reduction, sentiment control, linguistic style, and topic control, demonstrate that our framework achieves state-of-the-art performance with granular control, allowing for fine-grained adjustments of both the steering layers and the steering magnitudes for individual samples.
