# Evolutionary Genetics Analysis: Human, Neanderthal, and Chimpanzee

### Project Overview
This project performs a comparative genomic analysis to quantify the genetic similarity between **Homo Sapiens (Human)**, **Homo Neanderthalensis (Neanderthal)**, and **Pan Troglodytes (Chimpanzee)**.

Using **Python** and **BioPython**, the project utilizes Pairwise Sequence Alignment algorithms to calculate alignment scores and evolutionary divergence.

### Technologies & Libraries
* **Python**
* **BioPython** (SeqIO, PairwiseAligner)
* **NumPy** (Data handling)
* **Matplotlib / Plotly** (Visualization)

### Methodology
1.  **Data Acquisition:** Genomic sequences (FASTA format) were retrieved from NCBI (National Center for Biotechnology Information).
2.  **Sequence Loading:** Parsed DNA sequences using `Bio.SeqIO`.
3.  **Alignment:** Applied global pairwise alignment (Needleman-Wunsch algorithm) to find optimal matching regions.
4.  **Scoring:** Calculated similarity scores to determine evolutionary closeness.

### Key Results
* **Human vs. Neanderthal:** High similarity score observed, indicating recent common ancestry and interbreeding.
* **Human vs. Chimpanzee:** Significant divergence observed compared to the Neanderthal genome.
* *(Detailed alignment scores can be found in the notebook).*

### How to Run

1.  Install requirements:
    ```bash
    pip install biopython numpy matplotlib
    ```
2.  Run the Jupyter Notebook:
    ```bash
    jupyter notebook human_neanderthal_chimp.ipynb
    ```

---
*Developed by Furkan Onur*
