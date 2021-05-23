---
layout: page
title: Spostare i centri
permalink: /it/cubes/4x4_move_centers
lang: it
---

# <SEZIONE DA VERIFICARE>

# Centri Opposti

Per invertire due centro opposti (fronte e retro) senza muovere gli altri pezzi, si può usare:

`r2 U2 r2 U2 M2 U2 l2 U2 l2`

Alternativa più breve (top & bottom):

`r2 S2 r2 S2`

# Centri Adiacenti

Per invertire 2 centri adiacenti (top & front) si può usare:

`r U2 r' l' U2 l`

*ATTENZIONE: questo algoritmo sposta gli altri pezzi*

Versione front & left:

`u M2 u' L2 F2 u M2 u' M2 F2 LM2`

Versione front & right:

`u M' U2 M u' d' M U2 M' d`

***

# Credits

- <https://puzzling.stackexchange.com/questions/64504/how-to-swap-the-centre-squares-of-a-4x4-rubiks-cube>

{% include cube_footer.md %}