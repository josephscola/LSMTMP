## Point technique : différentielle d'une fonction à plusieurs variables

_Dans cette partie est introduite une notion du programme du second semestre de licence._

Soit la fonction réelle à trois variables réelles:

$$
\begin{array}{rccc}
f : &\mathbb{R}^3   &\mapsto & \mathbb{R} \\
 &      (x,y,z)     & = &      f(x,y,z)
\end{array}
$$

La _différentielle_ d'une fonction à plusieurs variables représente la
quantité par laquelle varie cette fonction lorsque chacune de ses
variables varie d'une quantité élémentaire. 

La *différentielle* de la fonction $f$, si elle existe, est définie par

$$
\mathrm{d}f \equiv \sum\limits_{\alpha=x,y,z} \dfrac{\partial f}{\partial \alpha} \mathrm{d}\alpha
            = \dfrac{\partial f}{\partial x} \mathrm{d}x
             + \dfrac{\partial f}{\partial y} \mathrm{d}y
             + \dfrac{\partial f}{\partial z} \mathrm{d}z
$$



 De même que
toutes les fonctions d'une seule variable ne sont pas dérivables, toutes
les fonctions de plusieurs variables ne sont pas différentiable. Il faut
que toutes ses dérivées partielles existent et soient continues pour
qu'une fonction soit différentiable sur un intervalle considéré.

Soit l'expression différentielle définie par


$$
\delta W = g(x,y,z) \mathrm{d}x + h(x,y,z) \mathrm{d}y + k(x,y,z) \mathrm{d}z.
$$



$\delta W$ est une *différentielle totale* si et seulement si il existe
une fonction $f$ telle que $\mathrm{d}f = \delta W$, si et seulement si
les trois relations suivantes sont vérifiées:


$$
g(x,y,z) = \dfrac{\partial f}{\partial x};
h(x,y,z) = \dfrac{\partial f}{\partial y};
k(x,y,z) = \dfrac{\partial f}{\partial z};
$$


 On a alors
$f = \int \delta W$.

Dans le cas d'une fonction à deux variables, on admettra le théorème
suivant:

>**Théorème de Schwarz**
L'expression différentielle $\delta W = g\mathrm{d}x + h \mathrm{d}y$ est totale si et seulement si les dérivées croisées sont égales, _i.e._
$\dfrac{\partial g}{\partial y} = \dfrac{\partial h}{\partial x}$.
