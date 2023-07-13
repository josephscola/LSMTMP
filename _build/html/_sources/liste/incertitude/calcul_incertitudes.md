# Incertitude absolue

On considère une _grandeur physique_ $f$ dépendant de 3 _paramètres_ $x$, $y$, $z$.
Si la façon dont $F$ dépend de ses paramètres est connue, on peut **représenter la _grandeur physique_ comme une _fonction_** $f$ dépendant de 3 _variables_ qui représentent les _paramètres physiques_.

Si la connaissance des paramètres est entachée des erreurs :

$$
\begin{align}
x &= x_0 \pm \Delta x \\
y &= y_0 \pm \Delta y \\
z &= z_0 \pm \Delta z \\
\end{align}
$$

alors se pose la question de  l'incertitude sur $f(x_0, y_0, z_0)$, c'est-à-dire :
>"de combien $f$ varie-t-elle lorsque $x$ varie de $\pm \delta x$ autour de $x_0$, $y$ varie de $\pm \delta y$ autour de $y_0$ et $z$ varie de $\pm \delta z$ autour de $z_0$ ?"

Cette question est très proche de celle à laquelle la _différentielle_ apporte une réponse.
En effet, la différentielle d'une fonction $\mathrm{d}f (x_0, y_0, z_0)$ définit 
>"de combien combien $f$ varie lorsque $x$ varie d'un petit incrément (positif) $\mathrm{d}x$ autour de $x_0$, $y$ varie de $\mathrm{d}y$ autour de $y_0$ et $z$ varie de $\mathrm{d}z$ autour de $z_0$.

La différentielle de $f$ est définie par :

$$
\mathrm{d} f =  \left( \dfrac{\partial f}{\partial x} \right)_{y,z} \mathrm{d}x
            + \left( \dfrac{\partial f}{\partial y} \right)_{x,z} \mathrm{d} y
            + \left( \dfrac{\partial f}{\partial z} \right)_{x,y} \mathrm{d} z
$$

où $\left( \dfrac{\partial f}{\partial x}\right)_{y,z}$ est la _dérivée partielle de $f$ par rapport à $x$_, qui se calcule comme la dérivée de $f$ par rapport à $x$ en considérant que toutes les autres variables de $f$ (dans l'exemple $y$ et $z$) sont des constantes.

L'_incertitude absolue_ est obtenue en additionnant les termes en valeurs absolues pour que les contributions s'ajoutent quel que soient les signe des dérivées partielles et des variations des paramètres $x$, $y$ et $z$ :

$$
\Delta f =  \left| \left( \dfrac{\partial f}{\partial x} \right)_{y,z} \right| \Delta x
            + \left| \left( \dfrac{\partial f}{\partial y} \right)_{x,z} \right| \Delta y
            + \left| \left( \dfrac{\partial f}{\partial z} \right)_{x,y} \right| \Delta z
$$


