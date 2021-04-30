---
layout: page
title: Risoluzione 2x2
permalink: /it/cubes/2x2_resolution
lang: it
---

Il cubo 2x2 è in pratica un cubo di Rubik tradizionale senza i pezzi centrali e gli spigoli, ma solo con gli 8 pezzi d'angolo. Se sai [risolvere il cubo di Rubik 3x3](3x3_resolution) allora sai fare anche questo.

Gli unici casi da gestire che non capitano con il cubo 3x3 sono relativi alla necessità di invertire 2 pezzi (angoli) nel secondo strato. Per risolvere questi casi si possono utilizzare gli algoritmi indicati in questa pagina.


# Passi da seguire per la risoluzione

1. Formare **una faccia con la cornice**
2. **Allineare gli angoli** della faccia opposta
3. Se ce ne sono 2 nella posizione errata utilizzare gli **algoritmi di inversione** indicati sotto
4. **Orientare gli angoli** della faccia opposta con la stessa mossa indicata nella [risoluzione del cubo 3x3](3x3_resolution), passo 6

***

# Inverti 2 angoli adiacenti

![2x2_resolution-1](/assets/cubes/2x2_resolution-1.png)

> **L F' L' D' L' D F**

***

# Inverti 2 angoli opposti

![2x2_resolution-2](/assets/cubes/2x2_resolution-2.png)

> **F L F L' D' L' D**

***

# Notazione

![2x2_resolution-3](/assets/cubes/2x2_resolution-3.png)

Una lettera singola si riferisce ad una rotazione di una faccia **in senso orario** di 90 gradi (un quarto di giro)

> **F R U L B D**

Una lettera seguita da un apostrofo si riferisce ad una rotazione di una faccia **in senso antiorario** di 90 gradi

> **F' R' U' L' B' D'**

Una lettera seguita dal numero 2 si riferisce ad una **doppia rotazione**, cioè di 180 gradi

> **F2 R2 U2 L2 B2 D2**

Nello schema a fianco è indicata in **rosso** la faccia da ruotare, in **grigio** la faccia frontale (**F**).

***

# Credits

- <https://ruwix.com/twisty-puzzles/2x2x2-rubiks-cube-pocket/>

{% include cube_footer.md %}