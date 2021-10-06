---
title: Giochiamo con i Neuroni della Macchina
description:
---

Il software online **[TensorFlow](https://www.tensorflow.org/overview/)** permette di costruire reti neurali artificiali e di testare le loro risposte per diversi tipi di problemi e su diversi tipi di dati. Nel tipo di problema "Classificazione", l'obiettivo è quello di separare i punti di colore blu e arancione. Un'applicazione di questo tipo di problema è, per esempio, un algoritmo di classificazione delle foto. Nell'esempio qui sotto, c'è un input (caratteristica) che separa i punti orizzontalmente e un altro che li separa verticalmente. Combinando questi due input, otteniamo una separazione obliqua. Il risultato (output) si adatta bene al tipo di dati scelti.

![Tensor flow playground view](../Images/tensor-flow.png)


###TensorFlow: Alcune spiegazioni prima di provare la simulazione di una rete neurale

_Fonte: tradotto da [Pixees French web site](https://pixees.fr/jouez-avec-les-neurones-de-la-machine/)_

**Cosa è una rete neurale e come funziona?**
Una rete neurale è un meccanismo generico composto da piccole unità (pseudo-neuroni) collegate tra loro. Ogni unità esegue un'operazione molto semplice: prende dei valori in ingresso, li combina in modo molto semplice (una semplice media con coefficienti) e applica una trasformazione sul risultato (ad esempio mantiene solo valori positivi).

I coefficienti utilizzati per pesare la media sono i parametri di questo algoritmo. È la combinazione di un numero molto, molto grande di queste unità che permette di eseguire operazioni molto complesse. Una rete di tali "neuroni" si ottiene accumulando diversi strati di tali unità. Gli input sono i dati che vogliamo elaborare. Vengono trasformati attraverso tutti gli strati e l'ultimo strato dà come output una predizione su questi dati, per esempio per rilevare se c'è un volto in un'immagine. La rete neurale è quindi una funzione parametrizzata con molti coefficienti (chiamati "pesi") ed è la scelta di questi pesi che definisce l'elaborazione effettuata.

**Dove sono i neuroni in TensorFlow?**
Sull'interfaccia web di TensorFlow, una rete di una dozzina di neuroni, ciascuno con un numero di parametri compreso tra 3 e 10, può essere facilmente creata. L'output calcolato dipende quindi da centinaia di parametri oltre alle due coordinate (x,y) del punto di ingresso. Sull'interfaccia, ogni quadrato rappresenta un neurone e il colore del pixel di coordinate (x,y) nel quadrato rappresenta l'output del neurone quando mettiamo (x,y) in input della rete. Se c'è un solo neurone all'uscita, esso viene rappresentato con un quadrato più grande sulla destra della rete. I parametri della rete sono inizializzati con valori casuali.

**Ma come si imparano questi pesi?**
L'apprendimento supervisionato consiste nel fornire esempi di dati con la soluzione da trovare per addestrare la rete a regolare questi pesi come richiesto. Nell'esempio della figura qui sopra, si tratta di una serie di punti in un quadrato, ognuno con un colore atteso (blu o arancione), con l'obiettivo di prevedere il colore del punto in una determinata posizione.  Un algoritmo classico di regolazione progressiva dei pesi viene utilizzato per trovare i parametri in questione.
Il pulsante "play" in alto a sinistra dell'interfaccia serve a lanciare questo algoritmo, e l'output della rete neurale si vede quindi evolvere durante il processo di "apprendimento": il colore di fondo del neurone di output tende ad assumere il colore dei punti di allenamento che vengono disegnati sopra di esso. Un'altra parte del dataset viene poi utilizzata per testare la qualità della funzione risultante della rete. Una curva in alto a destra mostra il tasso di errore dei dati utilizzati per l'apprendimento (per verificare che i pesi siano stati regolati correttamente) e il tasso di errore degli altri dati di prova (per verificare che ciò che è stato appreso si generalizza bene ai nuovi dati). I pulsanti sul lato sinistro permettono di regolare la distribuzione dei dati tra il set di allenamento e quello di test e anche di aggiungere errori ai dati (dati rumorosi) per vedere se il meccanismo è robusto a questi errori.

Nella pratica, riusciamo a trovare parametri soddisfacenti, ma non esiste un vero e proprio quadro teorico per formalizzare tutto questo, è una questione di sperimentazione: scegliere il giusto numero di neuroni, il giusto numero di strati di neuroni, quali calcoli preliminari aggiungere come input (per esempio moltiplicando gli input per aumentare i gradi di libertà del calcolo).
Questo tipo di tecniche può produrre risultati impressionanti nella pratica, come nel riconoscimento della voce o degli oggetti in un'immagine.

Tuttavia, capire perché (e come) si ottengono risultati così buoni è ancora una questione scientifica abbastanza aperta.

### Prova TensorFlow

_Clicca sull'immagine sottostante per avviare TensorFlow in una nuova finestra_

[![TensorFlow playground view](../Images/tensor-flow.png)](https://playground.tensorflow.org/#activation=tanh&amp;batchSize=8&amp;dataset=circle&amp;regDataset=reg-plane&amp;learningRate=0.03&amp;regularizationRate=0&amp;noise=10&amp;networkShape=5,2&amp;seed=0.02708&amp;showTestData=false&amp;discretize=false&amp;percTrainData=50&amp;x=true&amp;y=true&amp;xTimesY=false&amp;xSquared=false&amp;ySquared=false&amp;cosX=false&amp;sinX=false&amp;cosY=false&amp;sinY=false&amp;collectStats=false&amp;problem=classification&amp;initZero=false&amp;hideText=false;target=blank){:target="_blank" }
