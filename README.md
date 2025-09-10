## Flächenberechnung

Mit Hilfe des bereits eingeführten Intgralbegriffs lässt sich das Flächenmaß folgendermaßen definieren.

### Definition

Es sei $f:[a,b]\rightarrow\mathbb{R}$ eine integrierbare  Funktione und A jene Fläche, die vom Funktionsgraphen, der x-Achse und den beiden Senkrechten $x=a$ und $x=b$ begrenzt wird.

Gilt $f(x)\geq 0$ für alle $x\in [a,b]$ mit $a\leq b$, so ist die Fläche gegeben durch

$A=\int_a^b f(x) dx$

Gilt $f(x)\leq 0$ für alle $x\in [a,b]$ mit $a\leq b$, so ist die Fläche gegeben durch

$A=|\int_a^b f(x) dx |$

### Bemerkung

1. Hat die Funktion $f$ im Intervall $[a,b]$ sowohl positive als auch negative Werte, so zerlegt man $[a,b]$ in Teilintervalle, so dass die Funktion in diesen Intervallen konstantes Vorzeichen hat. Es gilt $A=\int_a^c f(x) dx+|\int_c^d f(x) dx|+\int_d^b f(x) dx$
2. Für eine gerade Funktion ( $f(x)=f(-x)$ ) gilt: $\int_{-a}^a f(x) dx =2\cdot\int_0^a f(x) dx$
3. Für eine ungerade Funktion ( $f(x)=-f(-x)$ ) gilt: $\int_{-a}^a f(x) dx = 0$
4. Für den Flächeninhalt zwischen den Graphen zweier Funktionen gilt. Es seien $f:[a, b]\rightarrow \mathbb{R}$ und $g:[a, b] \rightarrow\mathbb{R}$ zwei integrierbare Funktionen mit $f(x) \geq g(x)$ für alle $x\in[a,b]$ und $A$ jene Fläche, die von den Funktionsgraphen begrenzt wird. Dann gilt $A=\int_a^b (f(x)-g(x)) dx$

#### Beispiele

1. Berechnen Sie den Flächeninhalt jenes Flächenstücks, das von den Graphen $f(x)=x+1$ und $g(x)=\frac{1}{2}x^2-3$ begrenzt wird. (Lösung: 18 FE)
2. Eine Parabel 4. Ordnung hat in $W(0|0)$ einen Wendepunkt mit der x-Achse als Wendetangente und im Punkt $N(-4|0)$  einen weiteren Schnittpunkt mit der x-Achse. Die Fläche, die die Kurve mit der x-Achse begrenzt, hat den Flächeninhalt 12,8. Bestimmen Sie die Funktionsgleichung und fertigen Sie eine Skizze an! (Lösung: $f(x)=-\frac{1}{4}x^4-x^3$)

## Volumsberechnung

Berechnung des Volumens mittels VolumselementenAnalog zu der Berechnung von Flächenmaßen einer ebenen Figur kann auch das Raummaß mit Hilfe von Volumselementen berechnet werden.

1. Beispiel: **Volumen einer Kugel**
2. Beispiel: **Volumen einer regelmäßigen vierseitigen Pyramide**

Rotationsvolumen

1. Rotationskörper entstehen, wenn ein Kurvenstück um eine Achse, im Allgemeinen die x- bzw. y-Achse, die beide in der selben Ebene liegen, gedreht wird.

#### Rotation um die x-Achse

Über einem Intervall $[a, b]$ ist eine stetige Funktion $f(x)$ gegeben. Der Graph der Funktion erzeugt bei Rotation um die x-Achse einen Rotationskörper. Diesen kann man, näherungsweise, durch endlich viele Zylinderscheiben der Breite $\Delta x$ ersetzen.

#### Rotation um die y-Achse

Über einem Intervall $[c, d]$ ist eine stetige Funktion $f(x)$ gegeben. Der Graph der Funktion erzeugt bei Rotation um die y-Achse einen Rotationskörper. Diesen kann man, näherungsweise, durch endlich viele Zylinderscheiben der Breite $\Delta x$ ersetzen.


## Rotation um die x-Achse

Das Volumen $V$ eines Rotationskörpers, der durch Rotation des Graphen der Funktion $f(x)$ über dem Intervall $[a, b]$ um die x-Achse entsteht, berechnet sich durch:

$$
V = \int_a^b \pi [f(x)]^2 \, dx
$$

## Rotation um die y-Achse

Das Volumen $V$ eines Rotationskörpers, der durch Rotation des Graphen der Funktion $f(y)$ über dem Intervall $[c, d]$ um die y-Achse entsteht, berechnet sich durch:

$$
V = \int_c^d \pi [f(y)]^2 \, dy
$$


## Herleitung der Längenberechnung

Die Bogenlänge eines Funktionsgraphen $f(x)$ im Intervall $[a, b]$ wird wie folgt hergeleitet:

Man betrachtet ein kleines Stück des Graphen zwischen $x$ und $x + \Delta x$. Die Länge dieses Stücks ist näherungsweise:

$$
\Delta s \approx \sqrt{(\Delta x)^2 + (\Delta y)^2}
$$

wobei $\Delta y = f(x + \Delta x) - f(x)$.

Für sehr kleine $\Delta x$ gilt:

$$
\Delta s \approx \sqrt{1 + \left(\frac{\Delta y}{\Delta x}\right)^2} \cdot \Delta x
$$

Im Grenzfall ($\Delta x \to 0$) ergibt sich das Integral:

$$
s = \int_a^b \sqrt{1 + [f'(x)]^2} \, dx
$$
