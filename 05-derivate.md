# Derivate
## definizione di derivata
#### rette nel piano
$$
y = mx+q \qquad \text{oppure} \qquad x=a \qquad \text{rette verticali}
$$
- $m$ corrisponde al **coefficente angolare** ($m = \frac{\Delta y}{\Delta x}$)
- $m = tan(\alpha)$ dove $\alpha$ è l'angolo tra $y=0$ e la retta
- $q$ è l'**intercetta** (intersezione con l'asse $x=0$)

#### rette per un punto
dato il punto $P_0=(x_0, y_0) \in \mathbb{R}^2$ le rette passanti per $P_0$ hanno equazione:

$$
y = m(x-x_0)+q \qquad \text{oppure} \qquad x=a \qquad \text{rette verticali}
$$

#### retta per due punti
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
#### funzioni potenza
| $f(x)$     | $f'(x)$                         | Dominio di $f'$ |
|:----------:|:-------------------------------:|:---------------:|
| $c$        | 0                               | $\mathbb{R}$    |
| $x$        | 1                               | $\mathbb{R}$    |
| $x^n$      | $nx^{n-1}$                      | $\mathbb{R}$    |
| $x^{-n}$   | $-nx^{-n-1}$                    |                 |
| $\sqrt{x}$ | $\frac{1}{n}x^{-\frac{n-1}{n}}$ |                 |
| $x^\alpha$ | $\alpha x ^{\alpha - 1}$        |                 |

#### funzioni trigonometriche
| $f(x)$   | $f'(x)$                           | Dominio di $f'$ |
|:--------:|:---------------------------------:|:---------------:|
| $sin(x)$ | $cos(x)$                          | $\mathbb{R}$    |
| $cos(x)$ | $-sin(x)$                         | $\mathbb{R}$    |
| tan(x)$  | $\frac{1}{cos^2(x)} = 1+tan^2(x)$ |                 |


#### funzioni esponenziali e logaritmiche
| $f(x)$     | $f'(x)$             | Dominio di $f'$ |
|:----------:|:-------------------:|:---------------:|
| $e^x$      | $e^x$               | $\mathbb{R}$    |
| $a^x$      | $log(a) \cdot a^x$  | $\mathbb{R}$    |
| $log(x)$   | $\frac{1}{x}$       | $x > 0$         |
| $log_a(x)$ | $\frac{1}{xlog(a)}$ | $x > 0$         |

#### algebra delle derivate
date due funzioni $f$ e $g$ derivabili in $x_0$, allora:
- $f+g$ è derivabile in $x_0$: $D(f+g)(x_0) = f'(x_0) + g'(x_0)$
- $f \cdot g$ è derivabile in $x_0$: $D(f \cdot g)(x_0) = f'(x_0)g(x_0)+f(x_0)g'(x_0)$
- $\frac{f}{g}$ con $g(x_0) \not = 0$ è derivabile in $x_0$: $D(\frac{f}{g})(x_0) = \frac{f'(x_0)g(x_0)- f(x_0)g'(x_0)}{g^2(x_0)}$
- $D(\alpha f + \beta g)(x_0)=f'(g(x_0)) \cdot g'(x_0)$

## proprietà locali e teoremi sulle funzioni derivabili

#### proprietà locali
le proprietà locali riguradano l'andamento di una funzione in vicinanza (o in un intorno) di un punto $x_0$.
Data la funzione $f: A \rarr \mathbb{R}$ e $x_0 \in A$, se esiste un intorno di $x_0$ si ha:
- se $x < x_0 \implies f(x) \lt f(x_0)$ allora $f$ è **crescente** in $x_0$
- se $x < x_0 \implies f(x) \ge f(x_0)$ allora $f$ è **decrescente** in $x_0$
- se $f(x_0) \ge f(x)$ allora $x_0$ è **masimo relativo**
- se $f(x_0) \le f(x)$ allora $x_0$ è **minimo relatico**

#### massimi, minimi relativi e punti di flesso
data $f$ derivabile in $x_0$:
- se $x_0$ è un punto di massimo o minimo relativo allora $f'(x_0) = 0$
- se $f'(x_0) = 0$ e $f$ non è costante attorno a $x_0$ allora $x_0$ è **punto stazionario**
  - se $f(x)$ è crescente per $x \lt x_0$ e decrescente per $x \gt x_0$ allora $x_0$ è **massimo relativo**
  - se $f(x)$ è decrescente per $x \lt x_0$ e crescente per $x \gt x_0$ allora $x_0$ è **minimo relativo**
  - se $f(x)$ è crescente (o decrescente) sia per $x \lt x_0$ che per $x \gt x_0$ allora $x_0$ è **punto di flesso**