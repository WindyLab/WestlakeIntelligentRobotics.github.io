---
title: "Multi-Agent Consensus Seeking via Large Language Models"
collection: publications
permalink: /ConsensusLLM
link: https://westlakeintelligentrobotics.github.io/ConsensusLLM
GitHub: 'https://github.com/WestlakeIntelligentRobotics/ConsensusLLM-code'
Website: 'https://westlakeintelligentrobotics.github.io/ConsensusLLM/'
excerpt: 'This work explores LLM-driven multi-agent consensus seeking, uncovering a preference for average strategies and the influence of agent personalities and network topologies, with implications for multi-robot aggregation and complex task understanding.'
---

Multi-agent systems driven by large language models (LLMs) have shown promising abilities for solving complex tasks in a collaborative manner. This work considers a fundamental problem in multi-agent collaboration: *consensus seeking*. In particular, when multiple agents work together, we are interested in how they can reach a consensus through inter-agent negotiation given that they have different initial solutions for a task. To that end, this work studies an abstract consensus-seeking task, where the state of each agent is a numerical number and they negotiate with each other to reach a consensus value. We found that when not explicitly directed on which strategy should be adopted, the LLM-driven agents tend to use the *average strategy* for consensus seeking although they may also use some other strategies occasionally. Moreover, this work analyzes the impact of agents' *personalities* and *network topologies* on the negotiation process. It is shown that stubborn agents tend to dominate the consensus outcome, resulting in leader-follower structures, while network topologies can influence the speed and success of consensus convergence. Moreover, LLM-driven consensus seeking is applied as a planner to achieve multi-robot aggregation in the plane.The significance of this work lies in its potential to lay the foundations for understanding the behaviors of LLM-driven multi-agent systems to reach consensus in more complex tasks.

**GitHub Repository** [View on GitHub](<https://github.com/WestlakeIntelligentRobotics/ConsensusLLM-code>)
