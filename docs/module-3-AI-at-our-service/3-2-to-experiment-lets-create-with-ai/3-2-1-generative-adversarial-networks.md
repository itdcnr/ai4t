---
title: Reti Generative Avversarie (GAN)
description:
hide:
- toc
---

Le Reti Generative Avversarie si collocano tra l'apprendimento supervisionato basato sulla fornitura di dati di input, il cui corrispondente output desiderato è noto al fine di stimare la relazione input-output al di là dei campioni forniti per l'addestramento, e l'apprendimento non supervisionato.

Quando sono disponibili solo dati di input, per scoprire certe strutture all'interno dei dati (per esempio il numero di parametri che lo caratterizzano), ci sono molti altri paradigmi, per esempio **semi-supervisionato** dove si mescolano dati in cui si conosce l'output desiderato e altri no, per mescolare i due approcci.

Un altro paradigma cosiddetto **autosupervisionato** consiste nel trovare, a partire dai dati di input, un meccanismo esterno per generare gli output corrispondenti. Questo per risparmiare l'enorme sforzo umano di inserire per ogni input l'output desiderato, ad esempio etichettando le immagini a mano, pixel per pixel se necessario (se si vuole trovare dove si trova il gatto in un'immagine). Per esempio, per imparare a colorare automaticamente le immagini, si può iniziare con immagini a colori, ridurle a immagini in bianco e nero, e poi addestrare il meccanismo fornendogli le immagini a colori desiderate, qui note senza la necessità di ricostruirle per ogni immagine in bianco e nero.

Questo funziona anche per imparare la posizione relativa degli elementi in un'immagine che viene ritagliata, o la coerenza temporale in un video. Ma non funziona per tutto. Funziona ogni volta che si trova un trucco per generare automaticamente gli input e gli output desiderati dai dati. **Questo è una sorta di apprendimento non supervisionato che genera automaticamente i dati per un paradigma di apprendimento supervisionato.**
