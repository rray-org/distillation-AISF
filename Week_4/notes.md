# Task decomposition for scalable oversight

original: https://course.aisafetyfundamentals.com/alignment?session=4

You can significantly improve the performance of language models on tricky tasks by asking them to break down the problem in the right way.

​

This week introduces scalable oversight as an approach to preventing reward misspecification, and discusses one scalable oversight proposal: iterated amplification.

Scalable oversight refers to methods that enable humans to oversee AI systems that are solving tasks too complicated for a single human to evaluate. This week begins by justifying the problem of scalable oversight; we then examine iterated amplification as a potential solution to the problem. Iterated amplification is built around task decomposition: the strategy of training agents to perform well on complex tasks by decomposing them into smaller tasks which can be more easily evaluated and then combining those solutions to produce answers to the full task. Iterated amplification involves repeatedly using task decomposition to train increasingly powerful agents.

We'll examine two other alignment techniques that could work at scale next week.

By the end of the session, you should be able to:
Explain the basic concept of scalable oversight.
Understand the concept of iterated amplification as a means of achieving scalable oversight.
Understand task decomposition as a component of iterated amplification using two experimental setups in the curriculum as examples.
Understand the assumptions that iterated amplification relies on to work to train aligned, powerful agents.
Explain how it helps, the evidence that it works, and its limitations.

1. [AI Alignment Landscape by Paul Christiano (2020)](https://github.com/rray-org/distillation-AISF/blob/main/Week_4/AI%20Alignment%20Landscape.md)
2. [Measuring Progress on Scalable Oversight for Large Language Models by Samuel Bowman (2022)](https://github.com/rray-org/distillation-AISF/blob/main/Week_4/Measuring%20Progress%20on%20Scalable%20Oversight%20for%20Large.md)
3. [Learning Complex Goals with Iterated Amplification by Paul Christiano and Dario Amodei (2018)](https://github.com/rray-org/distillation-AISF/blob/main/Week_4/Learning%20Complex%20Goals%20with%20Iterated%20Amplification.md)
4. [Supervising strong learners by amplifying weak experts by Paul Christiano, Dario Amodei and Buck Shlegeris (2018)](https://arxiv.org/abs/1810.08575)
5. [Summarizing Books with Human Feedback by Jeffrey Wu, Ryan Lowe and Jan Leike (2021)](https://github.com/rray-org/distillation-AISF/blob/main/Week_4/Summarizing%20Books%20with%20Human%20Feedback.md)
6. [Language Models Perform Reasoning via Chain of Thought by Jason Wei, Denny Zhou and Google (2022)](https://github.com/rray-org/distillation-AISF/blob/main/Week_4/Language%20Models%20Perform%20Reasoning%20via%20Chain%20of%20Tho.md)
7. [Least-to-Most Prompting Enables Complex Reasoning in Large Language Models by Denny Zhou, Nathanael Scharli, Le Hou et al. (2022)](https://github.com/rray-org/distillation-AISF/blob/main/Week_4/Least-to-Most%20Prompting%20Enables%20Complex%20Reasoning.md
