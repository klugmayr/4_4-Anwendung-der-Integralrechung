## Flächenberechnung

Mit Hilfe des bereits eingeführten Intgralbegriffs lässt sich das Flächenmaß folgendermaßen defnieren.

### Definition

Es sei $f:[a,b]\rightarrow\mathbb{R}$ eine integrierbare  Funktione und A jene Fläche, die vom Funktionsgraphen, der x-Achse und den beiden Senkrechten $x=a$ und $x=b$ begrenzt wird.

Gilt $f(x)\geq 0$ für alle $x\in [a,b]$ mit $a\leq b$, so ist die Fläche gegeben durch

$A=\int_a^b f(x) dx$

Gilt $f(x)\leq 0$ für alle $x\in [a,b]$ mit $a\leq b$, so ist die Fläche gegeben durch

$A=|\int_a^b f(x) dx |$

### Bemerkung

    

1. Hat die Funktion $f$ im Intervall $[a,b]$ sowohl positive als auch negative Werte, so zerlegt man $[a,b]$ in Teilintervalle, so dass die Funktion in diesen Intervallen konstantes Vorzeichen hat. Es gilt $A=\int_a^c f(x) dx+|\int_c^d f(x) dx|+\int_d^b f(x) dx$
2. Für eine gerade Funktion ($f(x)=f(-x)$) gilt: $\int_{-a}^a f(x) dx =2\cdot\int_0^a f(x) dx$
3. Für eine ungerade Funktion ($f(x)=-f(-x)$) gilt: $\int_{-a}^a f(x) dx = 0$
4. Für den Flächeninhalt zwischen den Graphen zweier Funktionen gilt. Es seien $f:[a, b]\rightarrow \mathbb{R}$ und $g:[a, b] \rightarrow\mathbb{R}$ zwei integrierbare Funktionen mit $f(x) \geq g(x)$ für alle $x\in[a,b]$ und $A$ jene Fläche, die von den Funktionsgraphen begrenzt wird. Dann gilt $A=\int_a^b (f(x)-g(x)) dx$
