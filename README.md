# Stiefel and Grassmann manifolds

My LaTeX paper draft on orthonormal frames and basis-independent subspaces, supervised by Professor Ed Segal at UCL. The source develops the geometric setting for constrained optimisation and outlines an application to PCA.

`paper/main.tex` contains the draft; `paper/refs.bib` contains its references. Later theorem statements and proofs remain placeholders, as do the abstract and concluding sections. There is no ML implementation or numerical experiment in this repository.

## Build the draft

Requires a TeX distribution with the packages listed in `main.tex`, plus BibTeX and `latexmk`. From this folder:

```sh
cd paper
latexmk -pdf main.tex
```

This produces `paper/main.pdf`. No GitHub Actions workflow is included, so the PDF is not built automatically. The draft compiled to a 15-page PDF on a disposable copy during this review. That checks the build, not the mathematical arguments.

The draft shows the scope of my mathematical study. It does not establish completed proofs or an implemented manifold optimiser.
