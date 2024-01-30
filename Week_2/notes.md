# Reward misspecification and instrumental convergence

original: https://course.aisafetyfundamentals.com/alignment?session=2

Language models often "hallucinate" realistic false facts. Fine-tuning them using human feedback makes this less common, but also makes the hallucinations harder to distinguish from the truth.

​

This week starts off by focusing on reward misspecification: the phenomenon where our default techniques for training ML models often unintentionally assign high rewards to undesirable behaviour. Behaviour which exploits reward misspecification to get a high reward is known as reward hacking.

This type of alignment failure happens due to our failure to capture our exact desires for the resulting systems' behaviour in the reward function or loss function that we use to train machine learning systems. Failure to solve this problem is an important source of danger from advanced systems if they're built using current-day techniques, which is why we're spending a week on it.

We start by looking at some toy examples when rewards are hard-coded or based on human feedback. We'll then look at two techniques engineers working with foundation models use to overcome reward misspecification in advanced systems: Reinforcement Learning from Human Feedback (RLHF) and Inverse Reinforcement Learning (IRL). We’ll also examine the limitations of these techniques. Note that RLHF is much more of a focus, and the two readings on IRL should only be done after you feel like you understand the rest of the material in this week.

The second key topic this week is instrumental convergence: the idea that AIs pursing a range of different rewards or goals will tend to converge to a set of similar instrumental strategies. Broadly speaking, we can summarize these strategies as aiming to gain power over the world. Instrumental convergence therefore provides a bridge between the narrow examples of reward misspecification we see today, and the possibility of large-scale disempowerment from AI; a reading by Christiano provides an illustration of how this might occur.

By the end of the session, you should be able to:
Explain how reward functions can fall short of specifying our intentions.
Understand what a reward function is and why they're used.
Define the terms 'reward misspecification' and 'reward hacking'.
Examine whether reward hacking could play a part in catastrophic failure in advanced systems.
Explain what RLHF is and why it is proposed as a way to help deal with reward misspecification.
Predict ways in which RLHF could lead to undesirable outcomes, given an arbitrary environment and task.
Understand what IRL is and why it is proposed as a way to help deal with reward misspecification.
Explain why IRL is not typically used to learn human wishes, in modern systems.
List the proposed instrumental goals, and evaluate to what extent it appears to be a reward misspecification problem.

1. [Specification gaming: the flip side of AI ingenuity by Victoria Krakovna, Jonathan Uesato, Vladimir Mikulik et al. (2020)](https://github.com/rray-org/distillation/blob/develop/Week_2/Specification%20gaming%20the%20flip%20side%20of%20AI%20ingenuity.md)
2. [Learning from Human Preferences by Paul Christiano, Alex Ray and Dario Amodei (2017)](https://github.com/rray-org/distillation/blob/develop/Week_2/Learning%20from%20human%20preferences.md)
3. [Learning to Summarize with Human Feedback by Jeffrey Wu, Nisan Stiennon, Daniel Ziegler et al. (2020)](https://github.com/rray-org/distillation/blob/develop/Week_2/Learning%20to%20Summarize%20with%20Human%20Feedback.md)
4. [The alignment problem from a deep learning perspective by Richard Ngo, Soeren Mindermann and Lawrence Chan (2022)](https://github.com/rray-org/distillation/blob/develop/Week_2/The%20alignment%20problem%20from%20a%20deep%20learning%20perspective.md)
5. Optimal Policies Tend To Seek Power by Alex Turner, Logan Smith, Rohin Shah et al. (2021)
6. [What failure looks like by Paul Christiano (2019)](https://github.com/rray-org/distillation/blob/develop/Week_2/What%20failure%20looks%20like.md)
7. [Inverse reinforcement learning example by Udacity (2016)](https://github.com/rray-org/distillation/blob/develop/Week_2/Inverse%20reinforcement%20learning%20example.md)
8. [The easy goal inference problem is still hard by Paul Christiano (2018)](https://github.com/rray-org/distillation/blob/develop/Week_2/The%20easy%20goal%20inference%20problem%20is%20still%20hard.md)
