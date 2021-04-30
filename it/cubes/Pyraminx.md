---
layout: page
title: Pyraminx
permalink: /it/cubes/pyraminx
lang: it
---

Il **Pyraminx**, anche noto come il Cubo di Rubik triangolare, è un puzzle a tre strati a forma di tetraedro, con quattro facce triangolari che sono divise ciascuna in nove triangoli più piccoli.

- <https://it.wikipedia.org/wiki/Pyraminx>

![pyraminx-1](/assets/cubes/pyraminx-1.png)

# Notazione

Nel Pyraminx si possono identificare sono 3 tipi di pezzi:

- **Vertici** (**A**) - con 3 colori
- **Pezzi centrali** (**B**) - con 3 colori
- **Spigoli** (**C**) - con 2 colori

Si identificano i 4 vertici del Pyraminx con le lettere analogamente a quanto si fa con la notazione standard del Cubo di Rubik:

- **`U`** - vertice superiore (up)
- **`R`** - vertice destro (right)
- **`L`** - vertice sinistro (left)
- **`F`** - vertice frontale (front)

Il movimento indicato dalla lettera indica una **rotazione del vertice di 120° in senso orario** (es. **`L`** evidenziato in rosso). Il movimento indicato dalla lettera con l'apostrofo (es. **`L'`**) indica una rotazione di 120° in **senso antiorario**.

Gli **algoritmi** indicati sono descritti utilizzando una combinazione di lettere, ad esempio: **`L' F L F'`**.

![pyraminx-2](/assets/cubes/pyraminx-2.png)

# 1. Vertici e centri

La soluzione del Pyraminx comincia ruotando i 4 vertici (**A**) per allinearli ai pezzi centrali (**B**). Si tratta di una semplice rotazione di ciascun vertice perché i 3 lati dei pezzi centrali sono collegati rigidamente. Quando i vertici sono in posizione, ruota il Pyraminx in modo che i 3 centri siano abbinati su ciascuna faccia, in modo da raggiungere la configurazione simile a quella rappresentata nel disegno.

Una volta completato questo passo si procede a posizionare i 6 spigoli (**C**).

# 2. Due spigoli adiacenti ad un angolo

In questo passo bisogna **risolvere i 3 spigoli attorno al vertice superiore**. Si usano gli algoritmi **destro** e **sinistro** a secondo della direzione dello spigolo da spostare. Questi algoritmi lasciano in posizione i pezzi marcati con la stella (*).

- Algoritmo destro: **`R F R' F'`**
- Algoritmo sinistro: **`L' F' L F`**

![pyraminx-3](/assets/cubes/pyraminx-3.png)

![pyraminx-4](/assets/cubes/pyraminx-4.png)

# 3. Gli ultimi spigoli

Rimangono solo da sistemare gli ultimi spigoli. Tieni il Pyraminx con la faccia da completare **a sinistra** ed esegui le mosse seguenti, a seconda del caso, come riportato nello schema a fianco:

- Senso orario: **`U' F U F'`**
- Senso antiorario: **`U L' U' L`**
- Ruotare 2 spigoli: **`F U' F' U F' L F L'`**

***

# Credits

- <https://ruwix.com/twisty-puzzles/pyraminx-triangle-rubiks-cube/>

{% include cube_footer.md %}