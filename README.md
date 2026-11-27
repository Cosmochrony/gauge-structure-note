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

Let $\mathcal{G}_\Pi$ be the group of automorphisms that preserve $\Pi$, each mapping every fibre to
itself (ENI, Definition 3; the group $\mathcal{G}$ of Q6a), the automorphisms being taken
in the category whose morphisms also preserve the admissibility constraints. Whether the admissibility structure identifies a structure group
$G_\Pi = \mathrm{SU}(3) \times \mathrm{SU}(2) \times \mathrm{U}(1)$ is open: **the sub-programme does not
establish it.** The derivation of that identification is withdrawn at its source, and no
replacement is available. Throughout, $G_\Pi$ follows the convention of Q12: it denotes the
supplied structure group of a gauge structure in the physical sense. It is not $\mathcal{G}_\Pi$,
and it does not denote the group $G_\Pi$ acting effectively within $\mathcal{G}_\Pi$ of ENI's
Definition 3 (ENI, Remark 4).

Non-trivial minimal gauge freedom in ENI's sense (Definition 3) requires the non-injectivity of $\Pi$ (ENI,
Proposition 4); conversely, for a non-injective $\Pi$, a non-trivial minimal gauge structure exists exactly when
$\mathcal{G}_\Pi \neq \{e\}$ (ENI, Remark 4). On the
supplied complex carrier, the global phase rotations belong to $\mathcal{G}_\Pi$ to the extent that
$\Pi_n$ is defined through span-based observables (Q6a). Gauge structure in the physical sense
(structure group, principal bundle, connection and its dynamics) remains supplied. This note records what the question has and has not established.

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
   supports a $\mathrm{U}(1)$ phase symmetry with an integer winding number
   $w \in \pi_1(S^1) \cong \mathbb{Z}$ (TopInv, Proposition 3.1). The winding is invariant for
   configurations in a fixed fibre or over a trivialising domain of the base, not in the whole fibre
   $S^3$, so a chosen domain and its trivialisation enter this result too. The identification of the
   fibre with $S^3$, imported from the white paper, is a structural input; the identification of the
   winding with electric charge is not derived, since no relation between the internal fibre and an
   emergent electromagnetic potential is supplied, and charge quantisation is open. The sector is
   argued in the topological layer rather than in O31, so the O31 withdrawal notice does not reach it —
   which is a statement about independence from O31, not about its premises being derived.
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
principal bundle $P_{G_\Pi}(M, G_\Pi)$ is defined in Q12 for a supplied compact $G_\Pi$; Q6a's two
continuum hypotheses do not determine a connection, so the connection is supplied and read as the
generator of parallel transport on those data.

Downstream, Q12, Q13 and Note 8 carry $G_\Pi$ as a supplied compact group, and their results hold
for every such group; Q14 carries its colour module as an explicit hypothesis. None of them takes
$G_\Pi$ as a derived input, so their results concern a supplied group, not an identified Standard
Model group.

## Constituent Papers

| Sector | Papers | Central output | Status |
|---|---|---|---|
| $\mathrm{U}(1)$ fibre | TopInv | Integer fibre winding, on imported inputs | S |
| Charge from winding | TopInv | $q_{\mathrm{eff}} = w \cdot e$ not derived | O |
| Monopoles | TopInv | $\pi_2 = 0$ on a chosen domain; no exclusion derived | O |
| $\mathrm{U}(1)$ phase | Q6a | Global phase rotations, unresolved by span-based observables | S |
| $\mathrm{SU}(2)$ sector | O23, O27, Q6a, Q7 | Quotient factorisation; $\mathfrak{su}(2)$ supplied | C |
| Charges | Q6a | Fibre-invariant charges | S |
| Bundle | Q12, Q6a | Supplied compact $G_\Pi$ and connection | S, C |
| $\mathrm{SU}(3)$, either graph | O31 | Triplet co-admissibility route | W |
| Triplet variance ratios | O32 | diagnostic proved colour-blind (unit-scaling invariance) | P |
| $G_\Pi$ as a composite | O31 | Direct-product structure | W |

Status codes: **P** = proved, **S** = structural, **N** = numerical, **C** = conditional,
**O** = open, **W** = withdrawn at the source.

## Open Deliverables

1. **A route to $\mathrm{SU}(3)$.** The colour-triplet route is refuted by counterexample, not
   merely left incomplete. A replacement must single out $\mathrm{SU}(3)$ by an argument that
   excludes its subgroups, which irreducibility and determinant one demonstrably do not.
2. **A route to a composite gauge group.** Granting $\mathrm{U}(1)$ and a conditional
   $\mathrm{SU}(2)$, nothing establishes a single group, commuting factors, or a direct product.
3. **The winding as electric charge.** A specified relation between the internal fibre and an
   electromagnetic potential of the emergent description, which $q_{\mathrm{eff}} = w \cdot e$
   requires, is not supplied; charge quantisation in the emergent description is open.
4. **$\pi_2(\mathcal{C}_{\mathrm{eff}}) = 0$ in general.** The triviality of $\pi_2$ is proved
   for a chosen domain of the Hopf base, and no topological exclusion of magnetic monopoles is
   derived. Deriving the admissible base from the projection structure, and determining whether
   $\pi_2$ of the Hopf base bears on magnetic defects at all, are open problems.
5. **$V - A$ maximality from admissibility.** The structural mechanism for projective
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
