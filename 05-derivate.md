# Derivate
## definizione di derivata
### rette nel piano
$$
y = mx+q \qquad \text{oppure} \qquad x=a \qquad \text{rette verticali}
$$
- $m$ corrisponde al **coefficente angolare** ($m = \frac{\Delta y}{\Delta x}$)
- $m = tan(\alpha)$ dove $\alpha$ è l'angolo tra $y=0$ e la retta
- $q$ è l'**intercetta** (intersezione con l'asse $x=0$)

### rette per un punto
dato il punto $P_0=(x_0, y_0) \in \mathbb{R}^2$ le rette passanti per $P_0$ hanno equazione:

$$
y = m(x-x_0)+q \qquad \text{oppure} \qquad x=a \qquad \text{rette verticali}
$$

### retta per due punti
la retta passante per $P_0=(x_0, y_0)$ e per $P_1=(x_1, y_1)$ ha equazione:

$$
\begin{cases}
    y = m(x-x_0)+ y_0
    x = x_0
\end{cases}
$$

## rapporto incrementale
$$
r(x) = \frac{f(x)- f(x_0)}{x- x_0}
$$

### derivata di un punto
$h = x- x_0$
se $\lim_{h \to 0} \frac{f(x_0+h)-f(h)}{h}$ **esiste finito** allora $f$ è derivabile in $x_0$ e la derivata è:

$$
f'(x_0) = \lim_{h \to 0} \frac{f(x_0+h)-f(x_0)}{h}
$$

## derivate delle funzioni elementari
### funzioni potenza
| $f(x)$     | $f'(x)$                         | Dominio di $f'$ |
|:----------:|:-------------------------------:|:---------------:|
| $c$        | 0                               | $\mathbb{R}$    |
| $x$        | 1                               | $\mathbb{R}$    |
| $x^n$      | $nx^{n-1}$                      | $\mathbb{R}$    |
| $x^{-n}$   | $-nx^{-n-1}$                    |                 |
| $\sqrt{x}$ | $\frac{1}{n}x^{-\frac{n-1}{n}}$ |                 |
| $x^\alpha$ | $\alpha x ^{\alpha - 1}$        |                 |

### funzioni trigonometriche

### funzioni esponenziali e logaritmiche