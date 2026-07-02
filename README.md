# Point Cloud Invariants — degree bounds for separating invariants

A self-contained walkthrough and audit of Harm Derksen's note *Point Cloud Invariants* (v2):

- **Lower bound** (graphs, S_n on symmetric matrices): β_sep ≥ (¼−o(1))·n², via Molien's
  formula, the universal denominator, an equivariant-Koszul proof of the key divisibility,
  and a cyclotomic factor.
- **Upper bounds**: separation in degree ~n⁴/2 by Lagrange interpolation, improved to
  ~n⁴/8 via Göbel's bound (with a corrected constant).
- **Point clouds** (O(d)×S_n on d×n matrices): the Gram-map reduction, a proved ~n⁴/4
  bound, and a documented fatal gap in the note's claimed O(d²n²) bound.
- **Audit**: all five mathematical issues found in the note, with severities and repairs,
  plus improvement directions.

**Live site:** https://snirhordan.github.io/point-cloud-invariants/

Pages: Overview · Background · Machinery · Lower Bound · Upper Bound · Point Clouds · Audit · Significance.
