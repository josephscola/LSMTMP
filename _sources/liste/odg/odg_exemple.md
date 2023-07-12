# Comment calculer un ordre de grandeur ?

Considérons la force gravitationnelle entre la Terre et un corps de $m = 10$ kg situé au niveau de la mer.
On rappelle les valeurs numériques intervenant dans cette expression :
- constante gravitationnelle universelle : $\mathcal{G} = 6.674\cdot  10^{-11}$ m$^3$ kg$^{-1}$s$^{−2}$
- masse de la Terre : $m_T = 5.974\cdot 10 ^{24}$ kg
- rayon de la Terre : $R = 6.4$ km

**Etape 1** L'expression littérale de l'intensité de cette force est :

$$
F = \mathcal{G} \frac{m_Tm}{R^2}
$$

**Etape 2** L'expression littérale se réécrit en exprimant toutes les valeurs numériques dans son unité du système international :

$$
F = 6.674\cdot 10 ^{-11}  \frac{5.974\cdot 10^{24} \times 10^1}{(6.4\cdot 10^{6})^2}
$$

**Etape 3** L'expression est remplacée par une version simplifiée ne tenant compte que de l'ordre de grandeur :

$$
\begin{align}
F &\approx 10^{-11}  \frac{10^{24} \times 10^1}{(10^{6})^2} \\
  &\approx 10^{-11 + 24 + 1 - (6\times 2)} \\
F &\approx 10^{2} \, \mathrm{N}
\end{align}
$$
