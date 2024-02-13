# Practical Bioinformatics

### -Akshat Saxena(2022055)

## Task 1: Download the Genome Sequence of Baker’s Yeast (Saccharomyces cerevisiae)

### Citations:

1. used (https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_000146045.2/) to access the database of Baker's Yeast ARSs and Ref_Sequences
2. downloaded fasta files for ref_sequence (all 17) and then found the ORI in each fasta file

### Code Documentation:

1. The first code block is used to download the fasta files using each ref_sequence one-by-one using a for loop
2. The second code block is used to find the ORIs (positions of the ARSs)
3. The script will iterate through the provided list of ARS sequences and search for their positions in each specified FASTA file. The results will be printed, indicating the positions of the ARS sequences in each file.

#### Dependencies:
- Python 3.x

#### Instructions:
1. Ensure Python is installed on your system.
2. Run the script using the run command

## Task 2: Find the Origin of Replication in the Yeast Genome

### Code Documentation:

The Python script aims to find the positions of potential Origin of Replication (ARS) sequences in the Baker’s Yeast genome. The script reads multiple FASTA files and searches for specified ARS sequences (`possible_ars`).

### Important Note:
- Please make sure that the FASTA files (`outNC_001133.9.fasta` to `outNC_001224.1.fasta`) are in the same directory as the scripts.

For any issues or concerns, please contact [Akshat Saxena] at [akshat22055@iiitd.ac.in].

