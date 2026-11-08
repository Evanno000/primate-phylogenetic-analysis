# Primate HBB Protein Sequence Alignment and Phylogenetic Visualization

**Project 5 | Bioinformatics Portfolio**

## 1. Project Overview

This project investigates the conservation and variation of the beta-globin (HBB) protein among five primate species using bioinformatics tools.

Beta-globin is a protein subunit of haemoglobin, the oxygen-transport protein found in red blood cells. Comparing its amino acid sequence across different primates provides an opportunity to investigate protein conservation and sequence variation.

Five HBB protein sequences were retrieved from the NCBI Protein Database, aligned using EMBL-EBI Clustal Omega, and visualized using the Interactive Tree of Life (iTOL).

The project demonstrates practical applications of protein sequence retrieval, multiple sequence alignment, comparative sequence analysis and phylogenetic visualization.

## 2. Research Question

How conserved is the beta-globin protein among selected primate species, and what amino acid sequence differences can be identified through multiple sequence alignment?

## 3. Objectives

The main objectives were to:

1. Retrieve HBB protein sequences from five primate species.
2. Examine amino acid sequence conservation and variation.
3. Perform multiple sequence alignment using Clustal Omega.
4. Identify conserved and variable amino acid positions.
5. Generate and visualize the Clustal Omega guide tree using iTOL.
6. Interpret the findings in the context of comparative protein analysis.

## 4. Species Investigated

Five primate species were selected for comparison.

| Species | Scientific name | Protein accession |
|---|---|---|
| Human | *Homo sapiens* | P68871.2 |
| Chimpanzee | *Pan troglodytes* | XP_508242.1 |
| Gorilla | *Gorilla gorilla* | P02024.2 |
| Orangutan | *Pongo pygmaeus* | XP_054296805.1 |
| Rhesus macaque | *Macaca mulatta* | NP_001157900.1 |

All five retrieved protein sequences contained 147 amino acids.

## 5. Biological Background

Haemoglobin is a tetrameric protein responsible for transporting oxygen from the lungs to body tissues.

Adult human haemoglobin (HbA) consists of two alpha-globin and two beta-globin subunits.

The beta-globin protein is encoded by the HBB gene. Changes in its amino acid sequence can influence protein structure and function.

Because haemoglobin performs an essential physiological function, its protein sequence is highly conserved across many vertebrate species.

Comparing HBB sequences among primates therefore provides a useful model for studying protein conservation and molecular variation.

## 6. Methodology

### Step 1: Protein Sequence Retrieval

Protein sequences were retrieved from the NCBI Protein Database.

The following accessions were used:

- Human: P68871.2
- Chimpanzee: XP_508242.1
- Gorilla: P02024.2
- Orangutan: XP_054296805.1
- Rhesus macaque: NP_001157900.1

The five sequences were collected in FASTA format and saved in a file named:

`primate_HBB.fasta`

### Step 2: Multiple Sequence Alignment

Multiple sequence alignment was performed using EMBL-EBI Clustal Omega.

Clustal Omega aligns protein sequences to identify:

- Conserved amino acid positions.
- Variable amino acid positions.
- Similar amino acid substitutions.
- Sequence similarities and differences.

The resulting alignment was saved as:

`HBB_alignment.aln`

### Step 3: Guide Tree Generation

Clustal Omega generated a guide tree associated with the multiple sequence alignment.

The tree was provided in Newick format and saved as:

`HBB_phylogenetic_tree.nwk`

### Step 4: Tree Visualization

The Newick tree was uploaded to the Interactive Tree of Life (iTOL).

A text-label dataset was added to replace accession numbers with the corresponding primate names.

The resulting visualization was exported as:

`primate_HBB_tree.png`

## 7. Results

### 7.1 Multiple Sequence Alignment

The alignment revealed substantial conservation among the five HBB protein sequences.

The major observations included:

- All five sequences contained 147 amino acids.
- No gaps were observed in the alignment.
- Many amino acid positions were identical across all five sequences.
- Several positions showed amino acid variation.
- Human and chimpanzee HBB sequences were identical across all 147 aligned positions.

### 7.2 Sequence Comparison

Comparison with the human HBB reference sequence showed:

