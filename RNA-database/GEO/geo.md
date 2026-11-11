# 🧬 GEO – Gene Expression Omnibus

🔗 **Website:** https://www.ncbi.nlm.nih.gov/geo/

## 📌 What is it used for?
GEO is a public repository of **gene expression data**. Researchers deposit data from microarray, RNA-seq and single-cell experiments so that others can reuse them. It is commonly used to find published datasets, compare results with other studies and download expression matrices for new analyses.

## 🗂️ Type of database
| By data origin | By data review |
|---|---|
| Primary | Not reviewed (repository) |

Maintained by the **NCBI** (USA). Submissions must follow the **MIAME** standard (Minimum Information About a Microarray Experiment).

## ⭐ Key features
- Data are organised with identifiers:
  - **GSE** (Series): a complete study, usually linked to a publication
  - **GSM** (Sample): an individual sample
  - **GPL** (Platform): the microarray or sequencer used
  - **GDS** (DataSet): curated studies, mostly older microarrays
- **GEO2R** allows differential expression analysis directly on the web.
- Raw sequencing reads (FASTQ) are stored in the **SRA**, linked from each GEO series.
- Data can be downloaded programmatically from R with the Bioconductor package **GEOquery**.
