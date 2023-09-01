# Repères de projection

La représentation mathématique d'un vecteur nécessite la définition
d'un repère de projection.

## Définition

On choisit toujours un repère
<span
style="color: blue">ortho</span><span style="color: green">normée</span>
<span style="color: red">directe</span> $(O,\vec{u}, \vec{v})$ :

-   $O$ : origine du repère

-   <span style="color: blue">$\vec{u} \perp \vec{v}$</span>

-   <span style="color: green">$||\vec{u}|| = ||\vec{v}|| = 1$</span>
    ($\vec{u}$ et $\vec{v}$ sont dits *unitaires*)

-   l’angle entre $\vec{u}$ et $\vec{v}$ vaut <span
    style="color: red">+</span>$\pi/2$

```{image} ../liste/vect_compo_rep.png
:width: 200px
:align: center
```

```{important}
-   La composante $a$ est la **projection orthogonale** de $\overrightarrow{OM}$ sur la
    direction de $\vec{u}$.

-   La composante $b$ est la **projection orthogonale** de $\overrightarrow{OM}$ sur la
    direction de $\vec{v}$.
```

Le vecteur $\overrightarrow{OM}$ est entièrement décrit par ses *composantes* $a$ et $b$
dans le repère $(O,\vec{u},\vec{v})$.


## Choix du repère

Il existe une infinité de repères de projection.

On choisit généralement le repère le plus commode pour faire les
calculs.

```{image} ../liste/vect_multi_rep.png
:width: 200px
:align: center
```
Dans chaque repère l'expression du vecteur $\overrightarrow{OM}$ est **unique** :

## Le repère cartésien


$$
\overrightarrow{OM} = x \vec{u}_x + y \vec{u}_y =
\left( \begin{array}{c}
x \\ y
\end{array} \right)_{(\vec{u}_x,\vec{u}_y)}
$$


```{image} ../liste/vect_rep_cartesien.png
:width: 200px
:align: center
```
```{Attention}
Dans cette représentation, les *coordonnées* du point $M$ coïncident
avec les *composantes* du vecteur position $\overrightarrow{OM}$.
```
