## Analisi Dimensionale

> L'analisi dimensionale (o *controllo dimensionale*) è la **scomposizione** di una grandezza fisica nelle **grandezze fondamentali** che la determinano.

##### A cosa serve l'analisi dimensionale?

L'analisi dimensionale è utile per verificare la correttezza fisica dei calcoli. 

Le grandezze fisiche con la stessa dimensione si possono semplificare tramite operazioni algebriche del calcolo letterale (somma, sottrazione, divisione, prodotto). 

Un calcolo è fisicamente corretto se ha la stessa dimensione della legge fisica a cui si riferisce.

##### Come fare l'analisi dimensionale

1. Analizzo la relazione che determina la *grandezza*
2. **Sostituisco** ogni *grandezza* della relazione con la sua *dimensione* (es. t per il tempo, l per le lunghezze, l/t per la velocità, ecc.).
3. I simboli delle grandezze fisiche devono essere racchiusi tra *parentesi quadre*.
4. Il risultato finale è **l'equazione dimensionale**

##### Esempio Pratico

>  un'automobile percorre 100 metri in 5 secondi. La velocità dell'automobile è ?

- La prima cosa che facciamo è *analizzare* la dimensione della **velocità**

	La velocità (v) è una *grandezza fisica* ottenuta dividendo uno spazio percorso in (metri) e il tempo impiegato (secondi) seguendo la seguente formula v=$\frac{(m)}{(s)}$

	Passando al *punto 2* effettuiamo la **conversione** di ogni *grandezza fisica* con la *relativa dimensionale* seguendo questa tabella

| Grandezza Fondamentale | simbolo grandezza | unità di misura | simbolo unità |
|:---------------------- |:-----------------:| ---------------:|:-------------:|
| Lunghezza              |         l         |           metro |       m       |
| massa                  |         m         |     chilogrammo |      kg       |
| tempo                  |         t         |         secondo |       s       |
| intensità di corrente  |         i         |          ampere |       A       |
| temperatura            |         T         |          kelvin |       K       |
| quantità di sostanza   |         n         |            mole |      mol      |
| intensità luminosa     |       i(v)        |         candela |      cd       | 

Da cui deriva che$\ [v] = \frac{[l]}{[t]}$ e quindi ottengo la *dimensione fisica* della velocità: 
la velocità è una lunghezza **diviso** in tempo e quindi qualsiasi calcolo sulla velocità **deve** avere la stessa dimensione della *legge fisica* della velocità

Ad esempio, riprendendo il problema inziale ci troviamo davanti una situazione del genere:

	$\ v = \frac{(10m)}{(5s)} \ 2 \frac{(m)}{(s)}$

Per verificare la correttezza logica del calcolo faccio **l'analisi dimensionale** a entrambi i membri dell'equazione.

	$\frac{[l]}{[t]} = \frac{(10m)}{(5s)} \ 2 \frac{(m)}{(s)}$

A questo punto faccio **l'analisi dimensionale** anche dei calcoli nel membro di destra dell'equazione.

	$\frac{[l]}{[t]} = \frac{[l]}{[t]}$

*L'uguaglianza* delle dimensioni mi conferma che il ragionamento seguito è corretto. 
Ovviamente questo non mi mette al riparo da eventuali errori matematici nei calcoli. 

Se avessi scritto 10m / 5s = 3 m/s anziché 2m/s l'analisi dimensionale sarebbe comunque corretta ma il risultato errato.