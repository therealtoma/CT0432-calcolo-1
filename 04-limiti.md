# Limiti
Data una funzione $f: A \subseteq \mathbb{R}$ e sia $x_0 \in \mathbb{R}$ un punto di accumulazione di $A$. Diremo che $l \in \mathbb{R}$ è il limit per $x$ tendente a $x_0$ se è possibile trovare un intorno $I_{x_0}$ tale che i valori della funzione calcolati nel'intorno $I_{x_0}$ cadono nell'intorno $U_l$

$$
\lim_{x\to x_0}f(x) = l
$$

### teorema dell'unicità del limite
Se $l_1$ e $l_2$ con $l_1, l_2 \in \mathbb{R}$

$$
lim_{x \to x_0} f(x) = l_1 \quad \land \quad lim_{x \to x_0} f(x) = l_2
$$

allora deve essere $l_1 = l_2$ cioè il limite è **unico**.

### limiti infiniti
- $lim_{x \to -\infty} f(x) = l; \qquad lim_{x \to +\infty} f(x) = l; \qquad (lim_{x \to \infty} f(x) = l)$
- $lim_{x \to x_0} f(x) = -\infty; \qquad lim_{x \to x_0}; \qquad lim_{x \to x_0} f(x) = \infty$
- $lim_{x \to -\infty} f(x) = \pm\infty; \qquad lim_{x \to +\infty} f(x) = \pm\infty; \qquad lim_{x \to \infty} f(x) = \infty$

### limite destro e sinistro
se $lim_{x \to x_0} f(x) = l$ allora deve valere:

$$
lim_{x \to x_0^-} f(x) = l \qquad \land \qquad lim_{x \to x_0^+} f(x) = l
$$

## teorema confronto (carabinieri)
Se $f(x) \le g(x) \le h(x)$ allora, il teorema di carabinieri garantisce che:
- se $lim_{x \to x_0} f(x) = l$ e $lim_{x \to x_0} h(x) = l$ allora vale $lim_{x \to x_0} g(x) = l$
- se $lim_{x \to x_0} f(x) = + \infty$ allora $lim_{x \to x_0} g(x) = + \infty$
- se $lim_{x \to x_0} h(x) = - \infty$ allora $lim_{x \to x_0} g(x) = -\infty$

## algebrea dei limiti
### limite della somma
Se $lim_{x \to x_0} f(x) = l \in \mathbb{R}$ e $lim_{x \to x_0} g(x) = m \in \mathbb{R}$ allora vale 

$$
lim_{x \to x_0} (f(x) + g(x)) = l + m
$$

Più in generale:

|                    | $m \in \mathbb{R}$ | $m = +\infty$ | $m = -\infty$ |
| :----------------: | :----------------: | :-----------: | :-----------: |
| $l \in \mathbb{R}$ | $l+m$              | $l = +\infty$ | $l = -\infty$ |
| $l = +\infty$      | $l = +\infty$      | $l = -\infty$ | $f.i.$        |
| $l = -\infty$      | $l = -\infty$      | $f.i.$        | $l = -\infty$ |

### limite del prodotto
Se $lim_{x \to x_0} f(x) = l \in \mathbb{R}$ e $lim_{x \to} g(x) = m \in \mathbb{R}$ allora vale

$$
lim_{x \to x_0} (f(x) \cdot g(x)) = l \cdot m
$$

Più in generale:

|               | $m < 0$     | $m = 0$ | $m > 0$     | $m = +\infty$ | $m = - \infty$ |
| :-----------: | :---------: | :-----: | :---------: | :-----------: | :------------: |
| $l < 0$       | $l \cdot m$ | $0$     | $l \cdot m$ | $-\infty$     | $+\infty$      |
| $l = 0$       | $0$         | $0$     | $0$         | $f.i.$        | $f.i.$         |
| $l > 0$       | $l \cdot m$ | $0$     | $l \cdot m$ | $+\infty$     | $-\infty$      |
| $l = +\infty$ | $-\infty$   | $f.i.$  | $+\infty$   | $+\infty$     | $-\infty$      |
| $l = -\infty$ | $+\infty$   | $f.i.$  | $-\infty$   | $-\infty$     | $+\infty$      |

