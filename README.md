# How far are we from a lifelong game agent?

Technical report by Hao Chen (haochen2115@gmail.com), October 2026.

Read it at **https://haochen2115.github.io/nthgame-report/** ([中文版](https://haochen2115.github.io/nthgame-report/zh.html)).

A self-programming agent built on a frozen vision-language model plays ten browser games from
[GameWorld](https://arxiv.org/abs/2604.07429). It learns each game by writing its own code, but what it
learns is either anchored to the pixels it has seen or restates what the model already knows: experience gives a
small constant benefit across games, stops helping as soon as the screen changes, and does not transfer across
Pokémon generations either. Revised 2026-10-20; see Appendix A.4 of the report for corrections.

Game screenshots belong to their respective owners and are shown for research illustration only.
