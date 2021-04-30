---
layout: page
title: Casi di parità
permalink: /it/cubes/4x4_parity
lang: it
---

![4x4_parity-1](/assets/cubes/4x4_parity-1.png)

Raggiunto l'ultimo strato è possibile che si verifichi una situazione in cui il cubo sembra essere non risolvibile. Questi casi non si verificano con il cubo 3x3.

Gli algoritmi descritto sotto permettono di correggere l'orientamento oppure di invertire due pezzi dell'ultimo strato.

# RI-ORIENTARE 2 & 3

**`r2 B2 U2 l – U2 r' U2 r – U2 F2 r F2 – l' B2 r2`**

Lo stesso algoritmo senza mosse "slice":

**`Rw2 R2 B2 U2 – Lw L' U2 Rw' – R U2 Rw R' – U2 F2 Rw R' – F2 Lw' L – B2 Rw2 R2`**

# INVERTIRE 4 & 5

**`Rw2 f2 U2 Fw2 – D Rw2 U2 Fw2 – U’ Fw2 L2 U2 – B2 Lw2 U`**

Lo stesso algoritmo senza mosse "slice":

**`Rw2 Fw2 F2 U2 Fw2 – D Rw2 U2 Fw2 – U’ Fw2 L2 U2 – B2 Lw2 U`**

# INVERTIRE 1 & 4

**`F2 R2 B' - D' B R2 F' U  - Fw2 F L2 - f2 Lw2 - f2 l2 U'`**

Lo stesso algoritmo senza mosse "slice":

**`F2 R2 B' - D' B R2 F' U - Fw2 F L2 - Fw2 F2 Lw2 - Fw2 F2 Lw2 L2 U'`**

***

# Credits

- <https://ruwix.com/twisty-puzzles/4x4x4-rubiks-cube-rubiks-revenge/>

{% include cube_footer.md %}