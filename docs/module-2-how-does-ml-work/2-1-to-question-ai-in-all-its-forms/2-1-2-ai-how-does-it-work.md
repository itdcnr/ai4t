---
titolo: AI&#58; Come funziona?
descrizione:
---

_Texte tradotto da IAI Mooc._

Molti meccanismi di intelligenza artificiale oggi funzionano attraverso l'apprendimento supervisionato. Questo meccanismo assomiglia a uno dei modi in cui un sistema biologico impara.

Immaginiamo di voler insegnare ad un'intelligenza artificiale a riconoscere un gatto in un'immagine.

Per fare questo, forniremo molti dati, vale a dire, molte immagini dove si vede un gatto e molte immagini dove non si vede nessun gatto, in modo che il calcolo aggiusti i suoi parametri per dare un valore di uscita corrispondente alla presenza o meno del felino. Tutte queste immagini costituiscono i dati di entrata, e il risultato atteso, la presenza o meno di un gatto nell'immagine, i dati di uscita. Questi dati di "input" e "output" sono le uniche informazioni fornite per il suo addestramento.  
Il meccanismo computazionale deve quindi regolare i parametri interni (come le manopole di controllo di una macchina fotografica) per determinare se c'è o meno un gatto nell'immagine. La prima volta, verrà fornito un risultato casuale e quindi molto probabilmente falso, poi a poco a poco il meccanismo osserverà gli errori e con prove successive regolerà i parametri per ridurli. Questo processo è noto come apprendimento automatico.

<center><img src="../Images/artificial-intelligence-3382521_1280.jpg" alt="Pianta virtuale: riconoscimento piante" width="350"></center>
<center>Immagine di Gerd Altmann da Pixabay</center>

Il meccanismo delle reti neurali artificiali è molto diverso dai neuroni del nostro cervello: sono solo unità computazionali elementari che combinano i dati di input e forniscono un valore basso o alto come output a seconda del valore combinato. Una rete neurale è un insieme di neuroni che sono tutti connessi e comunicano tra loro. Sono i parametri di queste connessioni tra i neuroni che costituiscono le manopole di controllo per ottenere l'output desiderato per un dato input. Dai neuroni di input ai neuroni di output, attraverso i neuroni interni alla rete (neuroni nascosti), l'informazione digitale viene trasmessa per dare un risultato finale.

Si parla di **apprendimento profondo** quando ci sono molti strati nascosti sovrapposti per rendere il calcolo più efficiente.

Si parla di **reti neurali evolutive** quando i neuroni raccolgono informazioni da altri neuroni nelle vicinanze prima di trasmettere l'output agli strati superiori. Per esempio, quando si analizza un'immagine, una rete neurale convoluzionale creerà dei filtri per raggruppare le informazioni di una piccola area dell'immagine. Per esempio, il contrasto, o un elemento di colore, e poi allo strato successivo piccole aree corrispondenti a elementi di base come una linea o un'area leggermente rotonda, e poco a poco il meccanismo riconosce un gatto come Jim Davis, è incredibile. Ma allora, quale ragionamento è stato fatto per distinguere le immagini con e senza gatti? Beh, nessuno! È solo un calcolo, un calcolo cieco in un certo senso. E oggi non sappiamo come interpretare un tale calcolo. Questa è quella che chiamiamo la scatola nera dell'IA <sup>2</sup>.

* * *
<sup>2</sup>Riferimenti in francese: _[Comprendre le DeepLearning et les Réseaux de neurones en 10 mins !](https://www.youtube.com/watch?v=gPVVsw2OWdM)_ vidéo, Sociamix, août 2019 - (Capire l'apprendimento profondo e le reti neurali in 10 minuti!)  
_[Le deep learning](https://www.youtube.com/watch?v=trWrEWfhTVg)_, vidéo, Science étonnante #27, avril 2016  
_[Comment le " deep learning " révolutionne l'intelligence artificielle](https://www.lemonde.fr/pixels/article/2015/07/24/comment-le-deep-learning-revolutionne-l-intelligence-artificielle_4695929_4408996.html)_ par Morgane Tual ; Le Monde, juillet 2015. \- (Come l'apprendimento profondo trasforma l'AI.)
