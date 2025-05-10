# Ejercicio 5

## a

$|x.(y.\alpha)| = 1 + |(y.\alpha)| = 1 + 1 + |\alpha| = 2+ |\alpha|$ 

---

## b

$|\alpha^r| = |\alpha|$

Por inducción estructural:

caso base $\alpha = \lambda$

$$
|\lambda^r| = |\lambda| \hspace{2em} \text{definición de $\lambda$}
$$

paso inductivo $\alpha = x.\beta$

$$
\begin{align*}
    |\alpha^r| = |\beta^r.x| &= |\beta^r| + 1 \hspace{2em} \text{def de $|\cdot|$}\\
                            &= |\beta| +1 \hspace{2em} \text{HI}\\
                            &= |x.\beta| = |\alpha|
\end{align*}
$$

---

## c

$|\alpha x \beta| =  |\alpha| + |x \beta| = |\alpha| + 1 +|\beta| = |x \alpha \beta|$

---

## d

$|\alpha.\alpha| = |\alpha| + |\alpha| = 2 |\alpha|$

---

## e

Por inducción estructural con cualquier $\beta$ fijo.

caso $\alpha = \lambda$

$(\alpha.\beta)^r = (\lambda.\beta)^r = \beta^r = \beta^r.\lambda = \beta^r.\lambda^r = \beta^r\alpha^r$

paso inductivo $\alpha = x.\alpha'$

Hipotesis inductiva $(\alpha'.\beta)^r=\beta^r \alpha'^r$

$(\alpha.\beta)^r=(x.\alpha'.\beta)^r=(\alpha'.\beta)^r.x = \beta^r \alpha'^r.x = \beta^r\alpha^r$

---

## f

caso base

$(\alpha^r)^r = (\lambda^r)^r = \lambda$

paso inductivo $\alpha = x.\beta$

$(\alpha^r)^r = ((x.\beta)^r)^r = (\beta^r.x)^r = x.\beta = \alpha$

---

## g
