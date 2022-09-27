\## Numeri Complessi

>  I **numeri complessi** costituiscono un insieme che *estende* l'insieme dei numeri reali ed in cui, partire dalla definizione di **unità immaginaria**

##### Come nascono i numeri complessi

Nell'insieme **R** dei numeri reali, definito come l'unione tra gli insiemi dei numeri razionali e dei numeri irrazionali, sembrerebbe funzionare al meglio;

Se però ci chiedessero ad esempio:

- Di calcolare la **radice quadrata** di -1
- di trovare gli zeri del **polinomio** $\ p(x) = x^2 + 1$

Proprio per questo motivo i matematici hanno sentito l'esigenza di espandere i propri orizzonti e di definire l'insieme dei numeri complessi.

##### Definizione di numero complesso

Riprendendo gli esempi abbiamo già detto che in **R** non è  possibile trovare le soluzioni dell'equazione di secondo grado $$\ x^2 + 1 = 0 <=> x^2 = -1$$ Poichè sappiamo non esistere nessun numero nell'insieme **R** il cui quadrato sia uguale a -1

Partendo da tale equazione si introduce il valore *i* detto **unità immaginaria** e definito come la *radice quadrata* di **-1** $$ i := \sqrt{-1}$$ dove il *simbolo* $\ :=$ si legge **uguale per definizione**

