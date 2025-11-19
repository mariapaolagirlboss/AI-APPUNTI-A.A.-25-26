<div class = "domanda1">
1. Qual è lo scopo del metodo di <strong>Cross-Validation K-Fold</strong>?<br>
	- Selezionare automaticamente il miglior modello.<br>
	- Aumentare la dimensione del training set.<br>
	- <span class="evidenzia_risposta">Valutare il modello su più set di test, migliorando la generalizzazione. </span> <br>
	- Ridurre il numero di dati necessari per l'addestramento. <br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Valutare il modello su più set di test, migliorando la generalizzazione. <br>

<strong>Spiegazione</strong>: viene diviso il dataset iniziale in una serie di porzioni uguali di dati (k-campi) e ne uso iterativamente un tot per il train e un tot per il test. DA RIGUARDARE

</details>
</div>

---

<div class = "domanda1">
2. Nel caso di un <strong>albero di decisione</strong> con features discrete, cosa si può dire della profondità dell'albero?<br>
	-<span class="evidenzia_risposta"> È minore o uguale al numero delle features.</span><br>
	- È sicuramente maggiore del logaritmo in base due del numero dei dati.<br>
	- È minore o uguale del numero delle classi. <br>
	- Non si può dire nulla. <br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: È minore o uguale al numero delle features <br>

<strong>Spiegazione</strong>: La profondità massima è limitata dal numero di domande (features) uniche che puoi porre. Se hai N features, non puoi fare più di N passaggi prima di arrivare a una foglia.

</details>
</div>

---

<div class = "domanda1">
3. Che cosa si intende con <strong> apprendimento supervisionato </strong> ?<br>
	- Apprendimento che non fa uso di tecniche statistiche o probabilistiche<br>
	- Apprendimento che tende a imitare il comportamento di un esperto. <br>
	- Apprendimento sotto la supervisione diretta di un esperto. <br>
	- <span class="evidenzia_risposta">Apprendimento di funzioni basato su esempi di training composti da coppie input-output. </span> <br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Apprendimento di funzioni basato su esempi di training composti da coppie input-output.<br>

<strong>Spiegazione</strong>: Apprendimento supervisionato: vengono forniti sia valori di input, sia i valori di output (soluzioni). Nell'apprendimento supervisionato addestriamo la macchina dandole le soluzioni (etichette), affinché impari a dividere i dati o a calcolare valori numerici. Due categorie principali di apprendimento supervisionato: classificazione (output è categoria o una classe) e regressione (output è un numero continuo)

</details>
</div>

---

<div class = "domanda1">
4. Selezionare la sentenza <strong> ERRATA </strong> relativa all'<strong>entropia </strong> per la distribuzione di probabilità di una variabile aleatoria discreta<br>
	- Il range del suo valore è tra 0 e log n dove n sono i possibili valori di X <br>
	- Il suo valore è minimo (e uguale a 0) quando la probabilità è tutta concentrata in una classe <br>
	- <span class="risposta_errata">Il suo valore è minimo (e uguale a 0) quando la probabilità è equamente distribuita tra tutte le classi</span> <br>
	- È una misura del grado di disordine della variabile aleatoria<br>
	
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Il suo valore è minimo (e uguale a 0) quando la probabilità è equamente distribuita tra tutte le classi <br>

<strong>Spiegazione</strong>: L’entropia è massimizzata quando la X è uniforme su tutti i valori (1) e minima (0) quando è concentrata su un singolo valore. 


</details>
</div>

$$
H(X) = - \sum_{i=1}^{n} P(X=i)\log_2 P(X=i)
$$
---

<div class = "domanda1">
5. Selezionare la sentenza <strong> ERRATA </strong> relativa alla <strong>distribuzione congiunta</strong>di probabilità per N variabili aleatorie discrete<br>
	- <span class="risposta_errata">Richiede il calcolo di un numero esponenziale di parametri. </span> <br>
	- È la distribuzione di probabilità di tutte le possibili tuple di valori per le variabili. <br>
	- Non permette il calcolo di probabilità condizionali tra le features. <br>
	- Consente il calcolo delle probabilità marginali delle singole features <br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Richiede il calcolo di un numero esponenziale di parametri.<br>

<strong>Spiegazione</strong>: ?

</details>
</div>

---

<div class = "domanda1">
6. Selezionare la sentenza <strong> ERRATA </strong> relativa alla tecnica <strong>Naive Bayes</strong><br>
	- Fornisce un modo computazionalmente efficiente per approssimare la distribuzione congiunta di probabilità delle features <br>
	- Deriva dall'ipotesi teorica semplificativa che le features siano indipendenti tra loro, date le classi <br>
	- È una tecnica di tipo generativo in quanto cerca di determinare la distribuzione delle varie categorie dei dati <br>
	- <span class="risposta_errata"> Non può essere utilizzata se le features non sono tra loro indipendenti, date le classi </span> <br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Non può essere utilizzata se le features non sono tra loro indipendenti, date le classi <br>

