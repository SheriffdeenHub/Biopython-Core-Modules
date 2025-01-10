# Biopython-Core-Modules
This includes the Python script written to manipulate biological data (DNA) using Biopython - an open-source Python library for bioinformatics.
#Transcription
#Transcription is the process of making an RNA copy of a gene's DNA sequence.
#This copy, called messenger RNA (mRNA), carries the gene's protein information encoded in DNA.
#DNA is composed of four nucleotides:
#Adenine (A)
#Thymine (T)
#Guanine (G)
#Cytosine (C)
#The sequence "ATGGCCATTGTAATGGGCCGCTGAAAGGGTGCCCGATAG"
#has a length of 39 bases (nucleotides).
#Translation
#Translation is the process in living cells in which
#proteins are produced using RNA molecules as template
# Translate RNA to protein
protein_seq = rna_seq.translate()
print(f"Protein Sequence: {protein_seq}")

#protein sequence using the single-letter amino acid code.
#Each letter corresponds to a specific amino acid
#M: Methionine, A: Alanine, I: Isoleucine, V: Valine, M: Methionine, G: Glycine
#R: Arginine, K: Lysine,  *: Stop codon Indicates the termination of translation in a protein.
# It signals that the sequence ends here during protein synthesis.
