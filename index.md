# Interpretable Strategy Synthesis for Competitive Games

## Administrivia

- **Date**: July 16, 2024
- **Time**: 3:00 - 5:00pm EST
- **Venue**: Fully remote
- **Zoom**: [Zoom](https://ncsu.zoom.us/j/98794358822?pwd=dTlCE9caLBulGi7XiFU2F6pdmE6hHi.1)

## Research Theme

Competitive games admit a wide variety of player strategies and emergent, domain-specific concepts that are not obvious
from mere examination of their rules. Independently developing useful strategies requires expertise and time, which not
all players have access to. Algorithmically generating strategies that players can understand could help them become
more competent, improving their decision-making and leading to better performance. This thesis describes algorithmic
approaches to the problem of _interpretable strategy synthesis_ -- modelling and learning strategies for games that are
both effective and understandable to a human player.

The thesis begins by formalizing this problem in the context of reinforcement learning, as that of finding a policy for
a game-based environment that achieves high reward while being _interpretable_ by a human player. This problem
formulation is applied to the game of chess to develop a first-order logic-based policy model inspired by the documented
concept of _chess tactics_. Two novel metrics - coverage and divergence, are introduced to evaluate the performance of
learned chess strategies. Existing chess tactics are translated into this policy model and evaluated, with the results
showing that they are effective at capturing the behavior of beginner players, but not expert ones. I then introduce a
learning algorithm based on inductive logic programming to automatically learn strategies for chess in the form of the
previously introduced logic-based policy model. The learned strategies are evaluated using the coverage and divergence
metrics, and the results show that the learned strategies are better at approximating human beginners than a random
baseline. I build on this work by introducing two additional constraints based on precision and recall that measurably
improve the performance of the learned tactics. Finally, I introduce another approach to interpretable strategy
synthesis that models a strategy as a programmatic policy, and learns it using the decision transformer model. I apply
this approach to tasks in the Karel programming environment and show that the learned strategies are competitive with
those learned by a state-of-the-art approach, while being significantly more sample efficient.

This thesis contributes algorithmic techniques to model and learn policies for games that are both interpretable, and
effective. An evaluation of the strategies learned by these approaches finds that their performance outperforms
comparable baselines. I expect these techniques to be useful for esports analytics in a variety of game domains. More
generally, I also expect that these techniques will be useful for generating explanations of artificial agent behavior
in reinforcement learning tasks, increasing trust and verifiability of these systems.

## Findings

1. Towards Action Model Learning for Player Modeling. ([link](https://www.aaai.org/ojs/index.php/AIIDE/article/view/7436), [paper](https://abhijeetkrishnan.me/assets/docs/AML_for_Player_Modeling.pdf), [code](https://github.com/AbhijeetKrishnan/aml-for-player-modeling), [video](https://youtu.be/N2rfOBfT-ZE))
2. Towards the Automatic Synthesis of Interpretable Chess Tactics. ([link](https://sites.google.com/view/eaai-ws-2022/program), [paper](https://abhijeetkrishnan.me/assets/docs/Interpretable_Chess_Tactics.pdf), [slides](https://abhijeetkrishnan.me/assets/docs/EAAI_22_Presentation.pdf), [code](https://github.com/AbhijeetKrishnan/tactics))
3. Synthesizing Chess Tactics from Player Games. ([link](https://skatgame.net/mburo/aiide22ws/), [paper](https://abhijeetkrishnan.me/assets/docs/AIIDE_22_Paper_Synthesizing_Chess_Tactics_from_Player_Games.pdf), [slides](https://abhijeetkrishnan.me/assets/docs/AIIDE_22_SG_Presentation.pdf), [code](https://github.com/AbhijeetKrishnan/interpretable-chess-tactics/releases/tag/v1.0))
4. Learning Explainable Representations of Complex Game-playing Strategies. ([paper](https://abhijeetkrishnan.me/assets/docs/ACS_2024_Learning_Explainable_Representations_Of_Complex_Game-Playing_Strategies.pdf), [code](https://github.com/AbhijeetKrishnan/decision-transformer), [poster](https://abhijeetkrishnan.me/assets/docs/ACS_2024_Poster.pdf))

## Committee
- **Co-Chair:** [Dr. Arnav Jhala](https://www.csc.ncsu.edu/people/ahjhala)
- **Co-Chair:** [Dr. Chris Martens](https://www.convivial.tools/)
- **Member 1:** [Dr. James Lester](https://www.intellimedia.ncsu.edu/people/lester/)
- **Member 2 (GSR):** [Dr. Jonathan Stallrich](https://jonstallrich.com/)

## Document

- [version 0 (2024-06-17)](/defense/AbhijeetKrishnan-thesis-v0.pdf)

## Slides

_coming soon..._
