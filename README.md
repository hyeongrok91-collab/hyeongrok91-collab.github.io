# Hyeong Rok Lee — AI Theory & Mathematical Foundations

Research papers on the geometry and information theory of neural architectures.

## Papers

### Paper B — Flagship
**The Information Theory of AI Architectures: Effective Computational Capacity and Intelligence Decomposition**
- We define **Effective Computational Capacity (ECC)** as the generic Jacobian rank and prove it is the *unique* capacity measure satisfying three axioms.
- Intelligence = ECC × τ_rep × τ_stat × τ_opt
- Corrected ECC formulas: `ECC_Attn = H[d_h(2d−d_h) + d_v(2d−d_v)]`, `ECC_FFN = m(2d−1)`
- 📄 [PDF](https://hyeongrok91-collab.github.io/paper_b.pdf) · 📖 [Full Text (HTML)](https://hyeongrok91-collab.github.io/paper_b.html) · 🔗 [DOI: 10.5281/zenodo.18865785](https://doi.org/10.5281/zenodo.18865785)

### Paper A — Foundation
**The d² Pullback Theorem: Why Attention is a d²-Dimensional Problem**
- The gradient w.r.t. score kernel M is *exactly* the sandwich transform `X^T G(M) X / √d`
- Exact Jacobian rank: `r(r − ε_X)`, generically `d²`
- Same-depth softmax → positive polynomial replacement (unconditional)
- No-go theorem for universal fixed-width degree-2 simulation
- 📄 [PDF](https://hyeongrok91-collab.github.io/paper_a.pdf) · 📖 [Full Text (HTML)](https://hyeongrok91-collab.github.io/paper_a.html) · 🔗 [DOI: 10.5281/zenodo.18842724](https://doi.org/10.5281/zenodo.18842724)

## Keywords
Effective Computational Capacity · Intelligence Decomposition · Jacobian Rank · Pullback Theorem · Attention Geometry · Transformer Architecture · Polynomial Attention · Information Theory · Scaling Laws · Neural Architecture Theory

## License
© 2026 Hyeong Rok Lee. All rights reserved.
