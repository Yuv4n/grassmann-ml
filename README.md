# Stiefel and Grassmann manifolds

An expository mathematics paper on orthonormal frames and subspaces, supervised by Dr Ed Segal at UCL, with the groundwork for an orthogonal recurrent neural network.

- **Content:** proofs of the manifold constructions and the quotient `St(n,k)/O(k) ≅ Gr(k,n)`; the Stiefel tangent projection and Riemannian gradient under the Frobenius metric; a verified polar retraction.
- **Sources:** follows Segal's notes and Boumal's treatment of Riemannian optimisation.
- **Talk:** presented at the UCL Undergraduate Mathematics Colloquium on 28 October 2026.

**Read:** [paper (PDF)](paper/main.pdf) · [LaTeX source](paper/main.tex) · [bibliography](paper/refs.bib)

To rebuild: `cd paper && latexmk -pdf main.tex` (needs a TeX distribution).

## Next

A NumPy project on orthogonal RNNs using a Cayley retraction and backpropagation through time, comparing hard orthogonality constraints with soft penalties across seeds. This repository currently contains the paper only: no ML implementation or experiments.
