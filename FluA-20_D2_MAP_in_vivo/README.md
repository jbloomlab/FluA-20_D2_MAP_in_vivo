# FluA-20_D2_MAP_in_vivo

## Overview
Mutational antigenic profiling of potential escape mutations in A/WSN/33 H1 HA codon mutant libraries from the non-neutralizing antibodies [FluA-20](https://www.ncbi.nlm.nih.gov/pubmed/31100268) and [D2 H1-1/H3-1](https://www.ncbi.nlm.nih.gov/pubmed/27820605)(here referred to as D2) using the DBA/2J mouse model of influenza infection.

Profiling was done by Lauren Gentles and Jesse Bloom.

# Input data
Input data are in the [./data/](data) subdirectory.

- [./data/WSN-HA.fasta](./data/WSN-HA.fasta) contains the wildtype sequence of the A/WSN/1933 H1N1 hemagglutinin used in the experimental virus library.

- [./data/samplelist.csv](./data/samplelist.csv) provides the R1 location as well as relavent information about each sample.

- [./data/H1toH3renumber.csv](./data/H1toH3_renumber.csv) is a CSV file that mapes the numbering from the sequential numbering of the WSN HA protein to the commonly used H3 nubering scheme. The sequential numbering is in the *original* column, and the H3 number is in the *new* column.
