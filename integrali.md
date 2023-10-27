# Integrali
aggiornamento dell'argomento integrali. Le informazioni sono prese dai video di [Elia Bombardelli](https://www.youtube.com/playlist?list=PLD65828BD6F3E86AA)

La formula $\int_a^bf(x) dx$ rappresenta l'**area** (con segno) della regione di piano compresa fra il grafico di $f(x)$, l'asse $x$ e le rette verticali $x = a$ e $x=b$

#### procedura generale
[video](https://www.youtube.com/watch?v=MOE7x_B_WeA&list=PLD65828BD6F3E86AA&index=1&pp=iAQB)
per poter calcolare $\int_a^bf(x)dx$ devo:
- trovare una funzione che, nell'intervallo $[a; b]$ abbia $f(x)$ come **derivata** (ovvero *primitiva* di $x$)
- una volta trovata, la calcolo negli estrmi della zona di integrazione (calcolo cioè $F(b)$ e $F(a)$)
- sottraggo i due valori per calcolare $\int_a^bf(x) dx = F(b)-F(a)$.

#### primitive elementari e proprietà degli integrali
[video](https://youtu.be/4hfhVhnzuUw?list=PLD65828BD6F3E86AA)
prima di individuare le primitive dell'integrale bisogna capire se la funzione è derivabile: è dimostrabile che se la funzione $f(x)$ è continua nell'intervallo di integrazione $[a; b]$ allora esiste almeno una primitiva.

$\int f(x) dx$ rappresenta l'**integrale indefinito**

ecco una lista delle **primitve elementari**: 
| $f(x)$            | F(x)                            |
|:-----------------:|:-------------------------------:|
| $cos(x)$          | $sin(x)$                        |
| $sin(x)$          | $-cos(x)$                       |
| $e^x$             | $e^x$                           |
| $a^x$             | $\frac{a^x}{ln(a)}$             |
| $x^n$             | $\frac{x^{n+1}}{n+1}$           |
| $\frac{1}{x}$     | $ln \left\lvert x \right\rvert$ |
| $\frac{1}{1+x^2}$ | $arctan(x)$                     |
