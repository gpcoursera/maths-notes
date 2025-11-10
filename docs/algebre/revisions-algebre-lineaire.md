# Révisions d’Algèbre Linéaire

### 1. Réduction des endomorphismes
- **[Gourdon]** *Algèbre* (2ᵉ éd.), section 4.4 — Jordan / Dunford.
- [**Fiche ENS Rennes : Décomposition de Dunford**](../assets/pdfs/decomp_dunford.pdf){ target=_blank }
- Sujet [**CCINP MP 2021**](../assets/pdfs/CCINP_2021_MP_Maths_2_e.pdf){ target=_blank } — Décomposition de **Dunford**.
- **Exercices** sur les décompositions de matrices/endomorphismes (**LU**, **Jordan**, **SVD**, etc.).
- **YouTube** — vidéos de **Phil Caldero**.
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
- Décomposition polaire

Soient :

- \( O_n(\mathbb{R}) \) le **groupe orthogonal** :
  \[
  O_n(\mathbb{R}) = \{\, M \in M_n(\mathbb{R}) \mid {}^t M M = I_n \,\},
  \]
- \( S_n^{++}(\mathbb{R}) \) l’ensemble des **matrices symétriques définies positives**.

On considère l’application :
\[
\varphi : O_n(\mathbb{R}) \times S_n^{++}(\mathbb{R}) \longrightarrow GL_n(\mathbb{R}),
\quad (O,S) \longmapsto OS.
\]

**Montrer que** \( \varphi \) **est une bijection.**

- Exponentielle des matrices symétriques

Montrer l’homéomorphisme :
\[
\exp : S_n(\mathbb{R}) \longrightarrow S_n^{++}(\mathbb{R}),
\]
où :
- \( S_n(\mathbb{R}) \) désigne l’ensemble des **matrices symétriques réelles**,  
- \( S_n^{++}(\mathbb{R}) \) celui des **matrices symétriques définies positives** réelles.

- Compacité du groupe orthogonal

Montrer que le **groupe orthogonal** :
\[
O_n(\mathbb{R}) = \{\, M \in GL_n(\mathbb{R}) \mid {}^t M M = I_n \,\}
\]
est **compact**.

*Indication :* montrer que \( O_n(\mathbb{R}) \) est un sous-ensemble fermé et borné de \( M_n(\mathbb{R}) \).

- Théorème spectral

Montrer le **théorème spectral** :

> Si \( A \) est une **matrice symétrique réelle**, alors elle est **diagonalisable sur** \( \mathbb{R} \).

Autrement dit, il existe une matrice orthogonale \( P \in O_n(\mathbb{R}) \) telle que :
\[
{}^t P A P = D,
\]
où \( D \) est diagonale réelle.

#### Sujets de concours
- Sylvester. [**CCINP MP 2024**](../assets/pdfs/CCINP_2024_MP_Maths_2_e.pdf){ target=_blank }
- Théorème spectral et séries entières. [**X-ENS 2023 MP Maths B**](../assets/pdfs/X-ENS_2023_MP-MPI_Maths_B_e.pdf){ target=_blank }
- [**Mines-Ponts P' 1990**](../assets/pdfs/Mines-Ponts_1990_P_Maths_2_ea.pdf){ target=_blank }
- Étude de certaines matrices symétriques réelles. [**X 2005 MP**](../assets/pdfs/X_2005_MP_Maths_2_e.pdf){ target=_blank }
- Décomposition polaire et applications. [**Centrale 2013 MP Maths**](../assets/pdfs/Centrale_2013_MP_Maths_2_e.pdf){ target=_blank }
- Matrices symétriques positives, ordre de Löwner, fonctions matriciellement croissantes. [**Mines-Ponts 2006 PSI**](../assets/pdfs/Mines-Ponts_2006_PSI_Maths_2_e.pdf){ target=_blank }
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
