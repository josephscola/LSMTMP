Comment contrôler son résultat de calcul ?

Combien de molécules H\\(_2\\)O une bouteille de \\(V = 1.5\\) litre
contient-elle? Données numériques :

-   \\(V = 1.5\\) L = \\(1.5\cdot 10^{-3}\\) m\\(^{3}\\)

-   \\(\rho = 1.000\\) kg/L = \\(1.000 \cdot 10^{3}\\) kg/m\\(^{3}\\)

-   \\(\mathcal{M}_\mathsf{H_2O} = 18\\) g /mol = \\(18\cdot 10^{-3}\\)
    kg/mol

-   \\(\mathcal{N}_A = 6.02\cdot 10^{23}\\) mol\\(^{-1}\\)

Nombre de moles dans \\(V\\) :
\\[n = \frac{\rho V}{\mathcal{M}_\mathsf{H_2O}}\\]

Nombre de molécules dans \\(n\\) moles (et donc dans la bouteille) :
\\[X = n \mathcal{N}_A\\]

Expression littérale :
\\[X = \frac{\rho V \mathcal{N}_A}{\mathcal{M}_\mathsf{H_2O}}\\]

Comment contrôler son résultat de calcul ?

Analyse dimensionnelle (vérification) : \\[\begin{array}{rcl}
\left[
\frac{\rho V \mathcal{N}_A}{\mathcal{M}_\mathsf{H_2O}}
\right]
    &=& [\rho] \cdot [ V ] \cdot [\mathcal{N}_A] \cdot [\mathcal{M_\mathsf{H_2O}}]^{-1} \\
    &=& (ML^{-3}) \cdot L^{-3} \cdot N^{-1} \cdot (MN^{-1})^{-1} \\
    &=& 1 \\
\textcolor{red}{
\left[
\frac{\rho V \mathcal{N}_A}{\mathcal{M}_\mathsf{H_2O}}
\right]}
    &\textcolor{red}=& \textcolor{red}{ [X] }
\end{array}\\]

Ordre de grandeur (vérification) : \\[\begin{array}{rcl}
X   &=& \frac{10^{3} \time 1.5\cdot 10^{-3} \time 6.02\cdot 10^{23}}{1.8\cdot 10^{-2}} \\
    &=& \frac{1.5 \times 6.02}{1.8} \cdot 10^{3} \cdot 10^{-3} \cdot 10^{23} \cdot 10^{\textcolor{red}+2} \\
    &=& \frac{1.5 \times 6.02}{1.8} \cdot \textcolor{red}{10^{25}}
\end{array}\\]

Calcul machine : \\[X   = 5.016667 \cdot 10^{25}\\]

Confirmation par le calcul de la masse \\(m\\) des \\(X\\) molécules
d’eau : Données numériques :

-   masse atomique de l’hydrogène \\(m_H = 1.007978\\)

-   masse atomique de l’oxygène \\(m_O = 15.99940\\)

-   unité de masse atomique \\(u = 1.660538921 \cdot 10^{-27} kg\\)

\\[\begin{array}{rcl}
m   &=& X (2m_H + m_O) u \\
    &=& 5.017 \cdot 10^{25} \times (2\times 1.007978 + 15.99940) \times 1.66\cdot 10^{-27} \\
    &=& 5.017 \times 1.66 \times (2\times 1.007978 + 15.99940) \cdot 10^{25}\cdot 10^{-27} \\
    &=& 1.500258 \, \mathsf{kg} 
\end{array}\\]
