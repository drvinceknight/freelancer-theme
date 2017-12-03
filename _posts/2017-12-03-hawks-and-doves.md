---
layout: default
modal-id: 1
date: 2017-12-03
img: playing-games.png
alt: "An activity looking at the mathematics of evolution"
---

- [Slides]({{site.baseurl}}/assets/hawks-and-doves/tex/main.pdf)
- [Notebook]({{site.baseurl}}/assets/hawks-and-doves/nbs/main.ipynb)

This activity is intended for later high school years and introduces students to
the mathematics behind evolution. In particular using probability and Moran
processes.

1. Describe the Moran process image on the slides;
2. Ask for an explanation about the equations.
3. Ask what might be wrong about this assumption? (In particular that all
   individuals have "the same fitness").
4. Show the Hawk Dove game and discuss.
5. Create groups of 4 and explain that we will simulate the Moran process.
6. Discuss the probabilities that might occur and how to simulate these using
   the dice available.
   1. If 1 Hawk:
      - Hawk gets 9 (3 x 3)
      - Each dove gets 5 (1 x 1 + 2 x 2)
      - Total score is 24.
      - Assign numbers to each individual (roll dice)
   2. If 2 Hawk:
      - Hawks each gets 6 (1 x 0 + 3 x 2)
      - Each dove gets 4 (1 x 2 + 2 x 1))
      - Total score is 20.
      - Assign numbers to each individual (roll dice)
   3. If 3 Hawk:
      - Hawks each gets 3 (1 x 3 + 3 x 0)
      - Each dove gets 3 (0 x 2 + 3 x 1))
      - Total score is 12.
      - Assign numbers to each individual (roll dice)
7. Get students to repeat 10 times and check probability of Hawk taking over.
8. Put probabilities together.
9. Discuss slide that shows theoretic probability (without going in to details).
10. Show computer simulation.
