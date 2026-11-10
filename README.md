# Project : Intelligent Substation Inspection

## Data Source

This project uses the **Semantically Annotated 15-Class Ground Truth Dataset for Substation Equipment** (Gomes, 2023), published on Zenodo under the CC BY 4.0 license. It contains 1660 substation images with 50705 annotated objects across 15 classes.

- Dataset record: https://zenodo.org/records/7884270
- DOI: [10.5281/zenodo.7884270](https://doi.org/10.5281/zenodo.7884270)
- Direct download (about 1.84 GB): [substation-semantic-dataset.zip](https://zenodo.org/records/7884270/files/substation-semantic-dataset.zip?download=1)

To download the archive, run [notebooks/01_data_preparation.ipynb](notebooks/01_data_preparation.ipynb). It saves the zip to `data/raw/` when run locally, or to Google Drive (`MyDrive/`) when run in Colab, and verifies it against the checksum published on Zenodo.
