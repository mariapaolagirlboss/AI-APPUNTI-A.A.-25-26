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

$$H(X) = - \sum_{i=1}^{n} P(X=i)\log_2 P(X=i)$$
- - -

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
Scenario A: esce prima Testa e poi Croce: (1/2 * 1/2)<br>
Scenario B: esce prima Croce e poi Testa: (1/2 * 1/2)<br>
(1/2 * 1/2)+(1/2 * 1/2)=0.5<br>
2.<strong> Caso moneta truccata</strong><br>
Probabilità Testa (T)=3/4<br>
Probabilità Croce (C)=1/4<br>
(3/4 * 1/4)+(1/4 * 3/4)=6/16 (ovvero 0.375)<br>
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

<div class = "domanda1 riprendere">
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

<div class = "domanda1">
11. Quale delle seguenti opzioni <strong>NON</strong> aiuta a <strong>ridurre l'overfitting</strong> in un modello di deep learning?<br>
	-<span class="risposta_errata">Aumentare il numero di epoche di addestramento</span><br>
	-Ridurre la complessità del modello per evitare un adattamento eccessivo ai dati di training.<br>
	-Aumentare la quantità di dati disponibili per l'addestramento.<br>
	-Utilizzare tecniche di regolarizzazione come dropout o weight decay<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Aumentare il numero di epoche di addestramento.<br>

<strong>Spiegazione</strong>: Addestrare troppo a lungo causa l'overfitting! Le altre opzioni (b, c, d) sono errate nel contesto del quiz proprio perché sono metodi efficaci per combattere l'overfitting. <br>
<strong>RIDURRE LA COMPLESSITÀ DEL MODELLO</strong>: semplificare il modello (meno strati, meno neuroni) riduce la sua "capacità". Un modello più semplice è costretto a imparare solo le regole generali (i pattern principali) e non riesce a memorizzare il "rumore" o i dettagli inutili dei dati di training.<br>
<strong>AUMENTARE LA QUANTITÀ DEI DATI DISPONIBILI</strong>: simile a imparare a memoria dati per un test, se ne ho troppi è impossibile farlo. Più dati sono forniti al modello, più è difficile per lui impararli tutti.<br>
<strong>USO DI TECNICHE DI REGOLARIZZAZIONE</strong>: è come mettere dei freni/penalità al modello.<br>
-<strong>Weight Decay</strong>: penalizza pesi troppo grandi nella rete neurale. Pesi grandi indicano che modello reagisce in modo esagerato a piccoli cambiamenti (overfitting).<br> 
-<strong>Dropout</strong>: durante addestramento spegne casualmente alcuni neuroni. Impedisce al modello di basarsi su specifico percorso, crea così strategie più robuste.

</details>
</div>

---

 <div class = "domanda1 riprendere">
12. Nella <strong>Principal Component Analysis</strong>, cosa indica la varianza spiegata da ciascuna componente?<br>
	-Indica la correlazione tra ciascuna componente e la variabile target<br>
	-<span class="evidenzia_risposta">Indica quanto una singola componente contribuisce alla varianza complessiva dei dati</span><br>
	-Indica la deviazione standard della componente rispetto alla media dei dati<br>
	-Misura la somma cumulativa delle differenze quadratiche tra le osservazioni e i valori predetti dalla componente<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Indica quanto una singola componente contribuisce alla varianza complessiva dei dati<br>

<strong>Spiegazione</strong>: ...

</details>
</div>

---

<div class = "domanda1">
13. Selezionare la sentenza <strong>ERRATA</strong> relativa alla <strong>probabilità condizionata</strong> P(A|B) tra due eventi A e B<br>
	-P(A|B) può essere maggiore di P(A)<br>
	-P(A|B) può essere inferiore a P(A)<br>
	-<span class="risposta_errata">P(A|B) è sicuramente minore o uguale di P(A and B)</span><br>
	-P(A|B) è sicuramente maggiore o uguale di P(A and B)<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Aumentare il numero di epoche di addestramento.<br>

