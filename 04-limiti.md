# Limiti
Data una funzione $f: A\sub\mathbb{R}$ e sia $x_0 \in \mathbb{R}$ un punto di accumulazione di $A$. Diremo che $l \in \mathbb{R}$ è il limit per $x$ tendente a $x_0$ se è possibile trovare un intorno $I_{x_0}$ tale che i valori della funzione calcolati nel'intorno $I_{x_0}$ cadono nell'intorno $U_l$
$$
\lim_{x\to x_0}f(x) = l
$$

## definizione ($\epsilon - \delta$)
$$
|x-x_0| < \delta \qquad \text{da cui otteniamo} \qquad |f(x) - l| < \epsilon
$$

**esempio**
Data $f(x) = \frac{x^2-1}{x-1}$ vogliamo verificare che $\lim_{x \to 1}f(x)=2$
*sol:* dato $\epsilon$ dobbiamo dimostrare che esiste $\delta$
$$
|f(x)-2| < \epsilon \iff |\frac{x^2-1}{x-1}-2| < \epsilon \iff |x+1-2| < \epsilon
$$