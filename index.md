# Interpretable Strategy Synthesis for Competitive Games

## Administrivia

- **Date**: July 16, 2024
- **Time**: 3:00 - 5:00pm EST
- **Venue**: Fully remote
- **Zoom**: [Zoom](https://ncsu.zoom.us/j/98794358822?pwd=dTlCE9caLBulGi7XiFU2F6pdmE6hHi.1)

## Research Theme

Competitive games admit a wide variety of player strategies and emergent, domain-specific concepts that are not
obvious from mere examination of their rules. An example is the _fork_ in chess, where observing the pattern of
a piece attacking two other pieces provides useful information regarding which move ought to be played. Expert
agents trained on these games exhibit many useful strategies in their gameplay, but these are difficult for human
players to understand and adopt. Algorithmically generating _explanations_ for these AI learned strategies
could help human players become more competent in the game, improving their decision-making and leading to more
victories.

In this document, I propose to investigate approaches to the problem of _interpretable strategy synthesis_
i.e., the problem of finding algorithmic approaches to learning useful strategies for games that can be understood
and applied by a human player. In preliminary work, I was able to formally define the problem of interpretable
strategy synthesis and propose a unified framework for describing the problem, along with situating extant works in
that framework. I was also able to use the framework to learn strategies for chess. I was able to connect the problem
of program synthesis to the problem of interpretable strategy synthesis, and was able to use a decision transformer
to synthesize programmatic strategies. My hypothesis is that different game domains will require domain-specific strategy representations in
order to improve their in-game effectiveness and interpretability for a human player.

The work proposed in this dissertation will benefit the esports analytics industry by providing an additional,
powerful tool to gain insight into player strategies. It will also benefit explainable RL (XRL) research by
contributing an additional technique to explain the behavior of RL agents.


## Findings

1. Towards Action Model Learning for Player Modeling. ([link](https://www.aaai.org/ojs/index.php/AIIDE/article/view/7436), [paper](https://abhijeetkrishnan.me/assets/docs/AML_for_Player_Modeling.pdf), [code](https://github.com/AbhijeetKrishnan/aml-for-player-modeling), [video](https://youtu.be/N2rfOBfT-ZE))
2. Towards the Automatic Synthesis of Interpretable Chess Tactics. ([link](https://sites.google.com/view/eaai-ws-2022/program), [paper](https://abhijeetkrishnan.me/assets/docs/Interpretable_Chess_Tactics.pdf), [slides](https://abhijeetkrishnan.me/assets/docs/EAAI_22_Presentation.pdf), [code](https://github.com/AbhijeetKrishnan/tactics))
3. Synthesizing Chess Tactics from Player Games. ([link](https://skatgame.net/mburo/aiide22ws/), [paper](https://abhijeetkrishnan.me/assets/docs/AIIDE_22_Paper_Synthesizing_Chess_Tactics_from_Player_Games.pdf), [slides](https://abhijeetkrishnan.me/assets/docs/AIIDE_22_SG_Presentation.pdf), [code](https://github.com/AbhijeetKrishnan/interpretable-chess-tactics/releases/tag/v1.0))
4. Learning Explainable Representations of Complex Game-playing Strategies. ([paper](https://abhijeetkrishnan.me/assets/docs/ACS_2024_Learning_Explainable_Representations_Of_Complex_Game-Playing_Strategies.pdf), [code](https://github.com/AbhijeetKrishnan/decision-transformer), [poster]((https://abhijeetkrishnan.me/assets/docs/ACS_2024_Poster.pdf))

## Committee
- **Co-Chair:** [Dr. Arnav Jhala](https://www.csc.ncsu.edu/people/ahjhala)
- **Co-Chair:** [Dr. Chris Martens](https://www.convivial.tools/)
- **Member 1:** [Dr. James Lester](https://www.intellimedia.ncsu.edu/people/lester/)
- **Member 2 (GSR):** [Dr. Jonathan Stallrich](https://jonstallrich.com/)

## Document

- [version 0 (2024-06-17)](/defense/AbhijeetKrishnan-thesis-v0.pdf)

## Slides

_coming soon..._