<strong>Spiegazione</strong>:Essendo una probabilità, P(B) è un numero compreso tra 0 e 1. Cosa succede quando si divide un numero per qualcosa di più piccolo di 1? Il risultato diventa più grande.<br>
<strong>Esempio</strong>:<br>
Probabilità dell'intersezione P(A∩B) = 0,1 (10%).<br>
Probabilità di B P(B) = 0,5 (50%).<br>
P(A∣B)=0,1 / 0,5=0,2<br>
0,2 (il risultato) > 0,1 (l'intersezione).<br>
Opzione c afferma che P(A∣B)< P(A and B).<br>
Questo è matematicamente IMPOSSIBILE (a meno che P(A∣B) non sia zero). <br>
Dividendo l'intersezione per un numero decimale (P(B)), il risultato cresce, non diminuisce.
</details>
</div>

$$P(A \mid B) = \frac{P(A \cap B)}{P(B)}$$
---

 <div class = "domanda1">
14. Un dataset contiene 1/3 di positivi e 2/3 di negativi. La recall del modello è di 2/3. Che percentuale dei dati sono falsi negativi?<br>
	-Non può essere stabilito<br>
	-1/3<br>
	-<span class="evidenzia_risposta">1/9</span><br>
	-2/9<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: 1/9<br>

<strong>Spiegazione</strong>:<br>
2/3 = (TP) / 1/3 <br>
TP = 2/3 * 1/3 = 2/9, così abbiamo trovato i <strong>TRUE POSITIVES</strong><br>
Positivi = TP + FN, quindi 1/3 = 2/9 + FN <br>
FN = 1/3 - 2/9 = 1/9

</details>
</div>

$$
\begin{aligned}
\text{Positivi Totali (P)} &= TP + FN \\
\text{Negativi Totali (N)} &= TN + FP \\
\text{Totale Dati (All)} &= TP + TN + FP + FN \\
\\[10pt]
\text{Accuratezza} &= \frac{TP + TN}{\text{All}} \\
\\[10pt]
\text{Precisione} &= \frac{TP}{TP + FP} \\
\\[10pt]
\text{Richiamo (Recall)} &= \frac{TP}{TP + FN} \\
\\[10pt]
\text{Specificità} &= \frac{TN}{TN + FP} \\
\\[10pt]
\text{F1 Score} &= 2 \cdot \frac{\text{Precisione} \cdot \text{Recall}}{\text{Precisione} + \text{Recall}}
\end{aligned}
$$

---

 <div class = "domanda1 riprendere">
15. Selezionare la sentenza <strong>ERRATA</strong> relativa al learning rate<br>
	-Il learning rate può variare durante il training<br>
	-<span class="risposta_errata">È una metrica che misura la capacità di apprendimento del modello</span><br>
	-È un iper-parametro che definisce la lunghezza del passo durante la discesa del gradiente<br>
	-Un learning rate alto tipicamente velocizza il training ma potrebbe saltare sopra al minimo<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: È una metrica che misura la capacità di apprendimento del modello<br>

<strong>Spiegazione</strong>: ...

</details>
</div>

---

<div class = "domanda1 riprendere">
16. Selezionare la sentenza corretta riguardo alla <strong>regressione logistica</strong>?<br>
	-La predizione non dipende dal bilanciamento dei dati di training rispetto alle classi<br>
	-<span class="evidenzia_risposta">I parametri del modello sono tipicamente calcolati mediante discesa del gradiente</span><br>
	-I parametri del modello possono essere tipicamente calcolati in forma chiusa, mediante una formula esplicita<br>
	-Il calcolo della predizione non si basa sulla loglikelihood dei dati di training, in quanto si tratta di una tecnica discriminativa<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: I parametri del modello sono tipicamente calcolati mediante discesa del gradiente<br>

<strong>Spiegazione</strong>: <br>
regressione logistica molto sensibile al bilanciamento delle classi(...)<br>
i parametri <strong>non</strong> possono essere calcolati in forma chiusa (si parlerebbe di regressione lineare)<br>
Calcolo non si basa su loglikelyhood: Regressione logistica è un metodo discriminativo, ma la funzione standard per trovare parametri migliori è MLE (...)

</details>
</div>

---

<div class = "domanda1">
17. Selezionare la sentenza <strong>SCORRETTA</strong> relativa ai <strong>neuroni artificiali</strong><br>
	-<span class="risposta_errata">Un neurone artificiale può apprendere qualunque funzione dei suoi input</span><br>
	-Un neurone artificiale definisce un semplice modello matematico che simula il neurone biologico.<br>
	-Un neurone artificiale tipicamente calcola una combinazione lineare dei suoi input, seguita dalla applicazione di una funzione di attivazione non lineare.<br>
	-Il numero dei parametri di un neurone artificiale è lineare nel numero dei suoi input.<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Un neurone artificiale può apprendere qualunque funzione dei suoi input.<br>

<strong>Spiegazione</strong>: 
<strong>Calcolo di combinazione lineare degli input...</strong>: corretto! Prima fa la somma pesata (z = w1​x1​ + w2​x2​ + ... + b) e poi applica una non-linearità (come la Sigmoide o la ReLU) al risultato.<br>
<strong>Numero dei parametri...</strong>: Se un neurone ha N input, avrà N pesi (uno per ogni input) più 1 bias. Quindi i parametri totali sono N+1...riguarda...Pesi collegati a input (?).<br>
<br>
Un singolo neurone artificiale è limitato. Matematicamente, un singolo neurone è un classificatore lineare: può risolvere solo problemi dove i dati possono essere separati da una linea retta (o un iperpiano). <strong>Esempio classico</strong>: Un singolo neurone non può imparare la funzione logica XOR, perché non è linearmente separabile. Per apprendere "qualunque funzione" serve una rete di neuroni (con almeno uno strato nascosto), non un neurone da solo.


</details>
</div>
![[Screenshot 2025-11-24 alle 15.44.48.png|321x113]]

$$ y = f\left( \sum_{i=1}^{n} w_i x_i + b \right) $$
---

<div class = "domanda1">
18. Cosa si intende con <strong>"deep" features</strong>?<br>
	-Features ottenute mediante utilizzo di sensori ottici di profondità<br>
	-<span class="evidenzia_risposta">Features sintetizzate in modo automatico a partire da altre features</span><br>
	-Features soggette a una approfondita supervisione da parte umana<br>
	-Features relative a dati in 2 o più dimensioni<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Features sintetizzate in modo automatico a partire da altre features<br>

<strong>Spiegazione</strong>: Deep Learning exploits deep features of data, that is features extracted from other features.

</details>
</div>

---

<div class = "domanda1 riprendere">
19. Selezionare la sentenza <strong>SCORRETTA</strong> relativa alla <strong>backpropagation</strong> per reti neurali<br>
	-E' l'algoritmo per il calcolo della derivata parziale della loss rispetto a ogni parametro della rete<br>
	-Si riduce a semplici calcoli algebrici facilmente parallelizzabili in strutture di calcolo tipo GPU<br>
	-L'algoritmo calcola il gradiente un layer alla volta, sfruttando la regola matematica per la derivazione di funzioni composte<br>
	-<span class="risposta_errata">Tipicamente, il gradiente viene artificialmente rinforzato ad ogni layer attraversato per contrastare il fenomeno della sua scomparsa (vanishing)</span><br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Tipicamente, il gradiente viene artificialmente rinforzato ad ogni layer attraversato per contrastare il fenomeno della sua scomparsa (vanishing)<br>

<strong>Spiegazione</strong>: ...

</details>
</div>

---

<div class = "domanda1">
20. Quale è l'effetto tipico della <strong>riduzione della dimensione del minibatch</strong> durante il training?<br>
	-La Backpropagation è effettuata meno frequentemente e l'aggiornamento dei parametri è meno accurato<br>
	-<span class="evidenzia_risposta">La Backpropagation è effettuata più frequentemente ma l'aggiornamento dei parametri è meno accurato</span><br>
	-La Backpropagation è effettuata meno frequentemente ma l'aggiornamento dei parametri è più accurato<br>
	-La Backpropagation è effettuata più frequentemente e l'aggiornamento dei parametri è più accurato<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: La Backpropagation è effettuata più frequentemente ma l'aggiornamento dei parametri è meno accurato<br>

<strong>Spiegazione</strong>: If we <strong>decrease</strong> the batchsize we <strong>update more frequently</strong> (that is good), but updates are <strong>less accurate</strong>, since we are backpropagating form a loss relative to very specific data. Conversely, if we increase the batchsize, updates grow in accuracy (the ideal would be to compute them on the whole training set- fullbatch) but training can be slow, since parameters are too rarely updated.

</details>
</div>

---

<div class = "domanda1">
21. Selezionare la sentenza <strong>SCORRETTA</strong> relativa <strong>all'overfitting</strong><br>
	-Può essere contrastata con tecniche di regolarizzazione<br>
	-<span class="risposta_errata">L'acquisizione di nuovi dati di training non può che peggiorare la situazione.</span><br>
	-Può essere particolarmente pericolosa per modelli altamenti espressivi<br>
	-Può essere contrastata con la tecnica di early stopping durante la fase di training<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: L'acquisizione di nuovi dati di training non può che peggiorare la situazione<br>

<strong>Spiegazione</strong>: <br>
<strong>Early stopping</strong>: L'arresto anticipato interrompe la fase di addestramento prima che il modello di machine learning riconosca il rumore nei dati. Tuttavia, è importante che i tempi siano corretti, altrimenti il modello non darà risultati accurati.<br>
<strong>Tecniche di regolarizzazione</strong>: pensa a dropout o weight decay. <br>
<strong>Pericolosa per modelli espressivi</strong>: maggiore è l'espressività del modello, maggiore è il rischio di overfitting. Un modello poco espressivo deve basarsi su regole generali per memorizzare i dati e ignora il rumore delle immagini, un modello molto espressivo no. 


</details>
</div>

---

<div class = "domanda1">
22. Il problema della scomparsa del gradiente (vanishing gradient) si riferisce a una progressiva diminuzione dell'intensità del gradiente, dovuta a: <br>
	-Training eccessivamente lungo<br>
	-Dati troppo rumorosi o malamente preprocessati<br>
	-Troppi pochi dati di training a disposizione<br>
	-<span class="evidenzia_risposta">Backpropagation in reti profonde</span><br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Backpropagation in reti profonde<br>

<strong>Spiegazione 1</strong>: If you systematically use the sigmoid as activation function in all layers of a deep network, the gradient will contain a lot of factors below 0.25, resulting in a very small value. If the gradient is close to zero, learning is impossible. This is known as the vanishing gradient problem.<br>
<strong>Spiegazione 2</strong>: <br>
<strong>Backpropagation</strong>: algoritmo calcola i gradienti moltiplicando le derivate di ogni strato, partendo dalla fine verso l'inizio (Chain Rule)<br>
<strong>Limite della sigmoide</strong>: la derivata della sigmoide è sempre molto piccola<br>
<strong>Effetto della profondità</strong>: in una rete profonda, la backpropagation costringe a moltiplicare 0.25 (...)per se stesso moltissime volte, il quale diventa rapidamente quasi zero. Il segnale di errore si """spegne""" prima di arrivare ai primi strati, rendendo impossibile apprendimento(...)


</details>
</div>

---

<div class = "domanda1">
23. Quale è lo scopo dell'<strong>optimizer</strong> in <strong>Tensorflow/Keras?</strong> <br>
	-<span class="evidenzia_risposta">Definire l'algoritmo che calcola i gradienti della loss e aggiorna i pesi del modello</span><br>
	-Salvare i migliori pesi del modello durante il processo di training<br>
	-Aggiungere una penalità ai pesi del layer su cui viene istanziato<br>
	-Contrastare overfitting<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Definire l'algoritmo che calcola i gradienti della loss e aggiorna i pesi del modello<br>

<strong>Spiegazione</strong>: <br>
-<strong>Salvare migliori pesi del modelli...</strong>: compito dei Callbacks, il compito dell'optimizer è modificare i pesi, non salvarli o decidere quale sia il migliore.<br>
-<strong>Aggiungere penalità ai pesi...</strong>: questo si riferisce a regolarizzazione.<br>
-<strong>Contrastare overfitting</strong>: obiettivo optimizer è di minimizzare errore, non si preoccupa di generalizzazione/overfitting.<br>
<br>
<strong>Optimizer</strong>: The tool in charge of governing the gradient descent technique, possibly dynamically adapting the learning rate, is the so called optimizer.
</details>
</div>

---

<div class = "domanda1">
24. Quale delle seguenti <strong>NON</strong> è una applicazione tipica degli <strong>autoencoders</strong>?<br>
	-Rilevamento di anomalie (anomaly detection)<br>
	-Rimozione del rumore (denoising)<br>
	-<span class="risposta_errata">Segmentazione di immagini (semantic segmentation)</span><br>
	-Riduzione delle dimensioni (dimensionality reduction)<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Segmentazione di immagini (semantic segmentation<br>

<strong>Spiegazione</strong>: hanno applicazioni per la data denoising, anomaly detection, feature extraction e generative models
</details>
</div>

---

<div class = "domanda1">
25. Qual è il principale vantaggio delle <strong>connessioni residue</strong> (skip connections) in una <strong>ResNet</strong>?<br>
	-Riducono il numero di parametri da ottimizzare nel modello<br>
	-<span class="evidenzia_risposta">Permettono una migliore gestione del problema del vanishing gradient.</span><br>
	-Permettono di evitare l’overffitting durante l'addestramento<br>
	-Migliorano la velocità di calcolo durante l'addestramento<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Permettono una migliore gestione del problema del vanishing gradient.<br>

<strong>Spiegazione</strong>: In order to solve the problem of the vanishing/exploding gradient, this architecture introduced the concept called <strong>Residual Blocks</strong>. In this network, we use a technique called <strong>skip connections</strong>. The skip connection connects activations of a layer to further layers by skipping some layers in between, this forms a residual block. Resnets are made by stacking these residual blocks together.<br>
<strong>Riducono il numero di parametri...</strong>: le skip connections non riducono i parametri. Il numero di parametri rimane identico (o aumenta leggermente), poiché si tratta semplicemente di una somma elemento per elemento dell'input con l'output dello strato.<br>
<strong>Evitare overfitting</strong>: Lo scopo delle skip connections non è la regolarizzazione ma l'abilitazione dell'addestramento in profondità.<br>
<strong>Miglioramento velocità di calcolo</strong>: non migliorano la velocità di calcolo, la rete è di solito più profonda e complessa.
</details>
</div>

---

<div class = "domanda1 riprendere">
26. Seleziona la sentenza corretta relativa alle <strong>Transposed Convolutions</strong>.<br>
	-Sono prevalentemente utilizzate in architetture per classificazione di immagini.<br>
	-Sono essenzialmente equivalenti all'applicazione di un livello di downsampling seguito da una convoluzione normale.<br>
	-<span class="evidenzia_risposta">Possono essere interpretate come convoluzioni normali con stride sub-unitario.</span><br>
	-Nessuna delle altre risposte è corretta.<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Possono essere interpretate come convoluzioni normali con stride sub-unitario.<br>

<strong>Spiegazione</strong>: ...

</details>
</div>

---

<div class = "domanda1">
27. Selezionare la sentenza <strong>SCORRETTA</strong> relativa alle <strong>Generative Adversarial Networks</strong><br>
	-Durante la fase di allenamento del Generatore i parametri del Discriminatore devono essere congelati, e viceversa<br>
	-Le GAN possono soffrire del fenomeno di "mode collapse", cioè la tendenza a focalizzare la generazione su un unico o pochi esempi<br>
	-<span class="risposta_errata">Le GANs sono utilizzate per generare attacchi ad una rete di classificazione prefissata</span><br>
	-Le GAN basano il loro training su un game tra il Generatore e il Discriminatore, dove ognuno cerca di prevalere sull'altro<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Le GANs sono utilizzate per generare attacchi ad una rete di classificazione prefissata<br>

<strong>Spiegazione</strong>: <br>
<strong>Mode collapse</strong>: In machine learning, mode collapse is a failure mode observed in generative models, originally noted in Generative Adversarial Networks (GANs). Mode collapse in Generative Adversarial Networks (GANs) can be likened to a talented artist who creates a popular artwork. After the work gains popularity, the artist may be afraid to take risks and start producing similar works. This can lead to a lack of artistic exploration and eventually bore the audience. Similarly, in GANs, mode collapse happens when the generator focuses on producing a limited set of data patterns that deceive the discriminator. It becomes fixated on a few dominant modes in the training data and fails to capture the full diversity of the data distribution.
<strong>Parametri congelati</strong>: You have to manually stop keras from training the discriminator when you train the generator - if we didn’t do this, the discriminator would learn to be more convinced by the generator every time the generator is trained, undoing anything useful it could have learned! La frase "the discriminator would learn to be more convinced by the generator" significa questo: Se tu permettessi a entrambi di imparare durante il turno del Generatore, il Discriminatore imparerebbe che per "vincere" (minimizzare l'errore in quel momento specifico) gli basta dire "Sì, è tutto vero!"<br>
<strong>Generare attacchi: perché è errata?</strong>: La frase descrive gli Adversarial Attacks, non le GANs. Il discriminatore non è prefissato, deve evolvere e imparare contemporaneamente al generatore.


</details>
</div>

---

<div class = "domanda1">
28. Selezionare la sentenza <strong>SCORRETTA</strong> relativa alla <strong>U-Net</strong><br>
	-Spesso impiegata per problemi di segmentazione semantica di immagini<br>
	-<span class="risposta_errata">Spesso utilizzata nell'ambito della classificazione dei generi musicali</span><br>
	-Usata per rimozione del rumore (denoising) di immagini<br>
	-Componente tipico dei modelli generativi a diffusione<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Spesso utilizzata nell'ambito della classificazione dei generi musicali.<br>

<strong>Spiegazione</strong>: <br>
<strong>Impiegata per segmentazione...</strong>: U-Net is a convolutional neural network that was developed for image segmentation. The network is based on a fully convolutional neural network.<br>
<strong>Denoising</strong>: The U-Net architecture has also been employed in diffusion models for iterative image denoising.<br>
<strong>Componente modelli generativi a diffusione</strong>: The U-Net architecture has also been employed in diffusion models for iterative image denoising.<br>
La U-Net è un'architettura progettata specificamente per la <strong>Segmentazione Semantica</strong> non per la <strong>Classificazione</strong>.


</details>
</div>

---

<div class = "domanda1">
29. Con <strong>modelli generativi</strong> si intende:<br>
	-L'uso di attacchi avversariali allo scopo di aumentare la robustezza dei modelli<br>
	-<span class="evidenzia_risposta">Modelli che cercano di apprendere la distribuzione di probabilità dei dati.</span><br>
	-L'applicazione di tecniche genetiche al deep learning<br>
	-Il processo di automatizzazione della generazione di reti neurali<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>:Modelli che cercano di apprendere la distribuzione di probabilità dei dati.<br>

<strong>Spiegazione</strong>: A generative model is a model that tries to learn the actual distribution Pdata of real data from available samples (training set).
</details>
</div>

---

<div class = "domanda1">
30. Selezionare la sentenza <strong>SCORRETTA</strong> relativa ai <strong>modelli a diffusione</strong><br>
	-<span class="risposta_errata">Generano i risultati attraverso un processo di diffusione della informazione</span><br>
	-Tipicamente, lo spazio latente ha la stessa dimensione dello spazio visibile<br>
	-Il risultato è ottenuto attraverso passaggi multipli lungo una singola rete, tipicamente una U-net<br>
	-I modelli a diffusione iterano una operazione di denoising<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Generano i risultati attraverso un processo di diffusione della informazione. <br>

<strong>Spiegazione</strong>: <br>
<strong>Risultato ottenuto tramite U-net...</strong>: corretto, mostrato in ppt cartabinaria 07 modelli generativi ultima slide (...)<br>
<strong>Modelli a diffusione iterano operazione di denoising</strong>: as of 2024, diffusion models are mainly used for computer vision tasks, including image denoising, inpainting, super-resolution, image generation, and video generation.<br>
<strong>Spazio latente ha stessa dimensione spazio visibile</strong>: 


</details>
</div>

---

<div class = "domanda1">
31. Selezionare la sentenza <strong>SCORRETTA</strong> relativa agli <strong>alberi di decisione</strong><br>
	-<span class="risposta_errata">Possono essere utilizzati solo con features discrete</span><br>
	-Costo computazionale molto basso<br>
	-Forte tendenza all'overfitting<br>
	-Possono esprimere qualunque funzione di classificazione<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>: Possono essere utilizzati solo con features discrete. <br>

<strong>Spiegazione</strong>: <br>
<strong>Possono esprimere qualunque funzione di classificazione</strong>: Decision Trees are a non-parametric supervised learning method used for classification and regression.


</details>
</div>

---

<div class = "domanda1">
32. Perché la tecnica <strong>Naive Bayes</strong> è detta naive?<br>
	-<span class="evidenzia_risposta">Suppone ingenuamente che le features siano indipendenti tra loro, date le classi</span><br>
	-Suppone che i dati di training rispecchino i dati reali<br>
	-Fornisce un modo semplice ma preciso di calcolare la distribuzione congiunta di probabilità delle features<br>
	-Suppone che la teoria possa avere applicazioni pratiche<br>
<details>
<summary> Clicca qui per la soluzione e la spiegazione</summary>

<strong>Risposta corretta</strong>:Suppone ingenuamente che le features siano indipendenti tra loro, date le classi.<br>

<strong>Spiegazione</strong>: abbastanza straightforward
</details>
</div>

---

