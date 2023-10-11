## successioni
una successione è una funzione $a: A \to \mathbb{R}$ che ad ogni elemento $n \in A$ associa un solo elemento $a(n) = a_n \in \mathbb{R}$

**esempi**:
- $a_n = \frac{1}{n}$ è la successione $1, \frac{1}{2}, \frac{1}{3}, ...$
- $a_n = n!$ è la successione $1, 2, 6, 24, ...$

## limite di successione
sia $(a_n)$ una successione:
- $lim \ a_n = l$ se per ogni $\epsilon > 0$ esiste $n_0 \in \mathbb{N}$ tale che $|a_n - l| < \epsilon$ per ogni $n \geq n_0$, in questo caso la successione **converge**
- $lim \ a_n = +\infty$ se per ogni $M > 0$ esiste $n_0 \in \mathbb{N}$ tale che $a_n > M$ per ogni $n \geq n_0$, in questo caso la successione **diverge** a $+\infty$
- $lim \ a_n = +\infty$ se per ogni $M > 0$ esiste $n_0 \in \mathbb{N}$ tale che $a_n < M$ per ogni $n \geq n_0$, in questo caso la successione **diverge** a $+\infty$
- se non esiste il limite la successione è **indeterminata**