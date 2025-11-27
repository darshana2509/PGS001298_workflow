This repository contains a complete analysis of the scoring file:
**PGS001298_hmPOS_GRCh38.txt.gz**

The assignment includes:

## Tasks Performed
1. Download the PGS scoring file using bash.
2. Preprocess the data.
3. Perform exploratory data analysis using Pandas.
4. Filter the variants belonging to **chromosome 21** using `hm_chr` and `hm_pos`.
5. Generate and visualize a histogram of `effect_weight` distribution for chr21.
6. Prepare a `gsutil` command to copy a folder between Google Cloud buckets.

## Technologies Used
- Python 3 (Google Colab)
- Pandas
- Matplotlib
- Bash (wget, gunzip)
- Google Cloud SDK (gsutil command only)

## How to Run
Open the `analysis.ipynb` notebook either in Google Colab or locally using Jupyter.

Example:
- Click: **Open in Colab**
- Run each cell sequentially

## Files Included
- `analysis.ipynb` – Full notebook containing all analysis steps.
- `gsutil_copy_command.txt` – Required one-line gsutil command.
- `requirements.txt` – Python libraries needed.

---
