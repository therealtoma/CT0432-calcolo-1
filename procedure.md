# procedure
## studio di funzione
I passaggi principali per effettuare lo studio di funzione
Ogni volta che viene risolto un punto è necessatio riportare l'informazione sul grafico e verificare che sia in accordo con quanto dedotto precedentemente.
1. determinare il **dominio** della funzione $f$ e scriverlo come unione di intervalli $domf = I_1 \cup T_2 \dots$
2. determinare **simmetrie** (pari o dispari) o **periodicità** di $f$
3. studiare il **segno** della funzione ($f(x) \ge 0$) e calcolare, quando possibile, le **intersezioni** con gli assi cartesiani ($y = f(0)$ e risolvere $f(x) = 0$)
4. calcolare i **limiti** agli estremi di ciascun intervallo del dominio $I_1, I_2, \dots$
5. determinare se $f$ ha **asintoti** verticali, orizzontali o obliqui
6. stabilire se la funzione è **continua** e **derivabile**
7. calcolare $f'$ e studiarne il **segno** ($f'(x) \ge 0$). Determinare la **crescenza/decrescenza** di $f$ è i punti di **massimo/minimo** relativi
8. calcolare $f''$ e studiarne il **segno** ($f''(x) \ge 0$). Determinare la **concavità** di $f$ e i punti di **flesso**
9. determinare *inf*$f$ e *sup* $f$ stabilendo se sono o meno minmo e massimo **assoluti**. Determinare l'**immagine** di $f$ in base al teorema sull'immagine di funzioni continue
10. disegnare il **grafico** di $f$ in maniera consistente con i calcoli fatti

**NOTA**: in molti casi non si riescono a svolgere esplicitamente i calcoli per tutti i punti, e si dovrà dedurre l'andamento del grafico solo attraverso i punti svolti

#### 2. simmetrie e periodicità
- simmetria **pari**: una funzione $f$ è **pari** se, per ogni x appartenente al dominiio, $f(-x) = f(x)$ ovvero la funzione è simmetrica rispetto all'asse $y$
- simmetia **dispari**: una funzione $f$ è **dispari** se, per ogni x appartenente al dominio  $f(-x) = -f(-x)$ ovvero la funzione è simmetrica rispetto all'origine
- **periodicità**: una funzione $f$ è **periodica** di periodo $T$ se vale che $f(x+T) = f(x)$


**N.B.** determinare la paritaà/disparità di una funzione risulta molto importante durante lo studio di una funzione:
- se, per esempio, la funzione è *pari* e ha un *massimo* in  $x=3$ allora dovrà avere un *massimo* anche in $x=-3$
- analogamente, se la funzione è *dispari* e ha un *massimo in* $x=5$ allora dovrà avere un minimo in $x=-5$
- la parità/disparità della funzione va controllata solo se anche il dominio è simmetrico rispetto a $x=0$
#### 8. convessità, concavità e flessi

**convessità**
- Le rette **tangenti** alla funzione si trovano sotto al grafico di essa
- la derivata prima ($f'$) è **crescente**
- $f'' \ge 0$

**concavità**
- Le rette **tangenti** alla funzione si trovano sopra al grafico di essa
- la derivata prima ($f'$) è **decrescente**
- $f'' \le 0$

**punto di flesso**
è un punto nel quale $f'' = 0$ se esiste
- non è detto che, se $f'' = 0$ il punto di flesso esiste (parabola)
- non è detto che, se ho un cambio di concavità, il punto di flesso esista (punti di flesso a tangente verticale $\sqrt[3]{x}$)

## massimi e minimi
### massimi e minimi assoluti
un punto $M$ è detto **massimo** se la funzione $f(x)$ è sempre **minore** di quel punto, inoltre esiste almeno un punto $x_0$ tale che $f(x_0) = M$.
In tal caso $(x_0, M)$ è il punto di massimo.

Un punto $m$ è detto **minimo** se la funzione $f(x)$ è sempre **maggiore** di quel punto, inoltre esiste almeno un punto $x_0$ tale che $f(x_0) = m$.

### massimi e minimi relativi
se restringiamo il dominio della funzione $f(x)$ ad un intervallo $I$ allora possiamo parlare di **massimo relativo** e **minimo relativo**.

#### dove cercare i punti di massimo e minimo?
- bisogna cercare all'interno dei **punti stazionari interni**, ovvero quei punti nei quali si annulla la derivata prima ($f'(x) = 0$)
- bisogna cercare all'interno dei **punti singolari interni**, ovvero quei punti nei quali la derivata prima non esiste ($f'(x) = \nexists$)
- negli eventuali **punti di frontiera**
