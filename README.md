This repository contains the source of the **Gauge Structure Presentation Note** Cosmochrony paper
*The Gauge Structure Sub-Programme — Presentation Note 3*.

This work is a **structured entry point** to the gauge structure sub-programme of the
Cosmochrony corpus, not a summary of results. It maps the constituent papers, records the status
of every result as proved, conditional, structural, numerical, open, or withdrawn, and states the
remaining open deliverables.

## Central Question

The non-injective projection $\Pi: \chi \to O$ selects admissible configurations from the
relational substrate; its fibre $\Pi^{-1}(O_n)$ carries internal structure.

> Which internal symmetry groups are preserved as invariants of admissible projection?

Define $G_\Pi$ as the group of fibre symmetries of $\Pi$ that preserve the admissibility
constraints. **The sub-programme does not establish $G_\Pi$.** The derivation of
$G_\Pi = \mathrm{SU}(3) \times \mathrm{SU}(2) \times \mathrm{U}(1)$ is withdrawn at its source, and
no replacement is available. This note records what the question has and has not established.

## What the withdrawal removes

O31 is a withdrawal notice. It withdraws every derivation of a gauge factor and of the Standard
Model gauge group as a composite, together with the determinant-one condition, the commutation
of the putative factors and the direct-product structure. It also withdraws the uniqueness of
$\mathrm{SU}(3)$ among connected compact subgroups acting irreducibly on $\mathbb{C}^3$, the
irreducibility of the admissible transformation group, the co-admissibility of the individual
profiles, the arithmetic criterion, the metaplectic identity as used, the $\Delta(27)$ spectral
proposition, and a mistyped rank test.

Three counterexamples make this unavoidable rather than cautionary:

- $\mathrm{SO}(3) \subset \mathrm{SU}(3)$ is a proper connected compact subgroup acting
  irreducibly on $\mathbb{C}^3$ with determinant one, so those two conditions never single out
  $\mathrm{SU}(3)$;
- the diagonal torus $T^2 \subset \mathrm{SU}(3)$ satisfies every constraint that was imposed
  while acting reducibly;
- $\{1, 2, q-3\}$ is an admissible colour triplet for every prime $q \geq 7$, so triplets do not
  require $q \equiv 1 \pmod 3$.

## What remains

$\Pi \simeq S^3
\;\Longrightarrow\;
S^1 \hookrightarrow S^3 \to S^2
\;\Longrightarrow\;
\mathrm{U}(1)
\qquad\text{and}\qquad
\mathfrak{su}(2) \text{ from } \operatorname{Im}\mathbb{H}
\;\Longrightarrow\;
\mathrm{SU}(2)\ \text{(conditional)}.$

1. **$\mathrm{U}(1)$ from the Hopf phase fibre** — the projection fibre $\Pi \simeq S^3$
   carries a canonical Hopf fibration $S^1 \hookrightarrow S^3 \to S^2$; the circle fibre
   supports a $\mathrm{U}(1)$ phase symmetry whose winding number $w \in \pi_1(S^1) \cong \mathbb{Z}$
   is the topological origin of electric charge (TopInv, Proposition 3.1, which does not invoke the
   canonical admissible model). Two premises there are structural inputs rather than results: the
   identification of the fibre with $S^3$, imported from the white paper, and the identification of
   the $S^1$ phase with electric charge. The sector is
   argued in the topological layer rather than in O31, so neither withdrawal reaches it — which is a
   statement about independence from the withdrawals, not about its premises being derived.
2. **$\mathrm{SU}(2)$, conditional on a supplied carrier** — the admissible sector is
   $V_\rho \cong \mathbb{C}^2$, a supplied input; O23 (Theorem 3.1) proves that its traceless
   sector is $\mathfrak{su}(2) \cong \operatorname{Im}\mathbb{H}$, of real dimension three. O27
   gives unique real-linear factorisation through the admissibility quotient and a one-dimensional
   **complex** intertwiner space; identifying that quotient with $\mathfrak{su}(2)$ is supplied by
   O23 and rests, in O27, on its admissible-saturation hypothesis, not derived. O27 carries a second
   hypothesis, parity transport, for the involution's descent. The vector lift into $V_\rho$ is
   open.
3. **$\mathrm{SU}(3)$ — withdrawn.** No route is available.

There is no composite. Even granting $\mathrm{U}(1)$ and a conditional $\mathrm{SU}(2)$, nothing
establishes that they are factors of a single group, that they commute, or that the structure is a
direct product.

