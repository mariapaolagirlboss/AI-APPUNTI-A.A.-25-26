**INDICE**
[🅐](#a) | [🅑](#b) | [🅒](#c) | [🅓](#d) | [🅔](#e) | [🅕](#f) | [🅖](#g) | [🅗](#h) | [🅘](#i) | [🅙](#j) | [🅚](#k) | [🅛](#l) | [🅜](#m) | [🅝](#n) | [🅞](#o) | [🅟](#p) | [🅠](#q) | [🅡](#r) | [🅢](#s) | [🅣](#t) | [🅤](#u) | [🅥](#v) | [🅦](#w) | [🅧](#x) | [🅨](#y) | [🅩](#z)

## A
- **Aleatoria** (variabile): denota l’esito di un fenomeno riguardo al quale sussiste incertezza, come ad esempio il risultato di un processo stocastico.
		vedi anche *multivalore*
- 
## B
- **Bagging**: tecnica attraverso la quale si allenano i modelli su sottoinsiemi random (bags) dei dati di input
## C
- **Campionario** (spazio): insieme $\Omega$ dei possibili esiti di un esperimento casuale
- **Congiunta** (distribuzione): 
	1. costruire una tabella con tutte le possibili combinazioni dei valori delle features.
	2. stimare la probabilità per ogni combinazione di valori.
	Date *n* features booleane dobbiamo stimare $2^n-1$ parametri
- **Continuo** (attributo): un attributo con valori continui ha molti valori. Tuttavia, in questo caso la variabilità dei valori non accresce l'informazione bensì la riduce (vedi [[Link per argomento]])
## D
## E
- **Entropia**: misura il numero medio di bits richiesti per trasmettere il valore prodotto da una sorgente stocastica X. Misura il grado di impurità dell'informazione. 
	$$
H(X) = -\sum_{i=1}^{n} P(X=i) \log_2 P(X=i)
$$
- **Evento** (probabilità): è un qualche sottoinsieme di $\Omega$ 
## F
- **Feature randomness**: tecnica che porta alla costruzione di alberi a partire da sottoinsiemi random delle features
- **Foreste**: Gli alberi di decisione sono abitualmente utilizzati come componenti delle cosiddette Random Forests, dove sono utilizzati con una tecnica ad ensemble.

## G
## H
## I
## J
## K
## L
## M
## N
## O
- **Overfitting**: ipotesi h “overfitta” il set di training se esiste un’ipotesi h’ che dal training aumenta la percezione dell’errore e lo diminuisce dal data set.
		- **esempio**: 
			modello h soffre di overfitting se: $error_{train}(h) < error_{train}(h')$
			Durante l'allenamento, il modello h va alla grande! Fa meno errori del modello alternativo h′. Sembra il migliore. Lo studente che impara a memoria (h) prende 30 e lode nelle simulazioni perché ricorda le risposte esatte, mentre lo studente che impara i concetti (h′) prende 26.
			$error_{\mathcal{D}}(h) > error_{\mathcal{D}}(h')$
			Ma nel mondo reale (o su dati nuovi), la situazione si ribalta. Il modello h fa più errori del modello h′. All'esame vero, le domande cambiano leggermente. Lo studente (h) va nel panico e viene bocciato (errore alto), mentre lo studente (h′) ragiona e passa l'esame (errore più basso).
- 
## P
## Q
## R
## S
- **Stocastica** (sorgente) / (teoria dei processi): La teoria dei processi stocastici riguarda lo studio dei sistemi che evolvono nel tempo e/o nello spazio secondo leggi probabilistiche.
## T
- **Training set**: utilizzato per scegliere ipotesi h (overfitting)
## U
## V
- **Validation set**: utilizzato per misurare accuracy e overfitting h 
## W
## X
## Y
## Z
