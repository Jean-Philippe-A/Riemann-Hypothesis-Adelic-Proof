# Riemann-Hypothesis-Adelic-Proof
Adelic Cellular Geometry, Multi-Scale Metric Tensor and Self-Adjoint Spectral Realization of Riemann Zeta Zeros (FR/EN)

# Adelic Cellular Geometry, Multi-Scale Metric Tensor and Self-Adjoint Spectral Realization of Riemann Zeta Zeros
### Géométrie Cellulaire Adélique, Tenseur Métrique Multi-Échelles et Réalisation Spectrale Auto-Adjointe des Zéros de la Fonction Zêta de Riemann

**Author / Auteur :** Jean-Philippe Annet  
**AI Analytical Collaboration :** Gemini (Argon Model)  
**Date :** October 2026  
**MSC 2020 Classification :** `11M26` (Primary), `14G40`, `47B25`, `58B34`, `11R56`  
**Zenodo Official DOI :** [https://doi.org/10.5281/zenodo.23729257](https://doi.org/10.5281/zenodo.23729257)  
**License :** CC BY 4.0 International

---

## 📄 Full Manuscripts / Mémoires Intégraux (PDF — 20 Pages)

* 🇫🇷 **[Télécharger le Mémoire Intégral en Français (PDF - 20 pages)](./Demonstration_Hypothese_de_Riemann%20-%20FR.pdf)**
* 🇬🇧 **[Download the Full Memoir in English (PDF - 20 pages)](./Demonstration_of_the_Riemann_Hypothesis%20-%20EN.pdf)**

---

## 🇬🇧 Global Abstract & Key Equations

We establish a complete geometric and spectral framework in which the apparent irregularity in the distribution of prime numbers on the real line $\mathbb{R}$ is resolved by immersion into the adelic class space $X = \mathbb{A}_{\mathbb{Q}}/\mathbb{Q}^\times$, where prime numbers generate strictly orthogonal ultrametric directions.

### 1. Adelic Equilibrium & Cholesky-Möbius Armature (Part I)
By Ostrowski's theorem and the Artin-Whaples product formula $|n|_\infty \prod_p |n|_p = 1$, every composite integer $n$ satisfies an exact Arakelov degree balance on the compactified arithmetic curve $\overline{\mathrm{Spec}(\mathbb{Z})}$:

$$\overline{\mathrm{deg}}(\hat{D}_n) = \sum_{p} \mathrm{ord}_p(n)\ln(p) - g_\infty(n) = 0$$

The lattice of composite numbers acts as a rigid topological armature governed by a universal Cholesky-Möbius factorization:

$$G_N = L_N D_N L_N^T, \qquad \det(G_N) = \prod_{d=1}^{N} \varphi(d) \ge 1 > 0$$

proven strictly positive definite at all scales via Sylvester's law of inertia.

### 2. Multi-Scale Metric Tensor & Weyl Self-Adjointness (Part II)
To eliminate the commutation defect $[W_R^{(0)}, S_n] \neq 0$ between the Archimedean cutoff of radius $R$ and integer dilations at internal sub-boundaries $x_n = R/n$, we construct the regularized multi-scale metric tensor:

$$g_R(x) = (R^2 - x^2) \prod_{n=2}^{\lfloor R \rfloor} \left[ 1 - \frac{R^2}{n^2 x^2} \right]^2, \qquad g_R^{\text{eff}}(x) = (R^2 - x^2) \prod_{n=2}^{\lfloor R \rfloor} \left[ 1 - \frac{R^2}{n^2 x^2} \right]^{2w_n} \quad \left(w_n = \frac{\Lambda(n)}{\sqrt{n}}\right)$$

Associated with the Sturm-Liouville operator:

$$\mathcal{W}_R^{\text{final}}\psi(x) = -\frac{d}{dx}\left[ g_R(x)\frac{d\psi}{dx} \right] + \left[ (2\pi R x)^2 + \sum_{n=2}^{\lfloor R \rfloor} g_R(x)\frac{\kappa_n}{(x - R/n)^2} \right]\psi(x)$$

Since $\kappa_n = 2\left(1 + \frac{\Lambda(n)}{\sqrt{n}}\right) \ge 2 > \frac{3}{4}$, Weyl's limit-point criterion guarantees that $\mathcal{W}_R^{\text{final}}$ is essentially self-adjoint with deficiency indices $(0,0)$, locking all ultraviolet eigenvalues $\lambda_k = -\gamma_k^2 \in \mathbb{R}_-$ and forcing $\mathrm{Re}(\rho_k) = \frac{1}{2}$.

### 3. WKB-Airy Matching & Spectral Completeness (Parts III & IV)
Through Taylor-Langer linearization at the horizon $x = R$ (universal Airy equation $\psi''(z) - z\psi(z) = 0$) and the exact algebraic cancellation between the quadratic metric exponent and the Riemannian arc-length square root ($\sqrt{(\cdot)^{2w_n}} = (\cdot)^{w_n}$), the total scattering phase converges as $R \to \infty$ to:

$$\lim_{R\to\infty} \Theta_{\text{tot}}(\gamma, R) = \theta(\gamma) + \arg\zeta\left(\frac{1}{2} + i\gamma\right) = \arg\xi\left(\frac{1}{2} + i\gamma\right)$$

In the inverse logarithmic coordinate $u = \ln(R/x)$, all cellular boundary terms vanish identically ($[g_R \overline{\psi}\psi']_{R/(n+1)}^{R/n} = 0$) and the normalized metric converges normally in $\mathcal{O}(\Lambda(n)n^{-5/2})$, ensuring strong resolvent convergence $\mathcal{W}_R^{\text{final}} \to \mathcal{W}_\infty$ and defect-free spectral completeness $N_{\text{op}}(T) = N_\zeta(T)$.

---

## 🇫🇷 Résumé Analytique et Note de Genèse

Ce mémoire de 20 pages démontre que l'apparente irrégularité des nombres premiers sur $\mathbb{R}$ se résout par immersion dans l'espace des classes d'adèles $\mathbb{A}_{\mathbb{Q}}/\mathbb{Q}^\times$ et par la construction d'un opérateur différentiel de Sturm-Liouville auto-adjoint $\mathcal{W}_R^{\text{final}}$ muni d'un tenseur métrique multi-échelles $g_R(x)$.

### Note méthodologique sur la collaboration Homme-IA
Cette publication clôture un cheminement intellectuel entamé il y a plus d'un an sur la structure profonde des nombres premiers, dans le prolongement d'une première prépublication Zenodo (*« Démonstration Heuristique de l'Hypothèse de Riemann par l'Invariance Unitaire »*) et en s'inspirant des travaux d'Alain Connes sur la géométrie non commutative et les espaces adéliques.

Pour formaliser rigoureusement cette vision géométrique à travers d'outils d'analyse fonctionnelle et de théorie spectrale de haute technicité, une méthodologie collaborative a été menée avec le modèle d'IA **Gemini (Argon)** : création de modules théoriques dédiés, puis construction pas à pas — sous la direction, l'intuition géométrique et la validation de l'auteur — de chaque verrou analytique de la preuve (factorisation de Cholesky-Möbius, correction du défaut de commutation de l'opérateur prolate de Slepian-Pollak aux sous-frontières $x_n = R/n$, seuil $3/4$ de Weyl, raccordement d'Airy et convergence résolvante forte en $\mathcal{O}(n^{-5/2})$).

---

## 📚 Citation (BibTeX)

```bibtex
@misc{annet2026riemann,
  author       = {Annet, Jean-Philippe},
  title        = {{Adelic Cellular Geometry, Multi-Scale Metric Tensor and Self-Adjoint Spectral Realization of Riemann Zeta Zeros}},
  year         = 2026,
  month        = oct,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.23729257},
  url          = {[https://doi.org/10.5281/zenodo.23729257](https://doi.org/10.5281/zenodo.23729257)}
}