## Position in the Programme

The sub-programme sits at the intersection of Branch I (axiomatic primitive and fibre
structure) and Branch II (spectral admissibility). It takes from Presentation Note 1
(spectral admissibility) the spin-$\tfrac12$ admissible sector $V_\rho \cong \mathbb{C}^2$
(a supplied input), the threshold $\Sigma_c(n_3) = 3$ (a supplied selection rule, O23), and
$\operatorname{Im}\mathbb{H} \cong \mathfrak{su}(2)$. It takes no $\mathrm{SU}(3)$ input.
It takes from Presentation Note 2 (emergent geometry) the effective projection space
$H_{\mathrm{eff}}$, identified with $\mathrm{Sym}^2(V_\rho)$ by a supplied hypothesis, and the effective base manifold
$\mathbb{R}_\tau \times \mathrm{Heis}_3(\mathbb{R})$, with no metric coefficient: Q5b gives,
under the unestablished [H-L] and the open [H-lift], a rank-three co-metric with no coefficient
values, and Q11 a rank-four form only for a supplied extension with independent temporal and
spatial scales. The closure $g^{\mu\nu} = 2\eta^{\mu\nu}$ is not established. The admissible
principal bundle $P_{G_\Pi}(M, G_\Pi)$ is defined in Q12 for a supplied compact $G_\Pi$; Q6a reads
the connection as the generator of fibre transport, conditionally on two continuum hypotheses.

Downstream, Q12, Q13 and Note 8 carry $G_\Pi$ as a supplied compact group, and their results hold
for every such group; Q14 carries its colour module as an explicit hypothesis. None of them takes
$G_\Pi$ as a derived input, so their results concern a supplied group, not an identified Standard
Model group.

## Constituent Papers

| Sector | Papers | Central output | Status |
|---|---|---|---|
| $\mathrm{U}(1)$ fibre | TopInv | Charge $= w \cdot e$, on imported inputs | S |
| Monopole exclusion | TopInv | $\pi_2(\mathcal{C}_{\mathrm{adm}}) = 0$, canonical model | P |
| $\mathrm{U}(1)$ phase | Q6a | Global phase rotations, unresolved by span-based observables | S |
| $\mathrm{SU}(2)$ sector | O23, O27, Q6a, Q7 | Quotient factorisation; $\mathfrak{su}(2)$ supplied | C |
| Charges | Q6a, TopInv | Fibre-invariant charges | S |
| Bundle | Q12, Q6a | Supplied compact $G_\Pi$; transport | S, C |
| $\mathrm{SU}(3)$, either graph | O31 | Triplet co-admissibility route | W |
| Triplet variance ratios | O32 | $R_{\mathrm{var}}$ at the noise floor | N |
| $G_\Pi$ as a composite | O31 | Direct-product structure | W |

Status codes: **P** = proved, **S** = structural, **N** = numerical, **C** = conditional,
**O** = open, **W** = withdrawn at the source.

## Open Deliverables

1. **A route to $\mathrm{SU}(3)$.** The colour-triplet route is refuted by counterexample, not
   merely left incomplete. A replacement must single out $\mathrm{SU}(3)$ by an argument that
   excludes its subgroups, which irreducibility and determinant one demonstrably do not.
2. **A route to a composite gauge group.** Granting $\mathrm{U}(1)$ and a conditional
   $\mathrm{SU}(2)$, nothing establishes a single group, commuting factors, or a direct product.
3. **$\pi_2(\mathcal{C}_{\mathrm{eff}}) = 0$ in general.** The topological exclusion of
   magnetic monopoles is proved on the canonical admissible model; extension to the full
   effective configuration space is a well-posed open problem in homotopy theory.
4. **$V - A$ maximality from admissibility.** The structural mechanism for projective
   chirality is identified; its derivation of the specific $V - A$ form of the weak
   interaction current from admissibility data is an open analytical problem.

## Citation

If you reference this work, please cite the Zenodo concept DOI, which always resolves to the
latest version:

J. Beau: *The Gauge Structure Sub-Programme — Presentation Note 3*, Zenodo, 2026,
[10.5281/zenodo.20435029](https://doi.org/10.5281/zenodo.20435029).

## Build

```bash
bash compile.sh
```

This runs `pdflatex → bibtex → pdflatex → pdflatex` on `tex/GaugeStructureNote.tex` and
produces `out/GaugeStructureNote.pdf`.