<strong>Spiegazione</strong>: L'indipendenza delle feature è un'ipotesi teorica semplificativa, non un requisito tecnico bloccante. Nella realtà i dati hanno quasi sempre dipendenze, ma l'algoritmo si usa lo stesso e spesso funziona sorprendentemente bene perché l'approssimazione è sufficiente per classificare correttamente.

</details>
</div>

---

<div class = "domanda1">
7. Quale distribuzione di probabilità si assume abitualmente per una variabile obiettivo continua nel caso della tecnica <strong>Naive Bayes</strong>?<br>
	-Una distribuzione binomiale<br>
	-<span class="evidenzia_risposta">Una distribuzione Normale, ovvero Gaussiana(0,1)</span><br>
	-Una distribuzione uniforme in [0,1]<br>
	-Una distribuzione esponenziale<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Una distribuzione Normale, ovvero Gaussiana(0,1)  <br>

<strong>Spiegazione</strong>: Che cosa fare quando le features Xi sono continue? Per utilizzare Naive Bayes dobbiamo calcolare P(Xi|Y), ma quando Xi è continua, le probabilità puntuali sono nulle, per cui si parla di densità delle distribuzioni. Un approccio tradizionale consiste nel supporre che P(Xi|Y) abbia una distribuzione Gaussiana (detta anche Normale).

</details>
</div>

---

<div class = "domanda1">
8. Ci sono due monete, una normale e una che restituisce testa con probabilità 3/4 e croce con probabilità 1/4. Faccio due lanci con la stessa moneta e osservo una testa e una croce. Che cosa posso concludere?<br>
	-Nulla<br>
	-La probabilità di usare uno o l'altra moneta è esattamente la stessa<br>
	-È più probabile che la moneta sia truccata<br>
	-<span class="evidenzia_risposta">È più probabile che la moneta sia normale</span><br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: È più probabile che la moneta sia normale<br>

<strong>Spiegazione</strong>: Per capire il motivo si deve calcolare la probabilità di ottenere 1 testa e 1 croce con entrambe le monete e confrontare i risultati. <br>
1. <strong>Caso moneta normale</strong><br>
Probabilità Testa (T)=1/2<br>
Probabilità Croce (C)=1/2<br>
Scenario A: esce prima Testa e poi Croce: (1/2*1/2)<br>
Scenario B: esce prima Croce e poi Testa: (1/2*1/2)<br>
(1/2*1/2)+(1/2*1/2)=0.5<br>
2.<strong> Caso moneta truccata</strong><br>
Probabilità Testa (T)=3/4<br>
Probabilità Croce (C)=1/4<br>
(3/4*1/4)+(1/4*3/4)=6/16 (ovvero 0.375)<br>
Poiché 0.5 > 0.375 è più verosimile che i dati osservati provengano da una moneta normale

</details>
</div>

---

<div class = "domanda1">
9. Quale è l'obiettivo principale dell'algortimo di <strong>clustering K-means</strong>?<br>
	-Ridurre il numero dei clustersi al minimo<br>
	-Ottimizzare il numero dei clusters basandosi sulla distribuzione Gaussiana dei dati<br>
	-Trovare il punto medio del dataset<br>
	-<span class="evidenzia_risposta">Raggruppare i punti di un cluster attorno al loro centroide</span><br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Raggruppare i punti di un cluster attorno al loro centroide<br>

<strong>Spiegazione</strong>: K-means è un algoritmo di clustering basato su centroidi iterativo che suddivide un set di dati in gruppi simili sulla base della distanza tra i loro centroidi. Il centroide, o centro del cluster, è la media o la mediana di tutti i punti all'interno del cluster a seconda delle caratteristiche dei dati.

</details>
</div>

---
<div class = "domanda1">
10. Qual è il principale scopo della <strong>normalizzazione</strong> dei dati prima dell'addestramento di un modello di machine learning?<br>
	-Aumentare la precisione delle previsioni del modello.<br>
	-<span class="evidenzia_risposta">Garantire che tutte le feature abbiano la stessa scala, migliorando la convergenza dell'ottimizzazione.</span><br>
	-Evitare che i dati contengano valori mancanti.<br>
	-Ridurre il numero di parametri del modello.<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Garantire che tutte le feature abbiano la stessa scala, migliorando la convergenza dell'ottimizzazione.<br>

<strong>Spiegazione</strong>: ...

</details>
</div>

---

