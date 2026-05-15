# Kasner-singularity-of-black-holes-in-Einstein-scalar-gravity
Data and Mathematica notebooks for article 2602.22314
# Data and Code for "Kasner singularity of black holes in Einstein-scalar gravity"

## Article
- **Accession Code**:  2602.22314
- **Authors**: Ze-Xuan Xiong, Hong Lü

## Contents

| File | Description |
|:---|:---|
| `Numerical Solution.nb` | Mathematica solver for constructing scalar hairy black holes via the shooting method (Sec. IV–V) |
| `Results-Data.nb` | Compiled dataset of horizon parameters, Kasner exponents $(P_t, P_T, P_\phi)$, near-singularity parameter $\Xi$, mass $M$, scalar charge $\Sigma$, and thermodynamic quantities |
| `1a.nb` – `12a-12b.nb` | Mathematica notebooks generating Figs. 1–12 in the paper |

## Usage
All notebooks require **Wolfram Mathematica 13.0 or later**.  
- Run `Numerical Solution.nb` first to generate or reproduce the numerical black-hole solutions.  
- `Results-Data.nb` imports the output and organizes the tabulated data used in the paper.  
- The figure notebooks (`1a.nb` through `12a-12b.nb`) produce the plots shown in the article; they assume the corresponding data structures have been generated or are loaded from `Results-Data.nb`.

## Data Availability
The data and code that support the findings of this article are openly available in Zenodo at `` .
