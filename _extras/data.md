---
layout: page
title: Data
---

# Features of the dataset  

This dataset was selected for our exercise on NGS Data Carpentry for several reasons, including:

* Simple, but iconic NGS-problem: Examine a population where we want to characterize changes in sequence *a priori*   
* Dataset publicly available - in this case through the NCBI Sequence Read Archive (http://www.ncbi.nlm.nih.gov/sra)  
* Small file sizes - while several of related files may still be hundreds of MBs, overall we will be able to get through more quickly than if we worked with a larger eukaryotic genome  

# Introduction to the dataset  

Microbes are ideal organisms for exploring 'Long-term Evolution Experiments' (LTEEs) - thousands of generations can be generated and stored in a way that would be virtually impossible for more complex eukaryotic systems. In [Tenaillon et al 2016](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4988878/), 12 populations of *Escherichia coli* were propagated for more than 50,000 generations in a glucose-limited minimal medium. This medium was supplemented with citrate which *E. coli* cannot metabolize in the aerobic conditions of the experiment. Sequencing of the populations at regular time points reveals that spontaneous citrate-using mutants (Cit+) appeared in a population of *E.coli* (designated Ara-3) at around 31,000 generations. It should be noted that spontaneous Cit+ mutants are extraordinarily rare - inability to metabolize citrate is one of the defining characters of the *E. coli* species. Eventually, Cit+ mutants became the dominant population as the experimental growth medium contained a high concentration of citrate relative to glucose. Around the same time that this mutation emerged, another phenotype become prominent in the Ara-3 population. Many *E. coli* began to develop excessive numbers of mutations, meaning they became hypermutable. 

Strains from generation 0 to generation 50,000 were sequenced, including ones that were both Cit+ and Cit- and hypermutable in later generations.  

For the purposes of this workshop we're going to be working with 3 of the sequence reads from this experiment. 

| SRA Run Number | Clone | Generation | Cit  | Hypermutable | Read Length | Sequencing Depth |
| -------------- | ----- | ---------- | ---- | ----- |-------|--------| 
| SRR2589044 | REL2181A | 5,000 | Unknown | None |  150 | 60.2 |
| SRR2584863 | REL7179B | 15,000 | Unknown | None |  150 | 88 |
| SRR2584866 | REL11365 | 50,000 | Cit+ | plus |  150 | 138.3 |

We want to be able to look at differences in mutation rates between hypermutable and non-hypermutable strains. We also want to analyze the sequences to figure out what changes occurred in genomes to make the strains Cit+. Ultimately, we will answer the questions:  

- How many base pair changes are there between the Cit+ and Cit- strains?  
- What are the base pair changes between strains?  

## References  

Tenaillon O, Barrick JE, Ribeck N, Deatherage DE, Blanchard JL, Dasgupta A, Wu GC, Wielgoss S, Cruveiller S, Médigue C, Schneider D, Lenski RE.
Tempo and mode of genome evolution in a 50,000-generation experiment (2016) Nature. 536(7615): 165–170.  
[Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4988878/), [Supplemental materials](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4988878/#)  
Data on NCBI SRA: [https://trace.ncbi.nlm.nih.gov/Traces/sra/?study=SRP064605](https://trace.ncbi.nlm.nih.gov/Traces/sra/?study=SRP064605)  
Data on EMBL-EBI ENA: [https://www.ebi.ac.uk/ena/data/view/PRJNA295606](https://www.ebi.ac.uk/ena/data/view/PRJNA295606)
