Grandeurs pour l’optique

-   vergence (exprimée en dioptries) : \\[V = \frac{1}{f}\\]

-   indice de réfraction (sans unité) : \\[n = \frac{c}{v}\\]

Grandeurs pour l’optique

-   vergence (exprimée en dioptries) : \\[\begin{array}{rcl}
    V = \frac{1}{f}
    \Rightarrow
    [V] &=& \frac{1}{[f]} \\
        &=& L^{-1} \textcolor{lightgray}{M^0 T^0 I^0 \Theta^0 N^0 J^0} \\
        &=& L^{-1}
    \end{array}\\]

-   indice de réfraction (sans unité) : \\[\begin{array}{rcl}
    n = \frac{c}{v} \\
    \Rightarrow
    [n] &=& [c] \times \left[ v \right]^{-1} \\
        &=& LT^{-1} \times (LT^{-1})^{-1} \\
        &=& \textcolor{lightgray}{L^0 M^0 T^0 I^0 \Theta^0 N^0 J^0} \\
        &=& 1
    \end{array}\\]

Grandeurs pour la mécanique

-   vecteur position (dont la norme est exprimée en m):

-   vecteur vitesse (dont la norme est exprimée en m/s)

-   vecteur accélération (dont la norme est exprimée en m/s\\(^2\\))

-   vecteur force (dont la norme est exprimée en newtons)

-   énergie (exprimée en joules)

-   puissance (exprimée en watts)

Grandeurs pour la mécanique

-   vecteur position (dont la norme est exprimée en m):
    \\[\begin{array}{rcl}
    [\OM] &=& \left[ \Vert \OM \Vert \right] \\
          &=& L^1 \textcolor{lightgray}{M^0 T^0 I^0 \Theta^0 N^0 J^0} \\
          &=& L 
    \end{array}\\]

-   vecteur vitesse (dont la norme est exprimée en m/s) :
    \\[\begin{array}{rcl}
    \vv = \frac{\dd \OM}{\dd t}
    \Rightarrow
    [\vv] &=& \frac{\left[\dd \OM \right]}{ \left[ \dd t \right] } \\
          &=& L^1 \textcolor{lightgray}{M^0} T^{-1} \textcolor{lightgray}{I^0 \Theta^0 N^0 J^0} \\
          &=& LT^{-1}
    \end{array}\\]

-   vecteur accélération (dont la norme est exprimée en m/s\\(^2\\)) :
    \\[\begin{array}{rcl}
    \vec{a} = \frac{\dd^2 \OM}{\dd t^2}
    \Rightarrow
    [\vec{a}] &=&  \frac{\left[\dd \vec{v} \right]}{\left[ \dd t \right]}  \\
              &=& L^1 \textcolor{lightgray}{M^0} T^{-2} \textcolor{lightgray}{I^0 \Theta^0 N^0 J^0} \\
              &=& LT^{-2}
    \end{array}\\]

Grandeurs pour la mécanique

-   vecteur force (dont la norme est exprimée en newtons):
    \\[\begin{array}{rcl}
    \vec{F} = m\vec{g}
    \Rightarrow
    [\vec{F}]   &=& \left[ \Vert m\vec{g} \Vert \right]\\
                &=& L^1 M^1 T^{-2} \textcolor{lightgray}{I^0 \Theta^0 N^0 J^0} \\
                &=& LMT^{-2}
    \end{array}\\]

-   énergie (exprimée en joules): \\[\begin{array}{rcl}
    \mathcal{E} = \frac{1}{2} mv^2
    \Rightarrow
    [\mathcal{E}] &=& \left[\frac{1}{2} mv^2 \right] \\
                  &=& 1M \times [v] \\
                  &=& L^2 M^1 T^{-2} \textcolor{lightgray}{I^0 \Theta^0 N^0 J^0} \\
          &=& L^2M^1T^{-2}
    \end{array}\\]

<!-- -->

-   puissance (exprimée en watts): \\[\begin{array}{rcl}
    \mathcal{P} = \vec{F}\cdot \vv 
    \Rightarrow
    [\mathcal{P}]   &=& \left[ \Vert \vec{F} \Vert \right] \times \left[ \Vert \vv \Vert \right] \\
                    &=& LMT^{-2} \times LT^{-1} \\
                    &=& L^2 M^1 T^{-3} \textcolor{lightgray}{I^0 \Theta^0 N^0 J^0} \\
                    &=& L^2M^1T^{-3}
    \end{array}\\]
