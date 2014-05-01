A faire :
------------------

Voir l'onglet "Issues".


"Règle" de syntaxe lors de l'écriture du rapport :
--------------------------------------------------
Afin que toutes les parties du rapport que nous rédigons séparément soient un peu homogène, voici quelques petites "règles" (entre guillements) à suivre au niveau syntaxe :

Ne pas utiliser de :
- \bigbreak ;
- \\ ;
- etc.

Pour passer un espace.

**Insèrer un nombre**
Pour insèrer un nombre *seul* (sans unité) : utiliser 
```
\numprint{42}
```

**Insèrer une grandeur**
Pour insèrer une grandeur physique avec unité : utiliser
```
\SI{42}{\meter}
```
Documentation : ftp://ftp.tex.ac.uk/ctan%3A/macros/latex/exptl/siunitx/siunitx.pdf

**Insèrer une figure**
Utiliser :

```
\begin{figure}[ht!]
	\centering
	\includegraphics[scale=0.6]{haut-parleur.png}
	\caption{Schéma d'un haut-parleur}
	\label{hp-scheme}
\end{figure}
```

**Formules mathématiques**
En ligne (dans une phrase) : 
```
$x=42$
```
En bloc (saut à la ligne automatique et centré) : 
```
$$x=42$$
```

**Pour faire un grapgique**
PGFPlots : http://pgfplots.sourceforge.net/pgfplots.pdf

**Pour faire un circuit**
Circuitikz : http://ctan.math.washington.edu/tex-archive/graphics/pgf/contrib/circuitikz/circuitikzmanual.pdf

**Pour les noms propres placés au milieu d'un texte**

```
\textsc{Laplace}
```



