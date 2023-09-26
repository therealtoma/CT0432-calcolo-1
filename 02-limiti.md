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