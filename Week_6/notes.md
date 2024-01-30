# Interpretability

original: https://course.aisafetyfundamentals.com/alignment?session=6

By studying the connections between neurons, we can find meaningful algorithms in the weights of neural networks.

​

Our current methods of training capable neural networks give us little insight into how or why they function. This week we cover the field of interpretability, which aims to change this by developing methods for understanding how neural networks think.

In some sense, the core alignment problem stems from the fact that we don't know what our networks actually learn. If interpretability research succeeds, we'll have a better understanding of what our networks are doing and how to change it.

This week’s curriculum starts with readings related to mechanistic interpretability. Mechanistic interpretability is a subfield of interpretability which aims to understand networks on the level of individual neurons. After understanding neurons, we can identify how they construct increasingly complex representations, and develop a bottom-up understanding of how neural networks work.

It then moves onto an area we refer to as concept-based interpretability which focuses on techniques for automatically probing (and potentially modifying) human-interpretable concepts stored in representations within neural networks. (Note, this isn't a widely-used term in the field, but is used for the purposes of this curriculum for now).

By the end of the session, you should be able to:
Understand the distinction between mechanistic and concept-based interpretability.
Define mechanistic interpretability
Explain how circuits are found.
Understand the circuits hypothesis (3 claims in the introduction to circuits post).
Explain the concept of superposition and how superpositions are found.
Define conceptual interpretability.
Explain how probes work.
(For more advanced readers) Explain how probes can be used to improve model outputs, e.g. in the Burns paper.
Identify the pros and cons of each approach, in order to speculate about how mechanistic interpretability may or may not generalise to more abstract concepts.

1. [Zoom In: An Introduction to Circuits by Chris Olah, Nick Cammarata, Ludwig Schubert et al. (2020)](https://distill.pub/2020/circuits/zoom-in/)
2. [Toy models of superposition by Nelson Elhage, Tristan Hume, Catherine Olsson et al. (2022)](https://transformer-circuits.pub/2022/toy_model/index.html)
3. [Understanding intermediate layers using linear classifier probes by Guillaume Alain and Yoshua Bengio (2016)](https://arxiv.org/abs/1610.01644)
4. [Discovering language model behaviors with model-written evaluations: blog post by Ethan Perez (2022)](https://www.alignmentforum.org/posts/yRAo2KEGWenKYZG9K/discovering-language-model-behaviors-with-model-written)
5. [Locating and Editing Factual Associations in GPT by Kevin Meng, David Bau, Alex Andonian et al. (2022)](https://rome.baulab.info/)
