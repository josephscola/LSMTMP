# Incertitude relative

L'incertitude relative se définit par

$$
\dfrac{\Delta f}{f} = \dfrac{1}{f} 
                        \left[
                        \left| \left( \dfrac{\partial f}{\partial x} \right)_{y,z} \right| \Delta x
                        + \left| \left( \dfrac{\partial f}{\partial y} \right)_{x,z} \right| \Delta y
                        + \left| \left( \dfrac{\partial f}{\partial z} \right)_{x,y} \right| \Delta z
                        \right]
$$

 L'incertitude relative peut être
obtenue par le calcul direct de la différentielle de $f$ ou bien par la
méthode dite des \"logarithmes\" qui s'applique particulièrement bien
pour des fonctions sous forme de produits. On obtient directement
$\mathrm{d} f / f$ en remarquant que 

$$
\begin{array}{rcl}
\mathrm{d} (\ln f) &=& \dfrac{\mathrm{d} (\ln f)}{\mathrm{d} f} \mathrm{d} f \\
            &=& \dfrac{\mathrm{d} f}{f}.
\end{array}
$$
