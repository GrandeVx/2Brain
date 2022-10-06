## Algebra Vettoriale

> Le *Grandezze* si dividono in **scalari** e **vettoriali**
> **Grandezza scalare**: è una grandezza che può essere completamente definita solo attraverso un *numero* e la sua *unità di misura*:
> **Grandezza vettoriale**: è una grandezza che per essere completamente definita necessita delle seguenti *informazioni*:
> 	• *un numero* (che è il modulo o intensità del vettore) e la sua unità di misura
> 	• *una direzione* (che è la direzione del vettore)
> 	  • *un verso* (che è il verso del vettore)


### Rappresentazioni

#### Rappresentazione Grafica

Si Rappresenta **graficamente** con una *freccia* la cui *lunghezza* è **proporzionale** al valore numerico della grandezza che rappresenta, la cui *direzione* è quella della retta su cui **giace** e il cui *verso* indicato con la **punta** della *freccia*

![[Vettore-Grafica.png]]

#### Rappresentazione Cartesiana

![[Vettore-Cartesiana.png]]

Conoscendo $a$ che definiamo il **modulo** e l'*angolo* $\theta$ possiamo ricavare le componenti $\ a_{y} \space e \space a_{x}$ nel seguente modo  $$ \begin{align} a_{x} = acos\theta \\ a_{y} = a sin \theta \\ \theta = arctan(a_{y}/a_{x}) \end{align}$$
Mentre conoscendo le componenti di due vettori possiamo calcolare **l'angolo compreso** nel seguente modo $$ \theta = arcos(\frac{\overrightarrow{A} \space \bullet \space  \overrightarrow{B}}{\vert \overrightarrow{A} \vert \space \bullet \space \vert \overrightarrow{B} \vert}) $$

##### Esempi

###### Esempio 1
Dato il **vettore** *a* avete modulo pari a 8 e direzione che forma un *angolo* di $30°$ con l'*asse* delle **x**, trovare le sue componenti cartesiane 
$$ a_{x}= a cos(\theta) => a_{x} = 8 \bullet cos(30°) = 8 \bullet \frac{\sqrt{3}}{2} = 4\sqrt{3}$$
$$ a_{y}= a sen(\theta) => a_{y} = 8 \bullet sen(30°) = 8 \bullet \frac{{1}}{2} = 4$$

###### Esempio 2
Dato il **vettore** *a* avente le componenti con modulo $a_{x} = 5$ e $a_{y} = 3$ trovare il **modulo** del *vettore risultante* e **l'angolo** che forma rispetto alla direzione dell'**asse x** 


### Operazioni tra Vettori

#### Somma

##### Metodo Testa-Coda

Dati due vettori aventi la **stessa direzione** spostare il secondo vettore lungo la sua direzione in modo che la **coda** *coincida* con la **punta** del *primo vettore*

Il vettore **somma (c)** è il vettore che va dall'inizio del *primo* vettore **(a)** alla fine del *secondo* vettore **(b)** 

##### Metodo del Parallelogramma

Dati due vettori aventi **direzioni diverse** trasportare *parallelamente* i due vettori liberi in modo da avere **origini** o **code** *coincidenti* .il risultante è la **diagonale** del parallelogramma![[Metodo Parallelogramma.png]]

### Generalizzazione a 3 dimensioni

dati $a = a_{x}i + a_{y}j+a_{z}k$ e $b = b_{x}i+b_{y}j+b_{z}k$  si deriva che la **Somma** è uguale a $$ a+ b = (a_{x} + b_{x})i + (a_{y}+ b_{y})j + (a_{z}+ b_{z})k$$
e la **differenza** $$ a-b = (a_{x}-b_{x})i + (a_{y}-b_{y})j + (a_{z}-b_{z})$$
#### Prodotto Tra Vettori

Il **prodotto tra vettor**i è di due tipi:
1. **Prodotto scalare** tra vettori (esempio: il lavoro) 
2. **Prodotto vettoriale** tra vettori 

##### Prodotto Scalare 

Se **A** è uguale a $(A_x,A_y,A_z)$ e **B** è uguale a  $(B_x,B_y,B_z)$ deriva che $$ A \space \bullet \space B = A_x*B_{x} + A_{y}*B_{y} + A_{z}*B_{z} $$
##### Prodotto Vettoriale

Se **A** è uguale a $(A_x,A_y,A_z)$ e **B** è uguale a  $(B_x,B_y,B_z)$ deriva che $$ A \times B = \left\vert 
\begin{align} 

\widehat{x} \quad \space \widehat{y} \quad \widehat{z} \quad \\ 
A_{x} \quad A_{y} \quad A_{z} \\
B_{x} \quad B_{y} \quad B_{z}

\end{align} 
\right\vert $$
da cui $$A \times B = x(A_{y}B_{z} - A_{z}B_{y}) + y(A_{x}B_{z}-A_{z}B_{x}) + 
z(A_{x}B_{y}- A_{y}B_{x})$$

### Esercitazioni

##### Quesito 1

Calcolare i seguenti Prodotti tra Vettori $\overrightarrow{A} = (5,-3,2)$ e $\overrightarrow{B} = (3,4,0)$ 
1. $\overrightarrow{A} \space \bullet \space \overrightarrow{B} = (5 * 3) + (-3 * 4) + (2 * 0) = 3$
2. $\overrightarrow{A} \space \times \space \overrightarrow{B} =$  $$ A \times B = \left\vert 
\begin{align} 

\widehat{x}  \quad \widehat{y} \quad \widehat{z} \\ 
5  -3 \quad 2 \\
3 \quad 4 \quad 0

\end{align} 
\right\vert  = (0+8)i + (0-6)j + (20+9)k = (-8,6,29) => \overrightarrow{C}$$




