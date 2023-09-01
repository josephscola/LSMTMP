# Comment projeter un vecteur ?

## Projection par changement de base

1.  **Poser le repère** dans lequel l'angle est défini

2.  **Projeter** le vecteur dans le repère de travail $(\vec{i}, \vec{j})$
    en fonction de $q$

3.  **Exprimer** $\vec{i}$ et $\vec{j}$ dans le repère de
    l'énoncé $(\vec{u}_x, \vec{u}_y)$

4.  **Simplifier** l'expression du vecteur

## Projection par décomposition de l'angle

1.  **Poser l'angle** $\theta$ défini à partir du vecteur $\vec{u}_x$ de
    l'énoncé

2.  **Projeter** le vecteur dans le repère $(\vec{u}_x, \vec{u}_y)$ en
    fonction de $\theta$

3.  **Exprimer** $\theta$ en fonction de l'angle de l'énoncé $q$

4.  **Simplifier** l'expression du vecteur

```{important}
Les deux techniques sont **équivalentes**.
```

# Technique n$^\circ$ 1 : projection par changement de repère

```{image} ../liste/ProjectionVecteur.png
:width: 200px
:align: center
```
1.  **Poser la repère** dans lequel l'angle est défini

    $$\vec{i} = - \vec{u}_y;\quad \vec{j} = + \vec{u}_x$$

2.  **Projeter** le vecteur dans le repère de travail $(\vec{i}, \vec{j})$
    en fonction de $q$

    $$\overrightarrow{OM} = r (\cos q\, \vec{i} + \sin q\, \vec{j})$$

3.  **Exprimer** $\vec{i}$ et $\vec{j}$ dans le repère de
    l'énoncé $(\vec{u}_x, \vec{u}_y)$

    $$\overrightarrow{OM} = r \left( \cos q\, (-\vec{u}_y) + \sin q\, (+\vec{u}_x) \right)$$

4.  **Simplifier** l'expression du vecteur

    $$\overrightarrow{OM} = r (\sin q\, \vec{u}_x - \cos q\, \vec{u}_y)$$


# Technique n$^\circ$ 2 : projection par décomposition de l'angle

```{image} ../liste/ProjectionVecteur.png
:width: 200px
:align: center
```

1.  **Poser l'angle** $\theta$ défini à partir du vecteur $\vec{u}_x$ de
    l'énoncé

    $$\theta  = \angle{(\vec{u}_x, \overrightarrow{OM})} = q - \pi/2$$

2.  **Projeter** le vecteur dans le repère $(\vec{u}_x, \vec{u}_y)$ en
    fonction de $\theta$

    $$\overrightarrow{OM} = r (\cos \theta\, \vec{u}_x + \sin \theta\, \vec{u}_y)$$

3.  **Exprimer** $\theta$ en fonction de l'angle de l'énoncé $q$

    $$\overrightarrow{OM} = r (\cos (q - \pi/2)\, \vec{u}_x + \sin (q - \pi/2)\, \vec{u}_y)$$

4.  **Simplifier** l'expression du vecteur en utilisant les relations
    trigonométriques

    $$\overrightarrow{OM} = r (\sin q\, \vec{u}_x - \cos q\, \vec{u}_y)$$

