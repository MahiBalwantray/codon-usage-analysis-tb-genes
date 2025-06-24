# Codon Usage Analysis of Tuberculosis Resistance Genes

This project performs **codon usage bias analysis** on three essential *Mycobacterium tuberculosis* resistance genes: `katG`, `rpoB`, and `inhA`. These genes are associated with resistance to first-line anti-TB drugs like isoniazid and rifampicin.

Using **Biopython** and **Matplotlib**, codon frequencies are computed and visualized to understand codon preference, which may reflect gene expression patterns or evolutionary pressure in *M. tuberculosis*.

---

## 🔬 Genes Analyzed

| Gene  | Function                               | Resistance Type     |
|-------|----------------------------------------|---------------------|
| katG  | Catalase-peroxidase                    | Isoniazid resistance |
| rpoB  | RNA polymerase beta subunit            | Rifampicin resistance |
| inhA  | NADH-dependent enoyl-ACP reductase     | Isoniazid resistance |

---

## 📁 Project Files

- `katG.fasta.txt`, `rpoB.fasta.txt`, `inhA.fasta.txt` – Input FASTA files
- `tb-codon-usage-analysis.ipynb` – Main Jupyter notebook
- `*.csv` files – Codon frequency tables for each gene
- `*.png` files – Codon usage bar plots for each gene

---

## 📊 Features

- Parses input FASTA files using Biopython
- Calculates codon frequency per gene
- Plots codon usage as bar charts
- Saves both CSV and PNG outputs automatically

---

## 🛠️ Tools & Libraries

- Python 3
- [Biopython](https://biopython.org/)
- Matplotlib
- Pandas

To install the required packages:
```bash
pip install biopython matplotlib pandas
