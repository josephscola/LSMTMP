# Analyse dimensionnelle pour la mécanique

-   vecteur position (dont la norme est exprimée en m):

    $$  \begin{array}{rcl}
    \vec{OM} &=& \left[ \Vert \vec{OM} \Vert \right] \\
          &=& L^1 \textcolor{lightgray}{M^0 T^0 I^0 \Theta^0 N^0 J^0} \\
          &=& L 
    \end{array}$$  

-   vecteur vitesse (dont la norme est exprimée en m/s) :

    $$  \begin{array}{rcl}
    \vec{v} = \frac{\mathrm{d} \vec{OM}}{\mathrm{d} t}
    \Rightarrow
    [\vec{v}] &=& \frac{\left[\mathrm{d} \vec{OM} \right]}{ \left[ \mathrm{d} t \right] } \\
          &=& L^1 \textcolor{lightgray}{M^0} T^{-1} \textcolor{lightgray}{I^0 \Theta^0 N^0 J^0} \\
          &=& LT^{-1}
    \end{array}$$  

-   vecteur accélération (dont la norme est exprimée en m/s\\(^2\\)) :

    $$  \begin{array}{rcl}
    \vec{a} = \frac{\mathrm{d}^2 \vec{OM}}{\mathrm{d} t^2}
    \Rightarrow
    [\vec{a}] &=&  \frac{\left[\mathrm{d} \vec{v} \right]}{\left[ \mathrm{d} t \right]}  \\
              &=& L^1 \textcolor{lightgray}{M^0} T^{-2} \textcolor{lightgray}{I^0 \Theta^0 N^0 J^0} \\
              &=& LT^{-2}
    \end{array}$$  

-   vecteur force (dont la norme est exprimée en newtons):

    $$  \begin{array}{rcl}
    \vec{F} = m\vec{g}
    \Rightarrow
    [\vec{F}]   &=& \left[ \Vert m\vec{g} \Vert \right]\\
                &=& L^1 M^1 T^{-2} \textcolor{lightgray}{I^0 \Theta^0 N^0 J^0} \\
                &=& LMT^{-2}
    \end{array}$$  

-   énergie (exprimée en joules):

$$  \begin{array}{rcl}
    \mathcal{E} = \frac{1}{2} mv^2
    \Rightarrow
    [\mathcal{E}] &=& \left[\frac{1}{2} mv^2 \right] \\
                  &=& 1M \times [v] \\
                  &=& L^2 M^1 T^{-2} \textcolor{lightgray}{I^0 \Theta^0 N^0 J^0} \\
          &=& L^2M^1T^{-2}
    \end{array}$$  

<!-- -->

-   puissance (exprimée en watts):

$$  \begin{array}{rcl}
    \mathcal{P} = \vec{F}\cdot \vec{v} 
    \Rightarrow
    [\mathcal{P}]   &=& \left[ \Vert \vec{F} \Vert \right] \times \left[ \Vert \vec{v} \Vert \right] \\
                    &=& LMT^{-2} \times LT^{-1} \\
                    &=& L^2 M^1 T^{-3} \textcolor{lightgray}{I^0 \Theta^0 N^0 J^0} \\
                    &=& L^2M^1T^{-3}
    \end{array}$$  
