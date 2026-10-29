# Stiefel and Grassmann manifolds

An expository mathematics paper on orthonormal frames and subspaces, supervised by Professor Ed Segal at UCL. The paper develops the geometry of Stiefel and Grassmann manifolds and establishes their relationship through the column-space map.

The complete manuscript includes proofs of the manifold constructions and the quotient identification `St(n,k)/O(k) ≅ Gr(k,n)`. It also derives the Stiefel tangent projection and Riemannian gradient under the Frobenius metric, and verifies a polar retraction. The exposition follows Segal’s notes, supplemented by Boumal’s treatment of Riemannian optimisation.

The paper supported a presentation at the UCL Undergraduate Mathematics Colloquium on 28 October 2026 and provides a mathematical foundation for a planned NumPy project on orthogonal recurrent neural networks. That project will use a Cayley retraction and backpropagation through time, and compare hard orthogonality constraints with soft penalties across multiple random seeds. The paper proves the polar-retraction construction; the Cayley method and experiments are subsequent work. This repository currently contains the paper, with no ML implementation or numerical experiments.

## Paper

- [Compiled PDF](paper/main.pdf)
- [LaTeX source](paper/main.tex)
- [Bibliography](paper/refs.bib)

## Build

Requires a TeX distribution with the packages listed in `paper/main.tex`, plus BibTeX and `latexmk`. From the repository root:

```sh
cd paper
latexmk -pdf main.tex
```

This regenerates `paper/main.pdf`.
