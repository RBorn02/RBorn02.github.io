---
title: "Emergence of Collective Open-Ended Exploration from Decentralized Meta-Reinforcement Learning"
authors: "<strong>Richard Bornemann</strong>, Gautier Hamon, Eleni Nisioti, Clément Moulin-Frier"
venue: "NeurIPS 2023 - 2nd Agent Learning in Open-Endedness Workshop"
year: 2023
image: "/images/explore.png"
url: "https://arxiv.org/abs/2311.00651"
category: "conference"
---

Recent works have proven that intricate cooperative behaviors can emerge in agents trained using meta reinforcement learning on open ended task distributions using self-play. While the results are impressive, we argue that self-play and other centralized training techniques do not accurately reflect how general collective exploration strategies emerge in the natural world: through decentralized training and over an open-ended distribution of tasks. In this work we therefore investigate the emergence of collective exploration strategies, where several agents meta-learn independent recurrent policies on an open ended distribution of tasks. To this end we introduce a novel environment with an open ended procedurally generated task space which dynamically combines multiple subtasks sampled from five diverse task types to form a vast distribution of task trees. We show that decentralized agents trained in our environment exhibit strong generalization abilities when confronted with novel objects at test time. Additionally, despite never being forced to cooperate during training the agents learn collective exploration strategies which allow them to solve novel tasks never encountered during training. We further find that the agents learned collective exploration strategies extend to an open ended task setting, allowing them to solve task trees of twice the depth compared to the ones seen during training. Our open source code as well as videos of the agents can be found on our companion website.