| Species | Observed sequence relationship |
|---|---|
| Human | Reference sequence |
| Chimpanzee | Identical to human in this alignment |
| Gorilla | Very high sequence similarity |
| Orangutan | High sequence similarity with additional substitutions |
| Rhesus macaque | Greater sequence variation in this dataset |

These observations demonstrate that beta-globin is a highly conserved protein among the selected primates.

### 7.3 Phylogenetic Visualization

The Clustal Omega guide tree was visualized using iTOL.

The visualization displays the five HBB protein sequence identifiers and their associated branch lengths.

**Tree visualization:**

![Primate HBB guide tree](primate_HBB_tree.png)

## 8. Discussion

### Conservation of Beta-Globin

The high degree of sequence conservation observed among the five primates suggests that beta-globin has remained relatively conserved during primate evolution.

This conservation is consistent with the important physiological role of haemoglobin in oxygen transport.

### Human and Chimpanzee Similarity

Human and chimpanzee HBB sequences were identical in the dataset analysed.

This demonstrates the high degree of amino acid sequence similarity between the selected human and chimpanzee beta-globin proteins.

### Variation Among Other Primates

Gorilla, orangutan and rhesus macaque displayed amino acid differences relative to the human sequence.

These substitutions demonstrate that protein sequences can retain substantial similarity while still displaying evolutionary variation.

### Interpretation of the Guide Tree

The Clustal Omega guide tree provides an exploratory representation used in the progressive alignment process.

It should not be treated as a definitive phylogenetic reconstruction of primate evolutionary relationships.

A more rigorous phylogenetic investigation would require an appropriate evolutionary substitution model, a dedicated phylogenetic inference method and statistical support, such as bootstrap analysis.

## 9. Limitations

The project had several limitations:

1. Only five primate species were investigated.
2. Only one protein, beta-globin, was analysed.
3. Protein sequence similarity does not necessarily represent the complete evolutionary history of an organism.
4. The Clustal Omega guide tree was not subjected to formal phylogenetic model selection or bootstrap analysis.
5. The dataset included both curated Swiss-Prot and predicted RefSeq protein records.

Future investigations could include additional primate species, multiple protein-coding genes and maximum-likelihood phylogenetic analysis with bootstrap support.

## 10. Conclusion

This project demonstrated how bioinformatics tools can be applied to comparative protein sequence analysis.

The multiple sequence alignment revealed substantial conservation of beta-globin among five selected primate species, with human and chimpanzee displaying identical amino acid sequences in the dataset.

The project also provided practical experience in protein sequence retrieval, FASTA file preparation, multiple sequence alignment, sequence interpretation, Newick tree handling and phylogenetic visualization.

These skills form an important foundation for further studies in bioinformatics, computational biology, molecular evolution and genomics.

## 11. Tools and Resources

| Tool / Database | Application |
|---|---|
| NCBI Protein Database | Protein sequence retrieval |
| EMBL-EBI Clustal Omega | Multiple sequence alignment |
| Interactive Tree of Life (iTOL) | Tree visualization |
| Visual Studio Code | File preparation and editing |
| GitHub | Project documentation and portfolio management |

## 12. Project Files

The repository contains the following files:

```text
primate-phylogenetic-analysis/
│
├── README.md
├── primate_HBB.fasta
├── HBB_alignment.aln
├── HBB_phylogenetic_tree.nwk
├── primate_labels.txt
└── primate_HBB_tree.png
```

## 13. References

1. National Center for Biotechnology Information (NCBI). Protein Database. https://www.ncbi.nlm.nih.gov/protein/
2. EMBL-EBI. Clustal Omega Multiple Sequence Alignment Tool. https://www.ebi.ac.uk/jdispatcher/msa/clustalo
3. Interactive Tree of Life (iTOL). https://itol.embl.de/
4. Sievers, F. et al. (2011). Fast, scalable generation of high-quality protein multiple sequence alignments using Clustal Omega. *Molecular Systems Biology*, 7, 539. https://doi.org/10.1038/msb.2011.75

---

Author:Evans Kioko
Project:Primate HBB Protein Sequence Alignment and Phylogenetic Visualization

Field: Bioinformatics | Comparative Genomics | Protein Sequence Analysis