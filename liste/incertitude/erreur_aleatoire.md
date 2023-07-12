# Erreur aléatoire

Si les conditions de répétabilité sont remplies ( la mesure est répétées
$N$ fois dans les mêmes conditions), alors le meilleur estimateur de la
valeur vraie est la moyenne des $N$ valeurs mesurées.

$$m_\mathrm{mesure} = \frac{1}{N} \sum_{i=1}^{N} m_i$$

L'*erreur aléatoire* $\epsilon_i$ qui entache chaque valeur mesurée
$m_i$ est donc définie par la différence avec la valeur vraie
$m_{\mathrm{vraie}}$:

$$\epsilon_i = m_i - m_{\mathrm{vraie}}.$$

Réciproquement, la $i^\mathrm{eme}$ mesure s'exprime:

$$m_i = m_{\mathrm{vraie}} + \epsilon_i$$

Lorsque l'expérience est
répétées $N$ fois, la moyenne des valeurs mesurées s'écrit:

$$\begin{array}{rcl}
m_\mathrm{mesure}   &=& \frac{1}{N} \sum_{i=0}^{N} (m_\mathrm{vraie} + \epsilon_i) \\
                    &=& m_\mathrm{vraie} + \frac{1}{N} \sum_{i=0}^{N} \epsilon_i \\
                    &=& m_\mathrm{vraie} + \epsilon_\mathrm{moy}
\end{array}$$

De même que chaque $\epsilon_i$, $\epsilon_\mathrm{moy}$ ne peut donc
pas être connue complètement et doit être considérée comme une variable
aléatoire qui suit une loi de probabilité donnée par le contexte. Si $N$
est un grand nombre ($N\gtrsim 30$), la loi de probabilité de
$\epsilon_\mathrm{moy}$ peut être approchée par une loi normale centrée
et elle est caractérisée par sa moyenne et son écart-type. Dans le cas
de l'erreur expérimentale aléatoire, la moyenne est nulle, de sorte que
$\epsilon_\mathrm{moy}$ est caractérisée uniquement par son écart-type
$\sigma$.

Dans l'idéal, il faudrait faire tendre le nombre d'expériences vers
l'infini ($N \rightarrow \infty$) pour annuler $\epsilon$. En pratique,
$N$ n'est pas infini et l'erreur aléatoire $\epsilon_\mathrm{moy}$ n'est
pas nulle. Elle prend une valeur aléatoire distribuée autour de zéro
dans un intervalle dont la largeur est proportionnelle à $\sigma$. On
admettra que l'évolution de $\sigma$ quand $N$ augmente est la suivante:

$$\sigma = \frac{\sigma_0}{\sqrt{N}}$$

où $\sigma_0$ représente l'erreur
aléatoire d'une expérience unique parmi les $N$. Il faut donc par
exemple multiplier le nombre d'expériences par 100 pour diviser l'erreur
par 10.
