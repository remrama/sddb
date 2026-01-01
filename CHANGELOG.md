# Changes made

## Versioning

Given a version number MAJOR.MINOR.PATCH, increment the:

1. MAJOR version when you change the **raw/bronze** data (SDDb collection)
2. MINOR version when you change the **processed/silver** data (SDDb collection)
3. PATCH version when you change the **curated/gold** data (sub-corpora) or perform maintenance

## v1

* Fresh SDDb download and uploaded to Zenodo (this new file is much cleaner, but might be worth going back to older files for metadata at some point)
* Removed raw SDDb file from GitHub repository and related files, such as `raw/create.ipynb` and `raw/README.md`, because now pulling from Zenodo
* Added `raw/comparison.ipynb` for quick comparison and storing metadata of the different SDDb source files available
* Reduction in filtering steps in `prepare.ipynb`, since some of that is not happening in krank later
* Broke apart `prepare.ipynb` so that file is only about curating now, and describing it is done elsewhere. of preprocessing steps that were applied to the original dataset that was much dirtier. (e.g., column renamings)
