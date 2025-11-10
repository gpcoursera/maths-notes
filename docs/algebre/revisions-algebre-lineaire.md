# Révisions d’Algèbre Linéaire

### 1. Réduction des endomorphismes
- **[Gourdon]** *Algèbre* (2ᵉ éd.), section 4.4 — Jordan / Dunford.
- [**Fiche ENS Rennes : Décomposition de Dunford**](../assets/pdfs/decomp_dunford.pdf){ target=_blank }
- Sujet [**CCINP MP 2021**](../assets/pdfs/CCINP_2021_MP_Maths_2_e.pdf){ target=_blank } — Décomposition de **Dunford**.
- **Exercices** sur les décompositions de matrices/endomorphismes (**LU**, **Jordan**, **SVD**, etc.).
- **YouTube** — vidéos de **Phil Caldero**.
<iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?si=d2hBjv69IaoJUG39&amp;list=PLI-uIUgbJUl6srxnzN-jumwbXG4RTGXuX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
- **[Mansuy]** — (référence à compléter).

### 2. Théorème de Gerstenhaber
- Sujet [**Mines–Ponts MP 2020**](../assets/pdfs/Mines-Ponts_2020_MP_Maths_1_e.pdf){ target=_blank }

### 3. Théorème de Burnside
- [**Fiche ENS Rennes : Burnside**](../assets/pdfs/burnside.pdf){ target=_blank }
- **Exos Oraux X–ENS Algèbre 2** — Exercices 3.8, 2.28 et 1.10.
- [**Agrég. Interne 2021**](../assets/pdfs/Agreg-Interne_2021_Maths_ep1.pdf){ target=_blank }
- **Sujet : Entrelacement de valeurs propres**, [**X–ENS MP 2015**](../assets/pdfs/X-ENS_2015_Maths_A.pdf){ target=_blank }

### 4. Théorème de Perron–Frobenius
- [**Notes Perron-Frobenius**](../assets/pdfs/Perron-Frobenius.pdf)
- [**Développement Agreg Perron-Frobenius et Chaînes de Markov**](../assets/pdfs/Perron-Frobenius-Chaines-Markov.pdf)
- [**X–ENS PC 2017**](../assets/pdfs/X-ENS_2017_PC_Maths_e.pdf){ target=_blank }
- [**Mines-Ponts 2006**](../assets/pdfs/Mines-Ponts_2006_MP_Maths_1_e.pdf){ target=_blank }
- [**Centrale 2023**](../assets/pdfs/Centrale_2023_PC_Maths_1_e.pdf){ target=_blank }

