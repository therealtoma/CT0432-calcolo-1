# Limiti
## definizione di limite
$$
\lim_{x \to x_0} f(x) = l
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

