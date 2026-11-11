# No External Dimensional Scale at the Level of Admissibility (no-scale)

This repository contains the LaTeX source of the Cosmochrony structural note
*No External Dimensional Scale at the Level of Admissibility*.

## Status (version 2.0)

Version 1 claimed a **Level 1 rigidity theorem**: no dimensional parameter independent of the Born–Infeld
constant \(c_{\mathrm{BI}}\) can enter the admissibility constraints, with a corollary excluding
Reissner–Nordström and Schwarzschild–de Sitter exteriors. **Version 2.0 withdraws that theorem, its corollary
and that application.** Three things are kept apart:

- **The proof is invalid.** It rested on premises that the cited papers do not contain: a power law for the
  pair capacity \(\sigma_{\mathrm{pair}}\) (O24 states none), a continuum limit (Q5a proves convergence to the zero
  form and leaves the spatial limit open), a fibre-weight requirement (ENI states none), and axioms A3/A4 of
  Foundation fixing a unique primitive scale (A3 is non-premature selection, A4 projection locking). Each of its
  three cases also has internal gaps.
- **The claim is withdrawn.**
- **The question is open.** The failure of the proof does not show that every Level 1 property is false.

## What the note keeps

- **The dimension of \(c_{\mathrm{BI}}\) is not fixed by the model.** In the capacity axiom
  \(|\partial_\tau\phi_v|\le c_{\mathrm{BI}}\), neither the relational configuration \(\phi\) nor the ordering
  parameter \(\tau\) carries a physical dimension; in the mode-amplitude bound
  \(A_n\le c_{\mathrm{BI}}/\sqrt{\lambda_n}\), a hypothesis of O20, \(\lambda_n\) is a graph-Laplacian
  eigenvalue. The note records this gap and does not choose a dimension.
- **Independent dimensional parameters are defined relative to a supplied dimensional assignment.** Under any
  assignment giving \(c_{\mathrm{BI}}\) a single dimension, \(G\), \(\hbar\) and mass scales cannot all be
  reduced to it.
- **A dimensional-homogeneity observation on the bound.** Under such an assignment, a constant factor
  depending only on a parameter whose dimension lies outside the span of the bound's ingredients is constant,
  and a dimensionless factor rescales \(c_{\mathrm{BI}}\mapsto c_{\mathrm{BI}}f(\lambda)\). Dimensional
  parameters entering through \(n\)-dependent combinations are not excluded.
- **The Level 1 / Level 2 distinction.** Level 2 (functional determination of every scale) is stronger; both
  are open.
- The Gram rigidity classification is character-theoretic and scale-free; version 1's statement that it is
  derived under the Born–Infeld bound is withdrawn.

*Interpretation (a reading, not a result).* The programme's working reading is that physical scales arise as
outputs of the projection rather than as primitive inputs. The note does not establish it, and the geometric
sector already carries scales not derived from \(c_{\mathrm{BI}}\) (Q6b).

## Build

```bash
bash compile.sh
```

The PDF is written to `out/no-scale.pdf`.

## Keywords

admissibility; dimensional analysis; dimensional homogeneity; Born–Infeld bound; non-injective projection; scale
rigidity; open problem; emergent physics

## Citation

```bibtex
@misc{Beau2026j,
  author = {Beau, J.},
  title  = {{No External Dimensional Scale at the Level of Admissibility}},
  year   = {2026},
  doi    = {10.5281/zenodo.19744767}
}
```

## License

CC-BY-4.0.
