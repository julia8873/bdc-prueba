# Fuente: convergencia uniforme sin equicontinuidad (1).pdf

_Añadido por @julia:mi-matrix-local.dev el 1783236661._

[Página 1]
Yaojian Li

Sea $\{f_n\}$, $f_n : ]0, 1[ \to \mathbb{R}$ tal que $f_n(t) = \frac{1}{t} + \frac{1}{n} \quad \forall t \in ]0, 1[ \quad \forall n \in \mathbb{N}$

son funciones continuas y además convergen de forma puntual a $f$ en $]0, 1[$
con $f(t) : ]0, 1[ \to \mathbb{R}$, $f(t) = \frac{1}{t} \quad \forall t \in ]0, 1[$

$|f_n(t) - f(t)| = |\frac{1}{n}| \cdot \frac{1}{n}$ por lo que convergen de forma uniforme a $f$ en $]0, 1[$

sin embargo si tomamos $\varepsilon = \frac{1}{3}$, si fuera equicontinua
$\exists \delta > 0 : \exists N > \frac{1}{\sqrt{\delta}}$, si $n \ge N$, tenemos que
$$|\frac{1}{n} - \frac{1}{n+1}| = |\frac{1}{n^2+n}| \le |\frac{1}{n^2}| < \delta$, pero
$|f_n(\frac{1}{n}) - f_n(\frac{1}{n+1})| = 1 > \frac{1}{3} !!$$

Por tanto no son equicontinuas.

O también valdría el argumento de que si fueran equicontinuas, $f_n$ serían uniformemente continuas, pero no lo son, por tanto, por contrarrecíproco, no son equicontinuas

Yaojian Li