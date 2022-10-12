## Principio di Induzione

###### TODO | Sottolineare e scrivere esempi

> il **Principio di Induzione**, detto anche *procedimento induttivo*, è una tecnica di dimostrazione che consente di **dimostrare** la *validità* di una tesi della verifica di due condizioni: la validità del *passo zero* e la *validità* del *passo induttivo*

### Quando usare il Principio di Induzione

Il Principio di Induzione si utlizza quando è richiesta la dimostrazione di una proprietà, di un teorema o ancora di una proposizione il cui enunciato è formulato in funzione dei **numeri naturali** $$"Dimostrare \space che \space per \space ogni \space n \in \mathbb{N} \space vale \space pincopalla"$$
### Come funziona il Principio di Induzione

Riprendendo quello scritto sopra sostituiamo il nostro "pincopalla" con una **proprietà** $P(n)$, il **principio di induzione** stabilisce che, se valgono le seguenti condizioni.

1. **(Passo Zero)**  $P(n)$ è *vera* per $n =0$ cioè $P(0)$ è *vera*;
2. **(Passo Induttivo)** supponedo che $P(n)$ sia *vera*, ne **consegue** che $P(n+1)$ è *vera*. In altri termini $P(n) => P(n+1)$ *vera*

Allora $P(n)$ è *vera* per **tutti** gli $n \in \mathbb{N}$.

### Spiegazione sul principio di induzione

 Distaccandoci dalla matematica, immaginiamo di aver costruito un robot privo di inteligenza in grado di eseguire tutti i nostri comandi vocali. Vogliamo far costruire al robot una casa di due piani fatta di mattoni. Gli Daremo le seguenti istruzioni:

- Costruisci il piano terra assemblando sei pezzi; uno per il pavimento, quattro per i muri laterai ed uno per il solaio;
- Partendo dal solaio del piano terra assembla altri sei pezzi,quattro per i muri laterai ed uno per il solaio;

La Casa è quindi ufficialmente Costruita.

Supponiamo ora di voler far costruire al robot una casa di dieci,cento,mille paini... Potremmo come nel caso precedente spiegargli piano per piano impiegandoci un sacco di tempo... in alternativa potremmo:

- Spiegargli come costruire il piano terra (passo zero)
- Dirgli come costruire un piano qualsiasi a partire dal precedente (passo induttivo)

Considerata la seguente analogia vediamo:

- il palazzo di infiniti piani come alla **proposizione** $P(n)$ di cui vogliamo dimostrare la **validità** per ogni $n \in \mathbb{N}$
- Alla costruzione del piano terra come la verifica della *base di induzione* cioè la validità di $P(0)$ 
- All'ipotesi di aver costruito un generico piano come all'**ipotesi induttiva**, ossia all'ipotesi secondo cui $P(n)$ è vera;
- alla costruzione del piano successivo partendo dal precedente come la verifica del **passo induttivo** ossia alla verifica della validità dell'implicazione $P(n) => P(n+1)$ 


### Come usare il principio di Induzione 

Supponiamo di dover **dimostrare** che una certa proprietà $P(n)$ vale per ogni $n \in \mathbb{N}$,o eventualmente per ogni $n \geq k$ con $k$ un certo *numero naturale*. Procederemo nel modo seguente.

1. **Base di induzione**
	- Si esprime la proprietà $P(n)$ da dimostrare con il valore iniziale $n = k$ e si verifica che la proprietà ottenuta è vera. In altri termini si verifica che la propietà  $P(k)$ sia soddisfatta.
2. **Passo Induttivo**
	- **(2a)** si suppone che sia vera $P(n)$.. Attenzione !! Dobbiamo suppore che sia vera e non **dimostrarlo**
	- **(2b)** sI considera la propietà per $n+1$ ossia $P(n+1)$ e si dimostra che l'ipotesi per cui $P(n)$ è vera implica che  $P(n+1)$ è vera. Attenzione dobbiamo mostrare che la validità di $P(n)$ implica la validità di $P(n+1)$. In questo modo varrà per qualsiasi *iterazione*

A proposito di **(2b)**, all'atto pratico dovremo lavorare algebricamente o di puro ragionamento, e fare in modo di individuare un'opportuna relazione che esprima la proprietà