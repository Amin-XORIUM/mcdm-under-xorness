# Multiple Criteria Decision Making (MCDM) Under Xorness

Reference implementation and materials for the **XOR-Weighted Sum Method (XOR-WSM)**,
a multi-criteria decision-making (MCDM) framework that preserves **Xorness** throughout
the entire decision process.

> **Xorness** is a class of uncertainty arising from *indeterminacy, exclusivity, and
> hesitancy*. An **XOR number** is a finite set of distinct real values connected by an
> exclusive-or (XOR) relation, where exactly one value is the true value but its identity
> remains indeterminate.

## 📄 Paper

**Multiple Criteria Decision Making Under Xorness**
Amin Hocine · *under review at Omega*

If you use this work, please cite it (see [`CITATION.cff`](CITATION.cff)).

## ✨ What this method does

The XOR-WSM operates within an *[XOR-valued input → XOR-valued output]* decision system.
Unlike earlier XOR methods that collapse XOR numbers into deterministic values, XOR-WSM
preserves Xorness across every stage:

1. **XOR-decision matrix** — evaluations expressed as XOR numbers
2. **Normalization** — element-wise, preserving XOR structure
3. **Weighting** — scalar multiplication over XOR numbers
4. **XOR-aggregation** — additive operator producing a global XOR-performance score
5. **Xorness measure** — quantifies indeterminacy, exclusivity, and hesitancy
6. **Performance–Xorness (PXness) index** — ranks alternatives via a total preorder

## 🧩 Core concepts

- **XOR numbers** and their arithmetic operations (⊕, ⊖, ⊗, ⊘)
- **Xorness measure** — an axiomatic measure of uncertainty
- **PXness index** — trade-off between performance and Xorness via parameter γ ∈ [0,1]

## 🔬 Case study

The framework is demonstrated on a **cybersecurity risk assessment** of five cyberthreat
scenarios in energy systems: ransomware, coordinated attacks, malware injection, insider
attacks, and IoT exploitation.

## 🔗 Related methods in the Xorness family

`XOR-AHP` · `XOR-ANP` · `XOR-DEA` · `XOR-BWM` · `XOR-WSM`

## 📫 Contact

Amin Hocine, PhD — University of Bergamo · [xorium.org](https://xorium.org) ·
amin.hocine@unibg.it
