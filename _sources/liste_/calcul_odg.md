Pourquoi et comment calculer des ordres de grandeur ?

On considère deux corps de masse \\(m_1 = 61\\) kg et \\(m_2 = 72\\) kg
à la surface de la Terre de masse \\(m_T = 5.992\cdot 10^{24}\\) kg.
L’attraction gravitationnelle s’exerce entre \\(m_T\\) et \\(m_1\\),
entre \\(m_T\\) et \\(m_2\\) et entre \\(m_1\\) et \\(m_2\\), soient
trois forces dont on se propose de comparer les intensités. L’intensité
de la force d’attraction gravitationnelle s’exprime (en newtons) :
\\[\Vert \vF_{A\rightarrow B} \Vert = \mathcal{G} \frac{m_Am_B}{AB^2}, \quad 
\mathcal{G} = 6.6742\cdot 10^{-11} \,\mathsf{Nm}^2\mathsf{kg}^{-2}\\]

On suppose les corps 1 et 2 distants de 1 m (distanciation physique
oblige !); étant à la surface de la Terre, ils sont tous les deux
séparés du centre de la Terre d’une distance égale au rayon de la Terre
\\(R_T = 6371\\) km.

Pourquoi et comment calculer des ordres de grandeur ?

\\[\begin{array}{rcl}
\Vert \vF_{2\rightarrow 1}\Vert 
    &=& 6.6742\cdot 10^{-11} \frac{6.1\cdot 10^{1} \times 7.2\cdot 10^{1}}{1^2} \\
    &=& (6.6742 \times 6.1 \times 7.2) \cdot 10^{-11} \cdot 10^{1} \cdot 10^{1} \\
    &=& (6.6742 \times 6.1 \times 7.2) \cdot \textcolor{red}{10^{-9}} \textsf{\,N}
\end{array}\\] \\[\begin{array}{rcl}
\Vert \vF_{T\rightarrow 1}\Vert 
    &=& 6.6742\cdot 10^{-11} \frac{6.1\cdot 10^{1} \times 5.992\cdot 10^{24}}{(6.371 \cdot 10^{6})^2} \\
    &=& (6.6742 \times \frac{6.1 \times 5.992}{6.371^2})
            \cdot 10^{-11} \cdot \frac{10^{1} \cdot 10^{24}}{(10^{6\times 2})} \\
    &=& (6.6742 \times \frac{6.1 \times 5.992}{6.371^2}) \cdot \textcolor{red}{10^{2}} \textsf{\,N}
\end{array}\\] \\[\begin{array}{rcl}
\Vert \vF_{T\rightarrow 2}\Vert 
    &=& 6.6742\cdot 10^{-11} \frac{7.2\cdot 10^{1} \times 5.992\cdot 10^{24}}{(6.371 \cdot 10^{6})^2} \\
    &=& (6.6742 \times \frac{7.2 \times 5.992}{6.371^2})
            \cdot 10^{-11} \cdot \frac{10^{1} \cdot 10^{24}}{(10^{6\times 2})} \\
    &=& (6.6742 \times \frac{7.2 \times 5.992}{6.371^2}) \cdot \textcolor{red}{10^{2}} \textsf{\,N}
\end{array}\\]
\\[\Vert \vF_{2\rightarrow 1}\Vert \ll \Vert \vF_{T\rightarrow 1}\Vert \approx \Vert \vF_{T\rightarrow 2}\Vert\\]
L’évaluation des parenthèses n’est pas nécessaire. Les ordres de
grandeurs suffisent à établir que l’interaction gravitationnelle entre
les corps 1 et 2 est négligeable devant celle qui s’exerce entre chacun
d’entre eux et la Terre.
