## concavità, convessità e flessi

#### derivata di ordine superiore
una funzione $f: A \rightarrow \mathbb{R}$ si dice derivabile due volte se:
- $f$ è derivabile
- $f'$ è derivabile
allora $f'' : A \rightarrow \mathbb{R}$ è data da $f''=(f')'$

in modo analogo sono definite le derivate di ordine superiore.

#### insiemi di funzioni derivabili
indicato con $C^k(I)$ l'insieme (o la **classe**) delle funzioni derivabili $k$ volte con derivata $k$-esima continua in $I$.

$$
C^0(I)=\{ f : I \rightarrow \mathbb{R} \ | \ f \text{ continua} \}
$$

$$
C^1(I)=\{ f : I \rightarrow \mathbb{R} \ | \ f \ \text{derivabile e } \ f' \text{ continua} \}
$$

$$
C^k(I)=\{ f : I \rightarrow \mathbb{R} \ | \ f \ \text{derivabile k volte e } \ f^{(k)} \text{ continua} \}
$$

$$
C^\infty(I)=\{ f : I \rightarrow \mathbb{R} \ | \ f \ \text{derivabile k volte} \}
$$

#### funzioni convesse e concave
data $f : I \rightarrow \mathbb{R}$ diremo che $f$ è:
- **convessa** in $I$ se per ogni punto $x_1, x_2$ la retta passante per $P_1=(x_1, f(x_1))$ e $P_2=(x_2, f(x_2))$ si trova sotto al grafico di $f$
- **concava** in $I$ se la retta per $P_1$ e $P_2$ è sotto il grafico di $f$

il seguente teorema ci permette di capire se una funzionè concava o convessa:
- se $f''(x) \ge 0$ allora $f$ è **convessa** in $I$
- se $f''(x) \le 0$ allora $f$ è **concava** in $I$
- se $f''(x_0) \gt 0, x_0 \in I$ allora $f$ è **localmente convessa** in $I$
- se $f''(x_0) \lt 0, x_0 \in I$ allora $f$ è **localmente concava** in $I$
- se $x_0$ è punto di flesso allora $f''(x_0) = 0$