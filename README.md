# Logarithmic Laplacian, Hadamard formula and boundary balance for the infimum of the truncated Weil form

Vadim Chekmachev · chekmachev@phystech.edu · ORCID [0009-0009-2982-0532](https://orcid.org/0009-0009-2982-0532)

GitHub repository: https://github.com/coelto/logarithmic-laplacian-hadamard-boundary-balance.

DOI of all versions: [10.5281/zenodo.23848534](https://doi.org/10.5281/zenodo.23848534).

## Abstract

Let λ(c) be the infimum of the truncated Weil form in the even sector over functions supported in [−a, a], a = (ln c)/2. Every bounded weak solution of the Dirichlet problem for the logarithmic Laplacian on an interval with bounded right-hand side has, at distance δ from the boundary, an expansion u(a − δ) = β(ln(1/δ))<sup>−1/2</sup> + O((ln(1/δ))<sup>−1</sup>) with a boundary coefficient β. The expansion is derived from a first-order linear equation for the averages of the solution against bump functions shrinking to the boundary. The Pohozaev identity for the problem (L<sub>Δ</sub> − μ<sub>0</sub>)z = f, valid for every μ<sub>0</sub>, yields β<sup>2</sup> = 1/(2a) for every real normalized eigenfunction of this operator on (−a, a), and with it the simplicity of its spectrum. The function λ is locally Lipschitz in a and differentiable outside an at most countable set, and at points of differentiability dλ/da = −2β<sup>2</sup>, where β is the boundary coefficient of any minimizer. The terms with powers p<sup>m</sup> of primes do not enter this formula, and the derivative of λ exists at every point where λ(c) is a simple eigenvalue, including c = p<sup>m</sup>. The boundary balance r<sub>c</sub> is the ratio of the logarithmic decay rates of λ and of the explicit scale Θ<sub>c</sub> of order c<sup>5</sup>e<sup>−4πc</sup>. If r<sub>c</sub> ≤ ρ with a constant ρ ≥ 0 on the intervals where λ &gt; 0, then λ(c) ≥ λ(5)(Θ<sub>c</sub>/Θ<sub>5</sub>)<sup>ρ</sup> &gt; 0 for all c ≥ 5. Boundedness of r<sub>c</sub> does not follow from the proved properties of λ and remains an open question. Rigorous bounds for λ give the bound 1.0022 for the weighted mean of r<sub>c</sub> over [5, 71], but not the values of r<sub>c</sub> at individual points.

Pages: 45. Figures: 6. MSC 2020: primary 11M26, secondary 47A75, 35R11.

## Files

The repository contains the PDF of the paper, a list of checksums `SHA256SUMS` and an OpenTimestamps timestamp for it (a file with extension `.ots`). The same PDF is published in the Zenodo record of this version.

| File | Size, bytes | SHA-256 | MD5 |
|---|---|---|---|
| `chekmachev-logarithmic-laplacian-hadamard-boundary-balance-v2.pdf` | 1082212 | `f0cfda4022cdc5f43f75fd8a5094666279213c4b2000e4482c9b903e7279c475` | `d3c37549d2848f80d52f38b57f7dd4ae` |
| `chekmachev-logarithmic-laplacian-hadamard-boundary-balance-v2.pdf.ots` | 2655 | `ce4ad745e816296b24f4b9cd471274f65c7f0bd58a7ca4f0937f1f6b3717d178` | `5ca6c6124f60df8c9dbeecfb0b6cfe79` |

OpenTimestamps time (UTC): 2026-11-05 12:02:41.

## Version history

Each version of the paper is a separate version of a single Zenodo record with its own DOI. The record's common DOI resolves to the latest version, and the paper should be cited by it.

| Version | Publication date | DOI |
|---|---|---|
| 1.0 | 2026-10-31 | [10.5281/zenodo.23848535](https://doi.org/10.5281/zenodo.23848535) |
| 2.0 (this version) | 2026-11-05 | [10.5281/zenodo.23978194](https://doi.org/10.5281/zenodo.23978194) |

## Data

The numerical statements of the paper and its figures were obtained from data published in a separate Zenodo record. All versions of this record are listed below.

DOI of all versions: [10.5281/zenodo.23186383](https://doi.org/10.5281/zenodo.23186383).

| Version | Publication date | DOI | Title |
|---|---|---|---|
| 1.0 | 2026-10-06 | [10.5281/zenodo.23186384](https://doi.org/10.5281/zenodo.23186384) | Computational data for the paper "Boundary balance and the scaling law for the infimum of the truncated Weil form" |
| 1.1 | 2026-10-31 | [10.5281/zenodo.23847836](https://doi.org/10.5281/zenodo.23847836) | Computational data for the paper "The logarithmic Laplacian, the Hadamard formula and the boundary balance for the infimum of the truncated Weil form" |

## Verification

Checksums. The command `sha256sum -c SHA256SUMS` checks the files of the repository against the list. Zenodo shows each file's MD5 next to it. It is also given in the table above, so whether a file matches the published one can be verified without downloading the archives.

Timestamp. The `.ots` file is an OpenTimestamps proof: the SHA-256 checksum of the PDF is written into a Bitcoin block, and no one can change the time of that block. To verify, it suffices to drag the PDF and the `.ots` file onto the page https://opentimestamps.org or to run `ots verify` on the proof. The file does not leave the computer in the process.

Signature. The commits of this repository are signed by the author, and GitHub marks them as Verified.

## License

The terms of distribution of the paper and its copy in this repository are given in the [`LICENSE`](LICENSE) file.
