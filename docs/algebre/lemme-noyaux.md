# Lemme des noyaux

On considère un espace vectoriel \(E\) sur un corps commutatif \(K\) et un endomorphisme \(u \in \mathcal{L}(E)\).

---

## Énoncé

!!! theorem "Lemme des noyaux"
    Soient \(s \in \mathbb{N}^*\) et \(Q_1, \dots, Q_s \in K[X]\) des polynômes deux à deux premiers entre eux.  
    Alors :
    $$
    \ker\!\big[(Q_1 \cdots Q_s)(u)\big] = \bigoplus_{i=1}^s \ker\!\big(Q_i(u)\big).
    $$
    De plus, chacun des projecteurs associés à cette décomposition en somme directe est la **restriction à**  
    \(\ker\!\big[(Q_1\cdots Q_s)(u)\big]\) d’un **polynôme en \(u\)**.

---

## Preuve (esquisse)

### 1. Bézout sur les produits partiels

Pour \(k \in \{1, \dots, s\}\), on pose :
$$
R_k = \prod_{\substack{1 \le i \le s \\ i \ne k}} Q_i.
$$

Les \(R_1, \dots, R_s\) sont premiers entre eux.  
Par le théorème de Bézout, il existe \(V_1, \dots, V_s \in K[X]\) tels que :
$$
V_1 R_1 + \cdots + V_s R_s = 1.
$$

---

### 2. Surjectivité vers la somme des noyaux

Pour tout \(x \in \ker[(Q_1 \cdots Q_s)(u)]\), posons :
$$
x_i = \big[(V_i R_i)(u)\big](x), \quad \text{et} \quad x = \sum_{i=1}^s x_i.
$$

Alors :
$$
Q_i(u)(x_i) = 0 \quad \Rightarrow \quad x_i \in \ker(Q_i(u)).
$$

Ainsi :
$$
\ker[(Q_1 \cdots Q_s)(u)] = \sum_{i=1}^s \ker(Q_i(u)).
$$

---

### 3. Somme directe

Si \((x_1, \dots, x_s) \in \prod_i \ker(Q_i(u))\) et \(\sum_i x_i = 0\),  
alors, d’après l’identité de Bézout :
$$
x_i = \big[(V_i R_i)(u)\big]\!\Big(\sum_{j=1}^s x_j\Big) = 0.
$$
La somme est donc directe :
$$
\ker[(Q_1 \cdots Q_s)(u)] = \bigoplus_{i=1}^s \ker(Q_i(u)).
$$

---

### 4. Projecteurs polynomiaux en \(u\)

Les projecteurs associés s’écrivent comme :
$$
p_i = (V_i R_i)(u) \big|_{\ker[(Q_1 \cdots Q_s)(u)]},
$$
ce sont donc des **polynômes en \(u\)**.

---

## Application : décomposition de Dunford (rappel)

Supposons que \(E\) soit de dimension finie et que le polynôme caractéristique de \(u\) soit scindé sur \(K\).  
Alors il existe un **unique couple** \((d, n) \in \mathcal{L}(E)^2\) tel que :

1. \(d\) est diagonalisable ;  
2. \(n\) est nilpotent ;  
3. \(d\) et \(n\) commutent ;  
4. \(d, n \in K[u]\).

---

### Idée de preuve

D’après Cayley–Hamilton et le lemme des noyaux, il existe des valeurs propres distinctes  
\(\lambda_1, \dots, \lambda_s \in K\) et des entiers \(m_1, \dots, m_s \ge 1\) tels que :
$$
E = \bigoplus_{i=1}^s \ker\big((u - \lambda_i \operatorname{Id}_E)^{m_i}\big),
$$
avec des projecteurs \(p_i : E \to E\) polynomiaux en \(u\).

En posant :
$$
d = \sum_{i=1}^s \lambda_i p_i, \qquad n = u - d,
$$
on obtient la **décomposition de Dunford**.  
L’unicité et les détails figurent dans *Gourdon, Algèbre*, chap. 4, §4.2.
