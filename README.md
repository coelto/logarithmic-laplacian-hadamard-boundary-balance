# Logarithmic Laplacian, Hadamard formula and boundary balance for the infimum of the truncated Weil form

Vadim Chekmachev · chekmachev@phystech.edu · ORCID [0009-0009-2982-0532](https://orcid.org/0009-0009-2982-0532)

DOI of all versions: [![10.5281/zenodo.23848534](https://zenodo.org/badge/DOI/10.5281/zenodo.23848534.svg)](https://doi.org/10.5281/zenodo.23848534)

## Abstract

Let λ(c) be the infimum of the truncated Weil form in the even sector over normalized functions supported in [−a, a], a = (ln c)/2. Every bounded weak solution of the Dirichlet problem for the logarithmic Laplacian L<sub>Δ</sub> on an interval with bounded right-hand side has, at distance δ from the boundary, an expansion u(a − δ) = β(ln(1/δ))<sup>−1/2</sup> + O((ln(1/δ))<sup>−1</sup>) with a boundary coefficient β. The expansion is derived from a first-order linear equation for the averages of the solution against bump functions shrinking to the boundary. The Pohozaev identity for the problem (L<sub>Δ</sub> − μ<sub>0</sub>)z = f, valid for every μ<sub>0</sub>, yields β<sup>2</sup> = 1/(2a) for every real normalized eigenfunction of the operator L<sub>Δ</sub> on (−a, a), and with it the simplicity of its spectrum. The function λ is locally Lipschitz in a and differentiable outside an at most countable set, and at points of differentiability dλ/da = −2β<sup>2</sup>, where β is the boundary coefficient of any minimizer. The terms with powers p<sup>m</sup> of primes do not enter this formula, and the derivative of λ exists at every point where λ(c) is a simple eigenvalue, including c = p<sup>m</sup>. The boundary balance r<sub>c</sub> is the ratio of the logarithmic decay rates of λ and of the Fuchs scale d<sub>c</sub> of order c<sup>9/2</sup>e<sup>−4πc</sup>. If r<sub>c</sub> ≤ ρ with a constant ρ ≥ 0 on the intervals where λ &gt; 0, then λ(c) ≥ λ(5)(d<sub>c</sub>/d<sub>5</sub>)<sup>ρ</sup> &gt; 0 for all c ≥ 5. Boundedness of r<sub>c</sub> does not follow from the proved properties of λ and remains an open question. Rigorous bounds for λ give the bound 1.0009 for the weighted mean of r<sub>c</sub> over [5, 71], but not the values of r<sub>c</sub> at individual points.

Pages: 46. Figures: 6. MSC 2020: primary 11M26, secondary 47A75, 35R11.

## Files

The repository contains the PDF of the paper, the notes on the changes in this version (`version-notes-v3.txt`), a list of checksums `SHA256SUMS` and an OpenTimestamps timestamp for the PDF (a file with extension `.ots`). `SHA256SUMS` contains the SHA-256 of the PDF, its `.ots` proof and the version notes. The same PDF and notes are published in the Zenodo record of this version.

| File | Size, bytes | SHA-256 | MD5 |
|---|---|---|---|
| `chekmachev-logarithmic-laplacian-hadamard-boundary-balance-v3.pdf` | 1085614 | `fb31a9faf18c30789c03db3a2651d12264dede184da6547e91970465d153b95b` | `795ed74ce1a83adeed36e66b3b41de4c` |
| `chekmachev-logarithmic-laplacian-hadamard-boundary-balance-v3.pdf.ots` | 2700 | `f0a572990288adc862d32c461a867a0006f2470ccc5082050c129f5c482f505f` | `53836530dcb9a7a89fbe93e45448e821` |
| `version-notes-v3.txt` | 1492 | `5f8d12292ca2710ed1b812fe7035d02f0387b6493d10800b1a6ae94cd3839471` | `88389fbf0a7ee113a528d7913e331fdd` |

OpenTimestamps time (UTC): 2026-11-20 19:56:51.

## Version history

Each version of the paper is a separate version of a single Zenodo record with its own DOI. The record's common DOI resolves to the latest version, and the paper should be cited by it.

| Version | Publication date | DOI |
|---|---|---|
| 1.0 | 2026-10-31 | [10.5281/zenodo.23848535](https://doi.org/10.5281/zenodo.23848535) |
| 2.0 | 2026-11-05 | [10.5281/zenodo.23978194](https://doi.org/10.5281/zenodo.23978194) |
| 3.0 (this version) | 2026-11-20 | [10.5281/zenodo.24399903](https://doi.org/10.5281/zenodo.24399903) |

## Data

The numerical statements of the paper and its figures were obtained from data published in a separate Zenodo record. All versions of this record are listed below.

DOI of all versions: [![10.5281/zenodo.23186383](https://zenodo.org/badge/DOI/10.5281/zenodo.23186383.svg)](https://doi.org/10.5281/zenodo.23186383)

| Version | Publication date | DOI | Title |
|---|---|---|---|
| 1.0 | 2026-10-06 | [10.5281/zenodo.23186384](https://doi.org/10.5281/zenodo.23186384) | Computational data for the paper "Boundary balance and the scaling law for the infimum of the truncated Weil form" |
| 1.1 | 2026-10-31 | [10.5281/zenodo.23847836](https://doi.org/10.5281/zenodo.23847836) | Computational data for the paper "Logarithmic Laplacian, Hadamard formula and boundary balance for the infimum of the truncated Weil form" |
| 1.2 | 2026-11-19 | [10.5281/zenodo.24378296](https://doi.org/10.5281/zenodo.24378296) | Computational data for the paper "Logarithmic Laplacian, Hadamard formula and boundary balance for the infimum of the truncated Weil form" |

## Verification

Checksums. The command `sha256sum -c SHA256SUMS` checks the files of the repository against the list. Zenodo shows each file's MD5 next to it. It is also given in the table above, so whether a file matches the published one can be verified without downloading the archives.

Timestamp. The `.ots` file is an OpenTimestamps proof: the SHA-256 checksum of the PDF is written into a Bitcoin block, and no one can change the time of that block. To verify, it suffices to drag the PDF and the `.ots` file onto the page https://opentimestamps.org or to run `ots verify` on the proof. The file does not leave the computer in the process.

Signature. The commits of this repository are signed by the author, and GitHub marks them as Verified.

## License

The terms of distribution of the paper and its copy in this repository are given in the [`LICENSE`](LICENSE) file.
