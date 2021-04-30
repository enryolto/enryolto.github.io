---
layout: page
title: Risolution 4x4
permalink: /it/cubes/4x4_resolution
lang: it
---

Fate riferimento alla pagina di spiegazione della **[notazione](4x4_notation)** utilizzata per gli algoritmi.

![4x4_resolution-1](/assets/cubes/4x4_resolution-1.png)

# 1. CENTRO 2X2 SU UNA FACCIA

1. 
    1. Dato che il cubo 4x4 non ha pezzi centrali fissi che determinano il colore della faccia corrispondente, bisogna determinare lo [schema dei colori](color_scheme) a partire dai pezzi d'angolo.
    2. Utilizziamo i centri **bianchi** e **gialli** per iniziare la risoluzione; se non ci sono angoli con entrambi questi colori possiamo procedere.
    3. Non servono istruzioni per risolvere questo primo centro 2x2 in quanto non ci sono pezzi già risolti da mantenere in posizione; si può utilizzare il seguente algoritmo per inserire un pezzo dalla faccia superiore a quella frontale:
        ▪ **`Dw' Fw' Dw`**

# 2. CENTRO SULLA FACCIA OPPOSTA

1. 
    1. Una volta completato il centro della faccia **bianca**, procedi a completare il centro opposto 2x2 che sarà **giallo**.
    2. Mantieni la faccia **bianca** completa **in basso**, e completa quella **gialla in alto**.
    3. Gli algoritmi per completare il centro giallo sono: 
        ▪ **`Rw U Rw'`** e
        ▪ **`Rw U2 Rw'`**

![4x4_resolution-2](/assets/cubes/4x4_resolution-2.png)

![4x4_resolution-3](/assets/cubes/4x4_resolution-3.png)

# 3. GLI ALTRI CENTRI

1. 
    1. Mantieni i centri completati nelle facce **sinistra** e **destra**; fai attenzione allo [schema dei colori](color_scheme) per evitare di dover successivamente procedere a [spostare i centri](move_centers) già completati.
    2. Utilizza gli stessi algoritmi del passo precedente, sempre mantenendo le facce bianca e gialla a sinistra e destra:
        ▪ **`Rw U Rw'`**

# 4/A. ALLINEAMENTO SPIGOLI INCROCIATI

Una volta completati tutti i centri 2x2, il passo successivo consiste **nell'appaiare gli spigoli**; l'algoritmo permette di appaiare gli spigoli fronte-sinistro e fronte-destro (della faccia centrale). A seconda della posizione ci sono algoritmi speculari.

![4x4_resolution-4](/assets/cubes/4x4_resolution-4.png)

# PRIMO CASO

**`Uw L' U' L Uw'`**

![4x4_resolution-5](/assets/cubes/4x4_resolution-5.png)

# SECONDO CASO

**`Uw' R U R' Uw`**

# 4/B. ALLINEAMENTO SPIGOLI OPPOSTI

Quando i pezzi da appaiare sono opposti (sullo stesso livello della faccia centrale), è necessario girare quello a destra al contrario per effettuare una delle mosse.

- **`R U' B' R2`**

![4x4_resolution-6](/assets/cubes/4x4_resolution-6.png)

![4x4_resolution-7](/assets/cubes/4x4_resolution-7.png)

# 5. ALLINEAMENTO DEGLI ULTIMI 2 SPIGOLI

1. 
    1. Una volta rimasti gli ultimi 2 spigoli da appaiare, non si possono utilizzare gli algoritmi indicati sopra perché mancano spigoli ancora da appaiare da mantenere nello strato superiore.
    2. Si utilizza allora un algoritmo diverso per risolvere questi ultimi 2; utilizza l'algoritmo **`R U' B' R2`** se il pezzi non sono allineati correttamente.
    3. Appaia gli ultimi 2 spigoli: **`Dw R F' U R' F Dw'`**

# 6. RISOLUZIONE COME 3X3

1. Bisogna considerare i due strati centrali come uno solo fisso, in particolare
    - i centri 2x2 (**A**)
    - gli spigoli 2x1 (**B**)
    - gli angoli 1x1 (**C**)
2. Seguire lo schema illustrato [qui](3x3_resolution)

Attenzione che a differenza del cubo 3x3, possono capitare altri casi, come ad esempio:

- [Casi di parità](4x4_parity)
- Necessità di [spostare i centri](4x4_move_centers) (non è necessario se si è seguito correttamente lo [schema dei colori](color_scheme))

![4x4_resolution-8](/assets/cubes/4x4_resolution-8.png)

***

# Credits

- <https://ruwix.com/twisty-puzzles/4x4x4-rubiks-cube-rubiks-revenge/>

{% include cube_footer.md %}