# Projections orthogonale d'un vecteur : produit scalaire

## Définition du produit scalaire

On rappelle la définition *géométrique* du produit scalaire :
$\vec{u} \cdot \vec{v} = \Vert \vec{u} \Vert \cdot \Vert \vec{v} \Vert \cdot \cos (\vec{u},\vec{v})$


## Projection dans une base orthonormée directe
$$\begin{array}{rcl}
r\cdot \cos \theta &=& ||\overrightarrow{OM} || \cdot 1 \cdot \cos \theta \\
                   &=& ||\overrightarrow{OM} || \cdot ||\vec{u}_x || \cdot \cos (\vec{u}_x, \overrightarrow{OM}) \\
                   &=& \overrightarrow{OM} \cdot \vec{u}_x 
\end{array}$$

En procédant de même suivant $\vec{u}_y$, on retrouve finalement les projections orthogonales de $\overrightarrow{OM}$ dans $(\vec{u}_x, \vec{u}_y)$ :

$$\left\{
\begin{array}{rcl}
r\cdot \cos \theta &=& \overrightarrow{OM} \cdot \vec{u}_x = x \\
r\cdot \sin \theta &=& \overrightarrow{OM} \cdot \vec{u}_y = y
\end{array}
\right.$$

```{image} ../liste/trigo_triangle_vect.png
:width: 200px
:align: center
```


```{important}
Résultat important Le **produit scalaire** d'un vecteur $\overrightarrow{OM}$ et d'un
vecteur unitaire représente la **projection orthogonale** de $\overrightarrow{OM}$ sur
la direction du vecteur unitaire.
```
