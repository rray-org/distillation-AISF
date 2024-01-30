# Goal misgeneralisation

original: https://course.aisafetyfundamentals.com/alignment?session=3

Even without knowing which goals an agent will learn, we can predict some properties of its behavior which would be incentivized under many different goals.

​

Even without reward misspecification, the rewards used during training don’t allow us to control how agents generalize to new situations. This week we cover the scenarios in which agents in new situations generalize to behaving in competent yet undesirable ways because of learning the wrong goals from previous training: the problem of goal misgeneralisation.

The first two readings define and characterize goal misgeneralisation (also known as inner misalignment in the alignment field). Note that goal misgeneralisation and inner misalignment are roughly equivalent concepts, even though they are defined in slightly different ways. Goal misgeneralisation is defined in terms of behaviour in novel situations, while inner misalignment is defined in terms of the representations learned during training.

The following two readings explore specific hypotheses about how agents which have learned the wrong goals will behave: deceptively gaining high reward, and seeking power on a larger scale.

We then finish with two readings on how these behaviours could lead to catastrophe.

By the end of the session, you should be able to:
Understand the concept of internally-represented goals, and evaluate how policies might learn the 'wrong goals'.
Define goal misgeneralisation.
Consider the inner misalignment framework [note, not a definition but is a term that's used in the alignment field.].
Explore the extent to which adversarial training mitigates goal misgeneralisation, and evaluate whether it's a complete solution to the goal misgeneralisation problem.
Understand the concept of deception and the extent of its relation to goal misgeneralisation.
Understand that 'situational awareness' is necessary to cast bad behaviour in terms of 'maximising the reward signal'.
(Without situational awareness, bad behaviour is just bad generalisation. With it, you could interpret the system as trying to manipulate the environment instrumentally towards maximising reward.)

1. [Goal Misgeneralisation: Why Correct Specifications Aren’t Enough For Correct Goals by Rohin Shah (2022)](https://github.com/rray-org/distillation-AISF/blob/main/Week_3/Goal%20Misgeneralisation%20Why%20Correct%20Specifications.md)
2. [Goal Misgeneralization: Why Correct Specifications Aren’t Enough For Correct Goals by Rohin Shah and Vikrant Varma (2022)](https://arxiv.org/abs/2210.01790)
3. [Thought experiments provide a third anchor by Jacob Steinhardt (2022)](https://github.com/rray-org/distillation-AISF/blob/main/Week_3/Thought%20experiments%20provide%20a%20third%20anchor.md)
4. [ML Systems Will Have Weird Failure Modes by Jacob Steinhardt (2022)](https://bounded-regret.ghost.io/ml-systems-will-have-weird-failure-modes-2/)
5. [The alignment problem from a deep learning perspective by Richard Ngo, Soeren Mindermann and Lawrence Chan (2022)](https://arxiv.org/abs/2209.00626)
6. [What failure looks like by Paul Christiano (2019)](https://github.com/rray-org/distillation-AISF/blob/main/Week_3/What%20failure%20looks%20like.md)
