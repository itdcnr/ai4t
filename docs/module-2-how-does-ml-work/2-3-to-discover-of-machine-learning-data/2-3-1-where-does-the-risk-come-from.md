---
title: Da dove proviene il rischio?
description:
---

[Articolo completo in francese pubblicato il 20 febbraio 2020 da binaire sul sito web di Le Monde: "D’où vient le risque ? Des données et des algorithmes" - _Authori: Serge Abiteboul, Thierry Viéville_](https://www.lemonde.fr/blog/binaire/2020/02/05/les-plateformes-numeriques-un-foyer-pour-les-risques-donnees-et-algorithmes/) 

_L'incontro di ricercatori del settore giuridico e dell'informatica nel contesto del lancio della [Centre Internet et Société](http://cis.cnrs.fr/) (Internet and Society Center) è stato un'opportunità per una riflessione interdisciplinare e per sollevare una serie di domande e approcci di ricerca iniziali da esplorare insieme. Questo articolo riassume i risultati della tavola rotonda. **Serge Abiteboul, Thierry Viéville.**_

<center><img src="https://storage.googleapis.com/prd-blogs/2020/02/cc883a26-white-caution-cone-on-keyboard-211151.jpg" alt="Photo by Fernando Arcos from Pexels" width="500"></center>
<center>[Photo by Fernando Arcos from Pexels](https://www.pexels.com/photo/white-caution-cone-on-keyboard-211151/?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels)</center>

Classificazione dei rischi
-----------------------

Le piattaforme digitali e il loro ruolo nella società stanno occupando i media e gli organi di governo. Noi, avvocati e informatici, le percepiamo come nuovi mercati di dati.

Diversi attori umani, artisti, autori, creatori di contenuti, sviluppatori di lingue, sviluppatori di piattaforme, sviluppatori di applicazioni, utenti e consumatori di Internet, attori pubblici e privati, gravitano intorno a queste piattaforme e sono esposti a **due tipi di rischio**:

*   I **rischi legati ai dati** che riguardano la protezione dei dati su queste piattaforme.
*   I **rischi legati agli algoritmi** che si riferiscono alle questioni di discriminazione algoritmica..


Questo documento fornisce una prima riflessione su come affrontare le piattaforme digitali e i rischi legati ai dati e agli algoritmi. Queste questioni possono essere affrontate da due punti di vista complementari: il punto di vista giuridico, la cui preoccupazione principale è quella di definire i quadri che permettono di identificare e gestire questi rischi, e il punto di vista informatico, il cui obiettivo è quello di sviluppare gli strumenti necessari per quantificare e risolvere questi rischi.
Questo documento fornisce una prima riflessione su come affrontare le piattaforme digitali e i rischi dati e algoritmici. Queste questioni possono essere affrontate da due punti di vista complementari: il punto di vista giuridico, la cui preoccupazione principale è quella di definire i quadri che permettono di identificare e gestire questi rischi, e il punto di vista informatico, il cui obiettivo è quello di sviluppare gli strumenti necessari per quantificare e risolvere questi rischi.


Le tre sfaccettature del rischio legato agli algoritmi 
------------------------------------

Il rischio legato agli algoritmi può essere caratterizzato in tre modi.

*  In primo luogo, c'è il **confinamento algoritmico**, che può riguardare anche le opinioni, le conoscenze culturali o anche le pratiche commerciali. In effetti, gli algoritmi mettono gli utenti di Internet di fronte allo stesso contenuto, a seconda del loro profilo e dei parametri integrati, nonostante il rispetto del principio di equità. È il caso dei siti che suggeriscono notizie come Facebook o dei siti che suggeriscono prodotti come Amazon.
*   La seconda sfaccettatura del rischio algoritmico è legata al **controllo di tutti gli aspetti della vita di un individuo**, dalla regolamentazione delle informazioni per gli investitori alle sue abitudini alimentari, gli hobby o persino lo stato di salute. Questo tracciamento dell'individuo suggerisce una forma di sorveglianza che contravviene all'essenza stessa della libertà individuale.
*   Il terzo è legato alla **potenziale violazione dei diritti fondamentali**. In particolare, la discriminazione algoritmica definita come un trattamento sfavorevole o ineguale, rispetto ad altre persone o altre situazioni uguali o simili, basato su un motivo espressamente vietato dalla legge. Questo comprende lo studio dell'equità (_fairness_) odegli algoritmi di ranking (ordinamento delle persone che cercano un lavoro online), di raccomandazione e di apprendimento delle previsioni. Il problema del [bias discriminatorio](https://www.ted.com/talks/joy_buolamwini_how_i_m_fighting_bias_in_algorithms?language=fr) indotto da algoritmi riguarda diversi settori come le assunzioni online su MisterTemp', Qapa e TaskRabbit, le decisioni dei tribunali, le decisioni delle pattuglie di polizia o le ammissioni scolastiche.

Dai rischi ai bias nei dati e negli algoritmi
--------------------------------------------

Riprendiamo una [classificazione dei bias](https://www.telecom-paris.fr/wp-content-EvDsK19/uploads/2019/02/Algorithmes-Biais-discrimination-equite.pdf) proposta dai colleghi di Télécom ParisTech e discussa in [un report](https://www.institutmontaigne.org/blog/algorithmes-donnees-et-biais-quelles-politiques-publiques) dell'Institut Montaigne di Parigi. Adattiamo questa classificazione al rischio dati e al rischio algoritmicocon un focus sul bias.

<center><img src="../Images/AI4T-M2.3-Data-and-algorithms.png" alt="Illustration from Sihem Amer-Yahia" width="600"><br/>
©Sihem Amer-Yahia</center>

I dati provengono da diverse fonti e hanno formati multipli. Portano diversi tipi di bias.

Il bias dei dati è principalmente statistico.

*   Il **Data-bias** è tipicamente presente nei valori dei dati. Per esempio, nel caso di un algoritmo di reclutamento addestrato su un database in cui gli uomini sono sovrarappresentati, l'algoritmo escluderà le donne.
*  Lo **Standard bias**  è una tendenza ad agire in riferimento al gruppo sociale a cui apparteniamo. Per esempio, uno studio mostra che le donne tendono a cliccare sulle offerte di lavoro che pensano siano più facili da ottenere in quanto donne.
*   L'**Omitted variable bias** (bias di modellazione o di codifica) è un bias dovuto alla difficoltà di rappresentare o codificare un fattore nei dati. Per esempio, poiché è difficile trovare criteri fattuali per misurare l'intelligenza emotiva, questa dimensione è assente dagli algoritmi di reclutamento.
*   **Il selection bias** è a sua volta dovuto alle caratteristiche del campione selezionato per trarre conclusioni. Per esempio, una banca userà i dati interni per ricavare un punteggio di credito, concentrandosi su coloro che hanno o non hanno ottenuto un prestito, ma ignorando quelli che non hanno mai avuto bisogno di un prestito, ecc.

Il bias algoritmico è principalmente una questione di ragionamento.

*   **Un bias economico** viene introdotto negli algoritmi, intenzionalmente o meno, perché sarà economicamente efficiente. Per esempio, un algoritmo pubblicitario indirizza gli annunci a particolari profili per i quali le possibilità di successo sono maggiori; i rasoi avranno più probabilità di essere visti dagli uomini, i fast food dalle popolazioni socialmente svantaggiate, ecc.

Si dovrebbe anche menzionare una serie di bias cognitivi

*   I bias di conformità, noti come "panhandle sheep", corrispondono alla nostra tendenza a riprodurre le credenze della nostra comunità. Questo è il caso, per esempio, quando sosteniamo un candidato in un'elezione perché la sua famiglia e i suoi amici lo sostengono.       
*   Il bias di conferma è la tendenza a favorire le informazioni che rafforzano il proprio punto di vista. Per esempio, dopo che una persona di fiducia ci ha detto che quel tale è prepotente, notiamo solo gli esempi che lo dimostrano.            
*   Il bias di correlazione illusoria è una tendenza a voler associare fenomeni che non sono necessariamente correlati. Per esempio, pensare che ci sia una relazione tra se stessi e un evento esterno come il ritardo di un treno o il tempo.
*   Il bias endogeno è legato all'incapacità relativa di anticipare il futuro. Per esempio, nel caso del _credit scoring_, può essere che un candidato con una storia di rimborso di prestiti scadente possa cambiare il suo stile di vita quando decide di mettere su famiglia.

<center><img src="../Images/AI4T-M2.3-Data-and-algorithms-2.png" alt=Illustration from Sihem Amer-Yahia" width="600">  
©Sihem Amer-Yahia</center>

Gli algoritmi sono una serie di istruzioni che manipolano i dati di input e restituiscono dati di output. Questi dati di input a volte portano dei bias. I bias possono anche essere trovati in una o più istruzioni degli algoritmi.

#### Dovremmo affrontare il rischio legato ai dati e il rischio legato agli algoritmi sulle piattaforme digitali insieme o separatamente?
  
Consideriamo due esempi, il contesto della tecnologia blockchain e quello dei sistemi di intelligenza artificiale.


Su blockchain, prima di tutto, ci sono i dati, i rischi e i loro bias. Prendiamo l'esempio dei dati e dei rischi associati. La blockchain funziona per crittografia con due chiavi crittografiche: chiavi private e chiavi pubbliche. Molti utenti di Internet affidano alle piattaforme le loro chiavi private, delegando loro la gestione del loro indirizzo e il movimento dei fondi. Queste chiavi private sono conservate in un file accessibile su Internet (_hot storage_) o su un dispositivo isolato (_cold storage_). Il primo è ovviamente molto vulnerabile all'hacking, mentre il 92% delle piattaforme di trading riferisce di utilizzare un sistema di _cold storage_. Dal 2011, sono stati registrati 19 incidenti gravi per una perdita stimata in 1,2 miliardi di dollari. Le cause di questi incidenti sono molteplici. La più comune deriva dalla manomissione delle chiavi private, seguita dall'introduzione di malware. L'_hack_ della piattaforma Coincheck in Giappone nel gennaio 2018 illustra la debole protezione del sistema di _hot storage_.

Another example on algorithms and associated risks, the exchange of cryptocurrencies on platforms is seeing the development and diversification of market infrastructures. The ambition is _"to enable the establishment of an environment that promotes the integrity, transparency and security of the services concerned for investors in digital assets, while ensuring a secure regulatory framework for the development of a robust French ecosystem"_. France has recently France has recently adopted a legal framework to regulate these activities activities in a flexible manner. However, at the global level, the risks of non-transparent listings or suspicious transactions of non-transparent quotations or suspicious transactions resembling of direct price manipulation or informed investor practices, such as type of _frontrunning_. Frontrunning is a stock market technique that allows a broker to use an order transmitted by its customers transmitted by his clients in order to enrich himself. The technique consists of The technique consists of taking advantage of price discrepancies generated by large orders The technique consists of taking advantage of price shifts caused by large orders placed by the broker's clients.

Let's get to the question "should we address risk-data and data-risk and algorithm-risk on digital platforms together or separately?" With regard to blockchain, the law's answer is separate, because the risks captured are different. On the one hand, certain provisions of criminal law, civil liability or personal data protection will be mobilised. mobilised. On the other hand, in France, the recent legal framework for the other hand, in France, the recent legal framework aimed at capturing the activities of service providers and to avoid algorithmic risk is mainly regulatory. is mainly regulatory.

Responsability vs. Accountability
---------------------------------

**On AI systems, we will take the prism of liability and our question through the prism of liability and accountability.**

This question is diabolical because it requires the lawyer to dive into the world of computing in order to understand what artificial intelligence consists of, this catch-all word that covers, in reality, numerous computer sciences and techniques. And is it necessary to use this term at all, when the creator of the much used voice assistant Siri has just written a book with a slightly provocative title, which is a tad provocative, states that artificial intelligence intelligence does not exist... ([_Luc Julia, L’intelligence artificielle n’existe pas, First editions,_ 2019-](https://www.decitre.fr/livres/l-intelligence-artificielle-n-existe-pas-9782412043400.html?gclid=CjwKCAiA0svwBRBhEiwAHqKjFn1VMnxXJfj2t5mUiTcazBI-Bg9q6s9zDvYC8Oz8mII4f1z6TiTEIhoCGl8QAvD_BwE) _AI does not exist[)](https://www.decitre.fr/livres/l-intelligence-artificielle-n-existe-pas-9782412043400.html?gclid=CjwKCAiA0svwBRBhEiwAHqKjFn1VMnxXJfj2t5mUiTcazBI-Bg9q6s9zDvYC8Oz8mII4f1z6TiTEIhoCGl8QAvD_BwE)_.

A distinction between AI systems is often made: only certain systems are actually embedded in a body in order to offer its algorithmic behaviours: Other AI systems make algorithmic decisions or recommendations that can have an immediate effect on the real world and the human mind, without needing to be embodied in a body: These include consumer marketing recommendations, social network feeds, predictive justice, and are often seen as "rigged". However, all AI systems eventually become embedded in a machine: a robot, a car, a computer, a phone, and all AI systems have the potential to impact on the human mind or body, and even on personal rights ([M. Baccache, Intelligence artificielle et droits de la responsabilité, in Droit de l’intelligence artificielle, A. Bensamoun, G. Loiseau, (dir.), L.G.D.J., Les intégrales 2019, p. 71 f.](https://www.lgdj.fr/droit-de-l-intelligence-artificielle-9782275065649.html)\- _Law of Artificial Intelligence_) , so much so that we will choose here to grasp the question of liability when using AI systems in a transversal manner.

The cross-cutting question we will ask is whether the specificity of AI systems, both in terms of their evolving nature and their complex governance, and in terms of the risks of their implementation for humans and society, are sufficiently well understood; volutive nature and their complex governance, as well as the risks of their implementation for human beings and society, do not call for a new approach; This is not to say that accountability, understood as the sole a posteriori sanction for the occurrence of a risk, should be seen as a complement between accountability in the governance of each AI system throughout its life cycle and a posteriori accountability. If accountability is recognised as a prerequisite for responsibility, it will imply considering data-risks and algorithmic-risks jointly, thus preserving the specificity of the system; cificity of each of these risks, but by linking them, because it is through the conjunction of these two types of risks, that consequences that are precarious for humans or society can occur.

In fact, in its April 2019 guidelines on trustworthy AI, the High Level Expert Group on Artificial Intelligence, mandated by the European Commission to develop and implement a European strategy on artificial intelligence; In one of its proposals, the High Level Expert Group on Artificial Intelligence, mandated by the European Commission, recalls a fundamental point, namely the need to recognise and acknowledge that &some applications of AI may bring considerable benefits to the environment; While some AI applications may bring significant benefits to individuals and society, they may also have negative impacts, including impacts that may be difficult to anticipate, recognise or measure (e.g. in the form of the use of AI); (e.g. on democracy, the rule of law and distributive justice, or on the human mind itself) (High Level Expert Group on Artificial Intelligence, [Guidelines for Trustworthy AI, April 2019, constituted by the European Commission in June 2018](https://ec.europa.eu/digital-single-market/en/news/ethics-guidelines-trustworthy-ai),).

In doing so, the High Level Expert Group calls for appropriate measures to mitigate these risks where necessary, in a manner commensurate with the scale of the problem; (b) to take into account the extent of the risk and, on the basis of the articles of the Charter of Fundamental Rights of the European Union, to pay particular attention to situations involving more vulnerable groups of people; In this context, the European Commission should pay particular attention to situations concerning more vulnerable groups such as children, people with disabilities and other historically disadvantaged groups at risk of exclusion, and/or to situations characterised by asymmetries of power or information, for example between employers and workers, or between businesses and consumers.

Even though certain risks and the protection of certain vulnerable groups require it, taking the appropriate measures is not easy, even beyond the current tension between the principle of innovation and the principle of security. The reason is that both the technical bricks used and the people involved in the operation of an AI system are numerous, varied and complex, leading to many interactions that are not easy to master. It is worth noting that the high-level panel makes a set of proposals, in terms of the ethics and technical robustness of AI systems, that challenge the idea that trust in an AI system is a prerequisite for its success; In the light of the current risks of AI deployment, trust in an AI system must be based on an a priori accountability of its governance throughout its life cycle, which includes the objective of making these actions explicit.

The notion of accountability is central to understanding the complementarity and the long continuum between accountability and responsibility. More than the term responsibility, this notion of _accountability_ can be precisely translated by the notions of accountability and/or responsibility. This accountability makes it possible to consider data-risks and algorithmic risks together, thus taking into account the specificity of each of these risks, but also to take into account the fact that each of them has its own specificity; It is through the conjunction of these two types of risks that consequences that are harmful to humans or society can occur.

Summary
-------

**In summary**, the legal perspective will differ depending on the issues and applicable concepts. In the case of blockchain, it is important to separate the data risk from the risk-algorithms as they deal with different issues and require and require different legal frameworks. The The first deals with the issue of disclosure of the identity of the The first deals with the issue of disclosure of the identity of parties, which is a matter of data security, while the second deals with the issue of fraudulent digital assets. In the In the case of artificial intelligence systems, it will depend on whether whether the damage should be prevented or sanctioned once it has the damage or to sanction it once it has occurred. In the case of In the case of a search for accountability, it is necessary to consider the In the case of accountability, data-risks and algorithm-risks should be considered together.

If the question is one of responsibility (_liability_) and accountability (_accountability_), i.e., that of imputing fault to a the issue of attributing fault to a natural person, it will be important to to separate the two risks. This separation is also the one that is This separation is also the one advocated in computer science in order to identify the "culprits": data or algorithms. Data provenance and algorithmic tracing techniques and algorithmic tracing techniques will help to isolate the the reasons for the fault. The first step is to identify whether the fault is due to a data risk such as disclosure of privacy or statistical bias in the data, or data, or to an algorithmic risk of the economic or cognitive type, or if the cognitive type, or whether the fault is due to both. It will therefore only be possible to fault and determine the applicable legal frameworks only if there is a separation. if there is a separation. Similarly, if the objective is to "fix" the data or the algorithm, the data or the algorithm, the two types of risk must be considered separately. be done separately. This is called orthogonality in computer science. According to the dictionary, the instruction set of a computer is said to be _orthogonal_ when (almost) all instructions can be applied to all types of data. An orthogonal instruction set simplifies the task of the compiler since there are fewer special cases to deal with the operations can be applied as is to any type of data. any type of data. In our context, this would mean having a context, this would mean having a perfect dataset and seeing how the algorithm behaves to determine if there is a risk-algorithms and having a perfect algorithm and examining the results applied to a dataset to determine the risk-data. These strategies have a bright future ahead of them.

**Authors :** 

[**Sihem Amer-Yahia**](https://www.linkedin.com/in/sihem-amer-yahia-96072622/?originalSubdomain=fr) (DR CNRS INS2I, Univ. Grenoble-Alpes) - Research director at National Centre for Scientific Research  
[**Amélie Favreau**](https://www.linkedin.com/in/am%C3%A9lie-favreau-36b56b109/?originalSubdomain=fr) (MdC Droit Privé, Univ. Grenoble-Alpes) - Associate Professor in Private Law  
[**Juliette Sénéchal**](https://pro.univ-lille.fr/juliette-senechal/) (MdC Droit Privé, Univ. de Lille) -Associate Professor in Private Law
