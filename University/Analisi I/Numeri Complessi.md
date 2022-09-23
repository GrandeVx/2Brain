


>  I **numeri complessi** costituiscono un insieme che *estende* l'insieme dei numeri reali ed in cui, partire dalla definizione di **unità immaginaria**


##### Come nascono i numeri complessi

Nell'insieme **R** dei numeri reali, definito come l'unione tra gli insiemi dei numeri razionali e dei numeri irrazionali, tutto sembrerebbe funzionare al meglio;

Se però ci chiedessero ad esempio:

- Di calcolare la **radice quadrata** di -1
- di trovare gli zeri del **polinomio** $\ p(x) = x^2 + 1$

Proprio per questo motivo i matematici hanno sentito l'esigenza di espandere i propri orizzonti e di definire l'insieme dei numeri complessi.

##### Definizione di numero complesso

Riprendendo gli esempi abbiamo già detto che in **R** non è  possibile trovare le soluzioni dell'equazione di secondo grado $$\ x^2 + 1 = 0 <=> x^2 = -1$$ Poichè sappiamo non esistere nessun numero nell'insieme **R** il cui quadrato sia uguale a -1

Partendo da tale equazione si introduce il valore *i* detto **unità immaginaria** e definito come la *radice quadrata* di **-1** $$ i := \sqrt{-1}$$ dove il *simbolo* $\ :=$ si legge **uguale per definizione**

Ecco quindi che l'equazione di secondo grado $\ x^2 + 1 = 0$ ammette soluzioni. In particolare ammetterà due radici complesse distinte $\ x_1 = i, x_2 = -i$, infatti: $$ x^2 + 1 = 0 <=> x^2 = -1 <=> x = \pm\sqrt{-1} <=> x = \pm i$$
	Dopo aver introdoto *l'unità immaginaria* possiamo definire **l'insieme dei numeri complessi** che d'ora in poi indicheremo con la lettera **C** come l'insieme di tutti e soli in numeri della forma $$ a + ib \space con \space a,b \in R$$
	Quella appena scritta si dice **forma algebrica di un numero complesso** 


##### Parte reale e parte immaginaria di un numero complesso

sia $\ z = a+ib$ un qualsiasi numero complesso. 

il *numero reale* **a** prende il nome di **parte reale** e si indica con $\ Re(z)$ mentre **b** si dice **parte immaginaria** del numero complesso e viene indicata con $\ Im(z)$ 
$$ z = a+ib \space -> \left[ 
	\begin{align}
	Re(z) = a \space parte \space reale \\
	Im(z) = b \space parte \space immaginaria
	\end{align} \right]$$
Ad esempio $\ 2 + 3i$ è il numero complesso avente **parte reale** a 2 e **parte complessa** uguale a 3, mentre $\ 1 + i$ ha **parte reale** e **parte complessa** uguali ad 1

> I numeri complessi aventi *parte reale nulla*, ossia i numeri della forma $\ z = ib$, con $\ b \in R$ si dicono **immaginari puri**. Lo sono ad esempio $\ 2i, \space -3i, \space \sqrt{5}i$
> Di contro,  numeri complessi con *parte immaginaria nulla*, vale a dire quelli della forma $\ z = a \space con \space a \in R$ sono **tutti e soli i numeri reali**

Risulta allora evidente che l'insieme dei numeri reali è un **sottoinsieme proprio** dell'insieme dei *numeri complessi*

##### Piano di Argand-Gauss

Per quanto riguarda i *numeri complessi*, è possibile individuare una corrispondenza biunivoca tra gli elementi dell'insieme **C** e i punti del piano,  detto **piano complesso** o **piano di Argand-Gauss**

> Al numero complesso $\ z = a + ib$ si associa il punto del piano di *cordinate cartesiane* $\ (a,b) = (Re(z), Im(z))$ $$ a + ib = (a,b)$$

In parole povere il piano di **Argand-Gauss** è un *piano cartesiano* leggermente modificato: *l'asse x* infatti è chiamato **asse reale** *l'asse y* è detto **asse immaginario**

Dato quindi il numero complesso $$ z =  a + ib $$
sull'**asse reale** individueremo la parte *reale* $\ Re(z) = a$ mentre sull'**asse immaginario** individueremo la parte *immaginaria* $\ Im(z) = b$

###### Esempio Pratico

> al numero complesso $\ z = -3+ 2i$ corrisponde il punto di cordinate cartesiane $\ (-3,2)$  così come mostrato in figura

![[Argand-Gauss.png]]