### 5. Matrices symétriques et endomorphismes auto-adjoints
- [**Leçon 157 Agreg : Matrices symétriques et hermitiennes**](https://agreg.skyost.eu/lecons/157/){ target=_blank }
#### Résultats importants et développements
- Algorithme de Gauss
- Théorème : critère de Sylvester
- Théorème spectral
- Décompostion polaire
#### Exercices types oraux CPGE/Agrég.
##### Ex 1. Décomposition polaire
<div class="exo-maths">
Soient : \(
O_n(\mathbb{R}) = \{\, M \in M_n(\mathbb{R}) \mid {}^t M M = I_n \,\},
\) le <b>groupe orthogonal</b>
   et \( S_n^{++}(\mathbb{R}) \) l’ensemble des <b>matrices symétriques définies positives</b>.

On considère l’application :
\(
\varphi : O_n(\mathbb{R}) \times S_n^{++}(\mathbb{R}) \longrightarrow GL_n(\mathbb{R}),
\quad (O,S) \longmapsto OS.
\)
<p>
Montrer que \( \varphi \) est une bijection.
</div>
##### Ex 2. Exponentielle des matrices symétriques
<div class="exo-maths">
Montrer l’homéomorphisme :
\(
\exp : S_n(\mathbb{R}) \longrightarrow S_n^{++}(\mathbb{R}),
\)
où :
<ul>
<li>\( S_n(\mathbb{R}) \) désigne l’ensemble des <b>matrices symétriques réelles</b>,</li>
<li>\( S_n^{++}(\mathbb{R}) \) celui des <b>matrices symétriques définies positives</b> réelles.</li>
</ul>
</div>
##### Ex 3. Compacité du groupe orthogonal
<div class="exo-maths">
Montrer que le <b>groupe orthogonal</b> :
\(
O_n(\mathbb{R}) = \{\, M \in GL_n(\mathbb{R}) \mid {}^t M M = I_n \,\}
\)
est <b>compact</b>.
<p>
<i>Indication</i> : montrer que \( O_n(\mathbb{R}) \) est un sous-ensemble fermé et borné de \( M_n(\mathbb{R}) \).
</div>
##### Ex4. Théorème spectral
<div class="exo-maths">
Montrer le <b>théorème spectral</b> :

Si \( A \) est une <b>matrice symétrique réelle</b>, alors elle est <b>diagonalisable sur</b> \( \mathbb{R} \).
<p>
<i>Autrement dit, il existe une matrice orthogonale</i> \( P \in O_n(\mathbb{R}) \) <i>telle que :</i>
\(
{}^t P A P = D,
\)
<i>où</i> \( D \) <i>est diagonale réelle</i>.
</div>
#### Sujets de concours
1. Sylvester. [**CCINP MP 2024**](../assets/pdfs/CCINP_2024_MP_Maths_2_e.pdf){ target=_blank }
2. Théorème spectral et séries entières. [**X-ENS 2023 MP Maths B**](../assets/pdfs/X-ENS_2023_MP-MPI_Maths_B_e.pdf){ target=_blank }
3. [**Mines-Ponts P' 1990**](../assets/pdfs/Mines-Ponts_1990_P_Maths_2_ea.pdf){ target=_blank }
4. Étude de certaines matrices symétriques réelles. [**X 2005 MP**](../assets/pdfs/X_2005_MP_Maths_2_e.pdf){ target=_blank }
5. Décomposition polaire et applications. [**Centrale 2013 MP Maths**](../assets/pdfs/Centrale_2013_MP_Maths_2_e.pdf){ target=_blank }
6. Matrices symétriques positives, ordre de Löwner, fonctions matriciellement croissantes. [**Mines-Ponts 2006 PSI**](../assets/pdfs/Mines-Ponts_2006_PSI_Maths_2_e.pdf){ target=_blank }
### 6. Topologie et algèbre linéaire/réduction
- [**Fiches exos : Topologie et algèbre linéaire**](../assets/pdfs/exos-topo-matricielle.pdf){ target=_blank }
- [**Notes Sage : Topologie matricielle**](../assets/pdfs/TopoMat.pdf){ target=_blank }
- [**Notes Agreg ENS Rennes : Topologie des espaces de matrices**](../assets/pdfs/agreg_document_topologie_matrices.pdf){ target=_blank }

### 7. Autres théorèmes fondamentaux
- [Théorème de la **base incomplète**](./base-incomplete.md)
- [Théorème du **rang**](./th-rang.md)
- [**Lemme des noyaux**](./lemme-noyaux.md)
- [Théorème de **Cayley–Hamilton**](../assets/pdfs/CaylHami.pdf){ target=_blank }

---
### Références générales
- ENS Rennes : [**Cours d'Algèbre Linéaire et Bilinéaire**](../assets/pdfs/AL3.pdf){ target=_blank }
- P. Caldero (Lyon I) : [**Voyage en Algébrie**](../assets/pdfs/Voyage-en-Algebrie.pdf){ target=_blank }
- **[Grifone]** — Algèbre Linéaire - Cépaduès - 7e édition.
- **[Tauvel]** — Algèbre linéaire - Calvage & Mounet.
---
### TODO (liens & ressources)
- [ ] Ajouter les liens/biblios pour **Gourdon**, **Mansuy**, **Grifone**, **Tauvel**.
- [ ] Lier une liste d’exercices (LU, Jordan, SVD).
- [ ] Intégrer des rappels de définitions et énoncés types (Jordan, Dunford, Burnside, Perron–Frobenius).
