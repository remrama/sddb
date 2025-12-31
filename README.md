# Sleep and Dream Database

Dream reports collected from a variety of sources and aggregated in the public
[Sleep and Dream Database](https://sleepanddreamdatabase.org).

| | Summary |
|--:|:--|
| File | `sddb.tsv.xz` |
| Size | 4 Mb |
| Version | [v1-alpha.2](https://github.com/krank-sources/sddb/releases/tag/v1-alpha.2) |
| MD5 | `md5:082496b09f8973e511e15190bc344ac1` |
| SHA256 | `sha256:42fcb9e4f847f72cf64f20ca4f50d0028ee514d8bdfdcbe999dc9c2f02d5ac29` |
| Source | [Sleep and Dream Database](https://sleepanddreamdatabase.org/library) |
| References | Bulkeley, K. (2014). Digital dream analysis: A revised method. _Conscious Cogn_. doi:[10.1016/j.concog.2014.08.015](https://doi.org/10.1016/j.concog.2014.08.015) <br> Bulkeley, K. (2023). New approaches in the empirical study of dreams. _Poligrafi_. doi:[10.35469/poligrafi.2023.412](https://doi.org/10.35469/poligrafi.2023.412) |
| Processing code | [`prepare.ipynb`](prepare.ipynb) |
| Processing environment | [`environment.yaml`](environment.yaml) |

## Changes made

> These are the changes made to the original dataset.

* Remove excess metadata columns
* Clean/standardize dream report text
* Merge related datasets and authors
* Rename datasets
* Replace author names with standardized codes
* Remove entries with extreme word counts
* Remove datasets with small sample sizes
* Convert from comma-separated values (`csv`) to tab-separated values (`tsv`)

# Raw (original source) data

The SDDb source file comes from a [Zenodo archive](https://doi.org/10.5281/zenodo.18076716). See the description there for details on how the data was initially collected.

For older versions with less dream reports but more metadata (as columns), see access points mentioned in [this GitHub Issue](https://github.com/krank-sources/sddb/issues/1) and [./raw/compare.ipynb](./raw/compare.ipynb). The current version has 2 additional datasets and ~5k more dream reports than the previous versions, but again with less metadata.