Ecco quindi che l'equazione di secondo grado $\ x^2 + 1 = 0$ ammette soluzioni. In particolare ammetterà due radici complesse distinte $\ x_1 = i, x_2 = -i$, infatti: $$ x^2 + 1 = 0 <=> x^2 = -1 <=> x = \pm\sqrt{-1} <=> x = \pm i$$
	Dopo aver introdoto *l'unità immaginaria* possiamo definire **l'insieme dei numeri complessi** che d'ora in poi indicheremo con la lettera **C** come l'insieme di tutti e soli in numeri della forma $$ a + ib \space con \space a,b \in R$$
	Quella appena scritta si dice [[#Forma algebrica di un numero Complesso]]


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


##### Numeri Complessi come coppia ordinata

> I numeri complessi della forma $\ (a,0)$ coincidono con i **numeri reali**, mentre i numeri del tipo $\ (0,b)$ sono **immaginari puri**

L'**unità immaginaria** $\ i$ è il numero complesso immaginario puro che si indentifica con la coppia ordinata $\ i = (0,1)$ 

###### Somma e Prodotto

Si definiscono **Somma e prodotto di due numeri complessi** $\ z = (a,b) \space e \space w = (c,d)$ nel modo seguente:
$$ z + w = (a,b) + (c,d) = (a+c,b+d)$$
$$ zw = (a,b)(c,d) = (ac - bd, bc + ad)$$


##### Elemento Neutro, opposto, inverso di un numero complesso

>  Nell insieme dei *numeri reali* sappiamo che **0 e 1** sono gli *elementi neutri* rispetto alla somma ed al prodotto e che se $\ a$ è un numero **reale** diverso da 0 , $\ -a$ è il suo **opposto** e $\frac{1}{a} = a^-1$ è il suo **inverso** (o *reciproco*) 

Anche nell'insieme dei *numeri complessi* possiamo definire tali quantità, In particolare:

1. $\ (0,0)$ è l'**elemento neutro rispetto alla somma**; graficamente coincide con *l'origine degli assi* del piano complesso
2. $\ (-a,-b)$ è l'**opposto del numero compless** $\ (a,b)$; graficamente l'opposto di un numero complesso è il *simmetrico* rispetto agli *assi di origine*
3. $\ (1,0)$ è l'**elemento neutro rispetto al prodotto**;
4. $\ z^-1 = (\frac{a}{a^2 + b^2},\frac{-b}{a^2 + b^2})$ è l'**inverso moltiplicativo** di $\ z = (a,b) \space con \space a \neq 0 \land b \neq 0$

#### Forma algebrica di un numero Complesso

La **Forma algebrica** di un *numero complesso* è una rappresentazione che permette di esprimere un qualsiasi numero complesso $z$ esplicitandone la *parte reale* $\ Re(z)$ e la *parte immaginaria* $\ Im(z)$, nella forma $\ z = Re(z) + i \bullet Im(z)$.

Un numero complesso$\ z \in \mathbb{C}$ è epresso in *forma algebrica se si presenta come* $$ z = a + ib \space con \space a,b \in \mathbb{R}$$
dove$\ i$ indica l'*unità immaginaria*. I numeri reali $\ a,b$ vengono detti rispettivamente parte reale e parte immaginaria del numero complesso$\ z$ e si indicano con i simboli $\ Re(z),Im(z)$ 
$$ z = a+ib \space -> \left[ 
	\begin{align}
	Re(z) = a \space parte \space reale \\
	Im(z) = b \space parte \space immaginaria
	\end{align} \right]$$
###### Esempi

1. $\ 1 + 3i$
2. $\sqrt{2} - 7i$
3. $\ \Pi + \sqrt{3}i$
4. $\ -15 + i$
5. $\ ln(5) + 12i$


##### Come si ricava la forma algebrica dalla definizione di complesso

L'insieme dei *numeri complessi* si definisce come l'insieme di tutte e sole le coppie ordinate di *numeri reali*, ossia $$ \mathbb{C} = \mathbb{R}^2 = {(a,b) \space | \space a,b \in \mathbb{R}}$$
Abbiamo poi detto che la *coppia ordinata* $\ (0,1)$ è, **per definizione**, l'unità immaginaria e che le coppie ordinate avente **seconda componente nulla** sono *numeri reali* ossia: $$ (a,0) = a \in \mathbb{R}$$
Partendo quindi dal **numero complesso** $\ (a,b) \in \mathbb{C}$ possiamo *ricavarne la forma cartesiana (algebrica)* nel modo seguente : $$ (a,b) = (a,0) + (0,b) = (a,0) + (0,1)(b,0) = a+ib$$  
Per essere sicuri controlliamo il risultato di $\ (0,1)(b,0)$ cioè della **unità immaginaria** e della **parte immaginaria** da cui troviamo: $$ (0,1)(b,0) = (0 - 0,b + 0) = (0,b)$$
Inoltre per concludere: $$ (a,0) = a \space ; \space (b,0) = b \space ; \space (0,1) = i$$
#### Forma Trigonometrica di un numero Complesso

la **forma trigonometrica di un numero complesso** è una rappresentazione che consente di esprimere qualsiasis numero complesso mediante due valori detti modulo e argomento, nella forma $\ z = r[cos(\theta)+ i \bullet sin(\theta)]$ 

#####  Definizione ed esempi di numeri complessi in forma trigonometrica

sia $\ z \in \mathbb{C}$ un numero *complesso* è in **forma trigonometrica** se si presenta nella forma: $$ z = r[cos(\theta) + isin(\theta)] $$ 
dove $\ i$ indica *l'unità immaginaria*, $\ r$ è un *numero reale* non negativo $$ r \geqslant 0$$ 
e $\theta$ è un **angolo** tale da soddisfare una tra le eseguenti condizioni: $$ -\pi \lt \theta \lt \pi \space oppure \space 0 \le \theta \lt 2\pi$$
###### Esempi

1. $\ 2\sqrt{2} \space [cos(\frac{\pi}{4}) + isin(\frac{\pi}{4})]$
2. $\ 3 \space [ cos(\frac{5}{6}\pi) + isin(\frac{5}{6}\pi)  ]$

##### Come si ricava la forma Trigonometrica dalla definizione di complesso

abbiamo dato la definizone di **numero complesso** come *coppia ordinata* di numeri reali, Se $\ z \in \mathbb{C}$ è un numero complesso, allora è della forma : $$ z = (a,b) \space con \space a,b \in \mathbb{R}$$
Possiamo quindi definire una **corrispondenza biunivoca** tra i *numeri complessi* e i punti di un particolare *piano cartesiano*, il cosidetto [[#Piano di Argand-Gauss]], dove ad ogni *numero complesso* corrisponde **uno** e **un solo punto** nel piano complesso, il punto $\mathbb{P}$ di *cordinate catesiane* $\ (a,b)$ 

![[Forma Trigonometrica Argand-Gauss.png]]

Come si può osservare nella figura , possiamo individuare il **numero complesso** $\ z = (a,b)$ anche conoscendo la misura del *segmento* $\ r = \overline{OP}$ e *l'ampiezza dell'angolo* $\theta$ che il segmento $\overline{OP}$ forma con il *semiasse* delle *ascisse positive* 

Ricordando i **teoremi trigonometrici sugli angoli rettngoli** risulta che:
$$ a = \overline{OA} = \overline{OP} \bullet cos(\theta) = r \space cos(\theta)$$
$$ b = \overline{OB} = \overline{OP} \bullet sin(\theta) = r \space sin(\theta)$$
Per tanto partendo dalla **forma algebrica** possiamo scrivere: $$ z = (a,b) = a + ib = r cos(\theta) + i [rsin(\theta)] = r[cos(\theta) + isin(\theta)]$$
##### Condizioni su modulo ed argomento

sia $\ z \in \mathbb{C}$ un numero *complesso* è in **forma trigonometrica** se si presenta nella forma: $$ z = r[cos(\theta) + isin(\theta)] $$
1. poichè $\ r$ indica la **misura di un segmento**, il suo valore dovrà essere necessariamente *positivo* ad *eccezione* del segmento degenere di **lunghezza nulla**.

2. Inoltre dal momento che la **funzione seno** così come la **funzione coseno** sono *funzioni periodiche* di perido $\ 2\pi$, la **corrispondenza** tra un *numero complesso* e la sua *forma trigonometrica* non è **biunivoca**: vi sono infatti angoli (che differiscono per multipli di $\ 2\pi$ ) che *hanno stesso seno e stesso coseno*. Per rendere **biunivoca** tale corrispondenza dobbiamo imporre che l'angolo $\theta$ vari tra$\ -\pi \space e \space \pi$ oppure tra $\ 0 \space e \space 2\pi$, includendo in entrambi i casi solo uno dei due estremi.

##### Operazioni con i numeri complessi in forma trigonometrica

1. volendo calcolare la **somma o la differenza tra due numeri complessi** in forma **trigonometrica** è *consigliato passare* peima alla forma **cartesiana**
2. il **Prodotto tra due numeri complessi** $$ z_1 = r_1 [cos(\theta_1) + isin(\theta_1)] \space e \space z_2 = r_2 [cos(\theta_2) + isin(\theta_2)]$$ è un numero complesso il cui **modulo** è  dato dal prodotto dei moduli e l'argomento si deriva dalla somma degli argomenti: $$ z_1z_2 = r_1r_2[cos(\theta_1+\theta_2) + isin(\theta_1+\theta_2)]$$
3. La **Divisione tra due numeri complessi** è ancora un numero complesso il cui modulo è dato dal rapporto dei due e l'argomento dalla differenza; $$ \frac{z_1}{z_2} = \frac{r_1}{r_2}[cos(\theta_1-\theta_2) + isin(\theta_1-\theta_2)]$$ 

#### Modulo di un Numero Complesso

dato un *Numero Complesso* $\ z \in \mathbb{C}$ in forma algebrica $$\ z = a +ib$$
sappiamo che $\ Re(z) = a \in \mathbb{R}, \space Im(z) = b \in \mathbb{R}$ sono rispettivamente la *parte reale* e la *parte immaginaria* di $z$ e che sono entrambi *numeri reali*

Definiamo il **modulo del numero complesso** $z$ come $$ r = \vert z \vert := \sqrt{a^{2}+ b^2} $$
dove il *simbolo* $:=$ denota un uguaglianza per *definizione*. Dalla definizione stessa discende l'ovvia coindizione da imporre sul **modulo** $$ r \ge 0$$
#### Argomento di un numero complesso

Continuando con le notazioni adottate in precedenza, definiamo l'**argomento del numero complesso** $z$ come il numero $$\theta := Arg(z) \in (-\pi, +\pi]$$
dato da $$$\theta := Arg(z) =$$ 
##### Tabella Ricerca Modulo
| Valore                                  | Condizione                       |
| --------------------------------------- | -------------------------------- |
| $\frac{\pi}{2}$                         | se $\ a = 0, b > 0$              |
| $\ - \frac{\pi}{2}$                     | se $\ a = 0, b > 0$              |
| non definito                            | se $\ a = 0, b = 0$              |
| $\arctan(\frac{b}{a})$                  | se $\ a > 0, b \space qualsiasi$ |
| $\arctan\left(\frac{b}{a}\right) + \pi$ | se $\ a < 0, b \ge 0$            |
| $\arctan\left(\frac{b}{a}\right) - \pi$ | se $\ a < 0, b < 0$              |

#### Dalla Forma Algebrica alla forma Trigonometrica 

un **numero complesso in forma algebrica** si presenta come $$ z = a+ib, \space con \space a,b \in \mathbb{R}$$
per *Passare* alla **forma trigonometrica** $$ z = r[cos(\theta) + isin(\theta)] $$
basta calcolare $r$ e $\theta$, ossia il **modulo** e **argomento** del *numero complesso* $\ z = a + ib$ 

per il **modulo** basta ricorrere alla formula citata nella sezione [[#Modulo di un Numero Complesso]] $$r = \sqrt{a^2+b^2}$$
mentre per il valore dellargomento $\theta$ varia a seconda dell'intervallo in cui si decide di lavorare.  Possiamo ricorrere però alla tabella sopra citata ([[#Tabella Ricerca Modulo]])


###### TODO | Fare Esempio 

#### Dalla Forma Trigonometrica alla forma Algebrica

Ora analizziamo il caso in cui è nota la rappresentazione in *forma trigonometrica* $$z = r[cos(\theta) + i sin(\theta) ]$$
per arrivare a questa $$ z = a + ib$$
Le **Formule** che consentono di effetturare tale passaggio sono le seguenti $$\left[ 
	\begin{align}
	a = r cos(\theta) \\
	b = r sin(\theta)
	\end{align} \right]$$
$a$ e $b$ sono infatti cateti di un *triangolo rettangolo*; per determinare le lunghezze basta far ricorso ai **teoremi trigonometrici sui triangoli rettangoli**

###### TODO | Fare Esempio 

#### Dalla Forma Algebrica alla forma Esponenziale

un **numero complesso in forma algebrica** si presenta come $$ z = a+ib, \space con \space a,b \in \mathbb{R}$$
per passare alla *forma esponenziale* $$z = re^{i\theta}$$basta calcolare $r$ e $\theta$, ossia il **modulo** e **argomento** del *numero complesso* $\ z = a + ib$ 

per il **modulo** basta ricorrere alla formula citata nella sezione [[#Modulo di un Numero Complesso]] $$r = \sqrt{a^2+b^2}$$mentre per il valore dellargomento $\theta$ varia a seconda dell'intervallo in cui si decide di lavorare.  Possiamo ricorrere però alla tabella sopra citata ([[#Tabella Ricerca Modulo]])

###### TODO | Fare Esempio 

#### Dalla Forma Esponenziale alla forma Algebrica

Partendo dalla rappresentazione esponenziale di un *numero complesso* $$z = re^{i\theta}$$
disponiamo immediatamente del **modulo** $\ r$ e dell'**argomento** $\theta$, si riduce quindi a dover **calcolare** *parte reale* $a$ e *parte immaginaria* $b$ di un *numero complesso* conoscendone **modulo** e **argomento** con le formule  $$\left[ 
	\begin{align}
	a = r cos(\theta) \\
	b = r sin(\theta)
	\end{align} \right]$$
###### TODO | Fare Esempio 

#### Formula di De Moivre

>la **Formula di De Moivre** è una formula che si applica in campo complesso e che permette di calcolare la **potenza di un numero complesso** qualsiasi espresso in *forma trigonometrica* o in *forma esponenziale*

1. Supponiamo di ragionare nel caso più generale possibile, e dunque che il *numero* $z$ sia espresso in **forma algebrica**, vale a dire nella forma $$z = a+ib, \space con \space a,b \in \mathbb{R}$$
2. Calcoliamo il **modulo e argometo** di $z$, rispettivamente $r,\theta$, in modo di *passare* dalla *forma algebrica* alla *forma trigonometrica* $$ z = r[cos(\theta) + i sin(\theta)]$$
3. Applichiamo direttamente la **Formula di De Moivre**, secondo cui la *potenza* di un *numero complesso* si ottiene **elevando** il *modulo* all'*esponente* e **moltiplicando** l'*argomento* per l'*espontente* $$ z^{n} = r^{n}(cos(n\theta) + isin(n\theta))$$ se invece siamo in **forma esponenziale** allora $$ z^{n} = r^ne^{in\theta}$$

#### Sezione Nuova
gtftimn hb
Tutto Bene