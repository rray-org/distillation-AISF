# Adversarial techniques for scalable oversight

original: https://course.aisafetyfundamentals.com/alignment?session=5

We can train models to tell us when other models are making mistakes - but right now they're not always able to explain how they know that the mistakes are happening.

​

This week focuses on two more potential alignment techniques proposed to work at scale: debate and training using unrestricted adversarial examples.

The initial readings focus on practical and theoretical aspects of debate. The next two readings explore how to generate inputs on which AIs misbehave. Although there is a large literature on adversarial examples (inputs which cause misbehaviour despite being very similar to training examples), we focus on the general case of inputs which cause misbehaviour without necessarily being close to training inputs (known as unrestricted adversarial examples).

Note that although these techniques don’t rely on the task decomposability assumption required for iterated amplificiation, they rely on different strong assumptions. For debate, the assumption is that truthful arguments are more persuasive. For unrestricted adversarial training, the assumption is that adversaries can generate realistic inputs even on complex real-world tasks. The first further reading on each technique explores some problems with these assumptions and potential solutions. The first assumption can be operationalized in terms of a discriminator-critique gap and the second in terms of a generator-discriminator gap (both of which are discussed in the full version of Saunders et al.’s (2022) critiques paper).

By the end of the session, you should be able to:
Understand the debate framework.
Using AI to critique AI decisions, to help humans give feedback when they can't grasp the whole task.
Understand the assumptions it depends on.
Understand unrestricted adversarial training framework.
A means of using AI to provide oversight during training.
Understand the assumptions it depends on.

1. AI-written critiques help humans notice flaws: blog post by Jan Leike, Jeffrey Wu, Catherine Yeh et al. (2022)
2. AI safety via debate by Geoffrey Irving, Paul Christiano and Dario Amodei (2018)
3. [Red-teaming language models with language models by Ethan Perez, Saffron Huang, Francis Song et al. (2022)](https://github.com/rray-org/distillation-AISF/blob/main/Week_5/Red-teaming%20language%20models%20with%20language%20models.md)
4. Robust Feature-Level Adversaries are Interpretability Tools by Casper (2021)
