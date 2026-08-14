This repository contains the source of the **Gauge Structure Presentation Note** Cosmochrony paper
*The Gauge Structure Sub-Programme — Presentation Note 3*.

This work is a **structured entry point** to the gauge structure sub-programme of the
Cosmochrony corpus, not a summary of results. It maps the constituent papers, identifies
the internal phases, records the status of every result as proved, structural, numerical,
or open, and states the remaining open deliverables.

## Central Question

The non-injective projection $\Pi: \chi \to O$ selects admissible configurations from the
relational substrate; its fibre $\Pi^{-1}(O_n)$ carries internal structure.

> Which internal symmetry groups are preserved as invariants of admissible projection, and
> why are they precisely $\mathrm{U}(1)$, $\mathrm{SU}(2)$, and $\mathrm{SU}(3)$?

Define $G_\Pi$ as the group of fibre symmetries of $\Pi$ that preserve the admissibility
constraints. The sub-programme establishes $G_\Pi = \mathrm{SU}(3) \times \mathrm{SU}(2) \times \mathrm{U}(1)$:
the gauge group of the Standard Model is a **forced output** of the admissibility structure,
not a postulate. This note concerns the **identification** of $G_\Pi$ only; the derivation
of Yang–Mills dynamics belongs to the gauge–gravity spectral stratification sub-programme
(Presentation Note 8).

## Logical Chain

$\Pi \simeq S^3
\;\Longrightarrow\;
S^1 \hookrightarrow S^3 \to S^2
\;\Longrightarrow\;
\mathrm{U}(1)
\;\Longrightarrow\;
\mathfrak{su}(2) \text{ from } \operatorname{Im}\mathbb{H}
\;\Longrightarrow\;
\mathrm{SU}(2)
\;\Longrightarrow\;
\mathrm{SU}(3).$

Three factors arise from distinct structural mechanisms:

1. **$\mathrm{U}(1)$ from the Hopf phase fibre** — the projection fibre $\Pi \simeq S^3$
   carries a canonical Hopf fibration $S^1 \hookrightarrow S^3 \to S^2$; the circle fibre
   supports a $\mathrm{U}(1)$ phase symmetry whose winding number $w \in \pi_1(S^1) \cong \mathbb{Z}$
   is the topological origin of electric charge.
2. **$\mathrm{SU}(2)$ from the supplied spinor carrier** — the admissible sector is
   $V_\rho \cong \mathbb{C}^2$, a supplied input; O23 (Theorem 3.1) proves that its traceless
   sector is $\mathfrak{su}(2) \cong \operatorname{Im}\mathbb{H}$, of real dimension three,
   conditional on that carrier, and the quaternionic rigidity
   theorem (O27) forces every admissible morphism to factor through $\mathfrak{su}(2)$.
3. **$\mathrm{SU}(3)$ from colour-triplet co-admissibility** — metaplectic intertwining of
   $\mathrm{Heis}_3(\mathbb{Z}/q\mathbb{Z})$ forces unconditional triplet co-admissibility
   on the colour-adapted Cayley graph (O31); the standard graph is established at the rank,
   averaged, effective-exponent, and numerical levels (O31–O32).

## Position in the Programme

The sub-programme sits at the intersection of Branch I (axiomatic primitive and fibre
structure) and Branch II (spectral admissibility). It takes from Presentation Note 1
(spectral admissibility) the spin-$\tfrac12$ admissible sector $V_\rho \cong \mathbb{C}^2$
(a supplied input), the threshold $\Sigma_c(n_3) = 3$ (a supplied selection rule, O23), and
$\operatorname{Im}\mathbb{H} \cong \mathfrak{su}(2)$.
It takes from Presentation Note 2 (emergent geometry) the effective projection space
$H_{\mathrm{eff}} = \mathrm{Sym}^2(V_\rho)$, the effective base manifold
$\mathbb{R}_\tau \times \mathrm{Heis}_3(\mathbb{R})$, and the admissible principal bundle
$P_{G_\Pi}(M, G_\Pi)$. It produces the gauge group $G_\Pi$ and the admissible principal
bundle used downstream by Q12, Q13, Q14, and Note 8.

## Constituent Papers

The note organises the constituent papers by sector:

| Sector | Papers | Central output | Status |
|---|---|---|---|
| $\mathrm{U}(1)$ fibre | Foundation, TopInv, SMchargemass | Charge $= w \cdot e$; no monopoles | P (canonical) |
| $\mathrm{U}(1)$ bundle | Q6a, Q12 | Admissible $\mathrm{U}(1)$ connection | S |
| $\mathrm{SU}(2)$ sector | O23, O27–O30, Q6a, Q7 | $d_\rho = 2$ supplied; $\mathfrak{su}(2)$ conditional on the carrier | S |
| Charges | Q6a, TopInv, Q12 | Bundle structure; holonomy charges | S |
| $\mathrm{SU}(3)$ adapted | O31 | Triplet co-admissibility | P |
| $\mathrm{SU}(3)$ standard | O31–O32 | $[\mathrm{H\text{-}color}]_{\mathrm{rank/avg/eff}}$ | P/S |
| $[\mathrm{H\text{-}color}]_{\mathrm{pointwise}}$ | O32 | Finite-$q$ profile equality | O |

Status codes: **P** = proved, **S** = structural, **N** = numerical, **O** = open.

## Open Deliverables

1. **$[\mathrm{H\text{-}color}]_{\mathrm{pointwise}}$.** The $\mathrm{SU}(3)$ identification
   on the standard graph is established at the rank, averaged, effective-exponent, and
   numerical levels. Exact finite-$q$ profile equality remains analytically open; the
   spectral route is closed (O31), so the correct mechanism must act at the level of the
   BFS rank structure.
2. **$\pi_2(\mathcal{C}_{\mathrm{eff}}) = 0$ in general.** The topological exclusion of
   magnetic monopoles is proved on the canonical admissible model; extension to the full
   effective configuration space is a well-posed open problem in homotopy theory.
3. **$V - A$ maximality from admissibility.** The structural mechanism for projective
   chirality is identified; its derivation of the specific $V - A$ form of the weak
   interaction current from admissibility data is an open analytical problem.

## Build

```bash
bash compile.sh
```

This runs `pdflatex → bibtex → pdflatex → pdflatex` on `tex/GaugeStructureNote.tex` and
produces `out/GaugeStructureNote.pdf`.
