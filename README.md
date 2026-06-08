# NCBI Sequence Retrieval and GC Content Analysis

## Overview

This project demonstrates how to retrieve biological sequences from the NCBI database using Biopython and perform basic sequence analysis.

The workflow includes downloading DNA sequences from NCBI, calculating sequence length and GC content, and comparing sequence characteristics across different species.

## Objectives

* Retrieve biological sequences from NCBI using accession numbers.
* Calculate sequence length.
* Calculate GC content.
* Organize biological data using Pandas.
* Explore basic bioinformatics workflows using Python.

## Technologies Used

* Python
* Biopython
* Pandas
* NCBI Entrez

## Methodology

### 1. Sequence Retrieval

DNA sequences were downloaded directly from the NCBI GenBank database using accession numbers and the Entrez module from Biopython.

### 2. Sequence Processing

For each sequence, the following metrics were calculated:

* Sequence length
* GC content (%)

GC content represents the proportion of guanine (G) and cytosine (C) nucleotides within a DNA sequence.

### 3. Data Organization

The extracted information was stored in a Pandas DataFrame for comparison and analysis.

## Example Accession Numbers

The analysis used publicly available sequences obtained from NCBI.

```python
accessions = [
    "NC_001566",  # Apis mellifera
    "NC_015770",  # Bombus terrestris
    "NC_028009"   # Melipona bicolor
]
```

## Example Output

| Species   | Length | GC Content (%) |
| --------- | ------ | -------------- |
| Species 1 | ...    | ...            |
| Species 2 | ...    | ...            |
| Species 3 | ...    | ...            |

## Learning Outcomes

Through this project I learned how to:

* Access biological databases programmatically.
* Retrieve DNA sequences from NCBI.
* Work with accession numbers and GenBank records.
* Calculate basic sequence statistics.
* Apply Python tools to biological data analysis.

## Future Improvements

* Automate accession number searches using species names.
* Analyze larger datasets.
* Compare additional sequence features.
* Integrate visualization tools for comparative analysis.

## Author

**Valeria Solís**

Biologist | Data Analyst | Aspiring Bioinformatician 🧬