### limite del quoziente
Se $lim_{x \to x_0} f(x) = l \in \mathbb{R}$ allora vale:

$$
lim_{x \to x_0} \frac{1}{f(x)} = \frac{1}{l}
$$

|               | $m < 0$       | $m = 0^\pm$   | $m > 0$     | $m = +\infty$ | $m = - \infty$ |
| :-----------: | :-----------: | :-----------: | :---------: | :-----------: | :------------: |
| $l < 0$       | $l / m$       | $\pm \infty$  | $l / m$     | $0$           | $0$            |
| $l = 0$       | $0$           | $f.i.$        | $0$         | $0$           | $0$            |
| $l > 0$       | $l / m$       | $\pm \infty$  | $l / m$     | $0$           | $0$            |
| $l = +\infty$ | $-\infty$     | $\pm \infty$  | $+\infty$   | $f.i.$        | $f.i.$         |
| $l = -\infty$ | $+\infty$     | $\mp \infty$  | $-\infty$   | $f.i.$        | $f.i.$         |

# Funzioni continue

## definizione
Sia la funzione $f: A \subset \mathbb{R} \to \mathbb{R}$
- se $x_0$ è un **punto di accumulazione** per $A$ allora diremo che $f$ è **continua** in $x_0$
- se $x_0 \in A$ è un punto isolato di $A$, allora $f$ è continua anche in $x_0$
- diremo che $f$ è **continua** se è continua in ogni punto del suo dominio

## operazioni tra funzioni continue
Date due funzioni $f, g: A \to \mathbb{R}$, allora
- $h = f + g$ è continua
- $h = f \cdot g$ è continua
- $h = \frac{f}{g}$ è continua
- $g = |f|$ è continua

## limiti importanti delle funzioni elementari
$$
\lim_{x \to x_0} x^a =
\begin{cases}
  0 & \text{se} \ a > 0 \\
  +\infty & \text{se} \ a < 0
\end{cases}
$$

$$
\lim_{x \to -\infty} x^n =
\begin{cases}
+\infty & \text{se} n \text{pari}
0 & \text{s} 0 < a < 1
\end{cases}
$$

$$
\lim_{x \to 0^-} \frac{1}{x^n} =
\begin{cases}
+\infty & \text{se} n \text{pari}
-\infty & \text{se} n \text{dispari}
\end{cases}
$$

$$
\lim_{x \to +\infty} a^x =
\begin{cases}
-\infty & \text{se} a > 1
0 & \text{se} 0 < a < 1
\end{cases}
$$

$$
\lim_{x\to +\infty} x^a=
\begin{cases}
  +\infty & \text{se} \ a > 0 \\
  0 & \text{se} \ a < 0
\end{cases}
$$

## definizione
$$
|x-x_0| < \delta \qquad \text{da cui otteniamo} \qquad |f(x) - l| < \epsilon
$$

#### procedura
tramite un esempio:
sia $\lim_{x\to-2}x^2=4$ i passaggi sono:
- trovare $|x^2 -4| < \epsilon$
- per la proprietà del valore assoluto abbiamo $-\epsilon < |x^2-4| < \epsilon$
- isolando la $x$ otteniamo $\sqrt{4-\epsilon} < x < \sqrt{4+\epsilon}$
- a questo punto ci interessa trovare $|x-2| < \delta$
- sottraiamo $2$ ai due membri $\sqrt{4-\epsilon}-2 < x-2 < \sqrt{4+\epsilon}-2$
- ricomponiamo il valore assoluto e troviamo la soluzione $|x-2| < \sqrt{4-\epsilon} -2$


## limiti infiniti
quando abbiamo limiti per $x \to \pm \infty$ non possiamo verificare tramite $\epsilon - \delta$ ma dobbiamo considerare intorno di $\pm \infty$

#### procedura
sia $\lim_{x \to +\infty}\frac{x+1}{x}=1$ i passaggi sono:
- dobbiamo trovare $M$
