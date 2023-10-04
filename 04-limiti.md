# Limiti
Data una funzione $f: A\sub\mathbb{R}$ e sia $x_0 \in \mathbb{R}$ un punto di accumulazione di $A$. Diremo che $l \in \mathbb{R}$ è il limit per $x$ tendente a $x_0$ se è possibile trovare un intorno $I_{x_0}$ tale che i valori della funzione calcolati nel'intorno $I_{x_0}$ cadono nell'intorno $U_l$
$$
\lim_{x\to x_0}f(x) = l
$$

## definizione ($\epsilon - \delta$)
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

