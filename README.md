The inherent "statelessness" of Large Language Models (LLMs), where each API call operates in isolation, presents a significant obstacle in developing truly sophisticated multi-turn agents. Unlike humans, who seamlessly integrate prior knowledge, experiences, and learned skills into new tasks, LLMs must be augmented with mechanisms to overcome this limitation. This notebook explores a practical approach to imbue LLM agents with more robust cognitive capabilities by modeling key aspects of human memory. We will focus on the design and implementation of a simple Retrieval-Augmented Generation (RAG) agent that incorporates four distinct memory paradigms: Working Memory (for immediate context), Episodic Memory (for historical experience), Semantic Memory (for factual grounding), and Procedural Memory (for interaction rules). Through this exploration, we aim to provide a foundational understanding of how to architect memory and recall mechanisms within agentic systems.


Citations
- Adam Lucek
- Types of memory by Psychology Today
- Cognitive Architectures for Language Agents - https://arxiv.org/pdf/2309.02427
