---
title: "Examining Data on the NCBI SRA Database"
teaching: 0
exercises: 0
questions:
- "Key question"
objectives:
- "First objective."  
keypoints:
- "First key point."
---

# Accessing the original archived data
The sequencing dataset was obtained from the [NCBI Sequence Read Archive](http://www.ncbi.nlm.nih.gov/sra), which is a large (>3 quadrillion basepairs as of 2014) repository for next-generation sequence data. Like many NCBI databases, it is complex and mastering its use is greater than the scope of this lesson. Very often, as in the Lenski paper, there will be a direct link (perhaps in the supplemental information) to where on the SRA the dataset can be found. The link from the Lenski paper is: [http://www.ncbi.nlm.nih.gov/sra?term=SRA026813](http://www.ncbi.nlm.nih.gov/sra?term=SRA026813)  

## Locate the Run Accessory Table for the Lenski Dataset on the SRA

1. Access the Lenski dataset from the provided link: [http://www.ncbi.nlm.nih.gov/sra?term=SRA026813](http://www.ncbi.nlm.nih.gov/sra?term=SRA026813).  
You will be presented with a page for the overall SRA accession SRA026813 - this is a collection of all the experimental data.

2. Click on the first entry ([ZDB30](http://www.ncbi.nlm.nih.gov/sra/SRX040669%5Baccn%5D)). This will take you to a page for an SRX (Sequence Read eXperiment). Take a few minutes to examine some of the descriptions on the page.

3. Click on the ['All runs'](http://www.ncbi.nlm.nih.gov/Traces/study/?acc=SRP004752) link under where it says **Study**. This is a description of all of the NGS datasets related to the experiment.  

4. Go to the top of the page and in the **Total** row you will see there are 37 runs, 10.15Gb data, and 16.45 Gbases of data. Click the 'RunInfo Table' button.  

We are not downloading any actual sequence data here! This is only a text file that fully describes the entire
dataset.  

You should now have a file called `SraRunTable.txt`

## Review the SraRunTable in a spreadsheet program


Using your choice of spreadsheet program open the **SraRunTable.txt** file. If prompted this is a tab-delimited file (`.tsv`).

> ## Discussion  
> Discuss with the person next to you:
> 
> 1. What strain of *E. coli* was used in this experiment?
> 2. What was the sequencing platform used for this experiment?
> 3. What samples in the experiment contain
> [paired end](http://www.illumina.com/technology/next-generation-sequencing/paired-end-sequencing_assay.html)
> sequencing data?
> 4. What other kind of data is available?
> 5. Are you collecting this kind of information about your sequencing runs?
{: .challenge}

After answering the questions, you should avoid saving this file. We don't want to make any changes. If you were to save this file, make sure you save it as a plain `.txt` file.


## Where to learn more

#### About the Sequence Read Archive

* You can learn more about the SRA by reading the [SRA Documentation](http://www.ncbi.nlm.nih.gov/Traces/sra/)  
* The best way to transfer a large SRA dataset is by using the [SRA Toolkit](http://www.ncbi.nlm.nih.gov/Traces/sra/?view=toolkit_doc)  

#### References

Blount, Z.D., Barrick, J.E., Davidson, C.J., Lenski, R.E.
Genomic analysis of a key innovation in an experimental Escherichia coli population (2012) Nature, 489 (7417), pp. 513-518.  
[Paper](https://www.ncbi.nlm.nih.gov/pubmed/22992527), [Supplemental materials](https://www.nature.com/nature/journal/v489/n7417/full/nature11514.html#supplementary-information)  
Data on NCBI SRA: [http://www.ncbi.nlm.nih.gov/sra?term=SRA026813](http://www.ncbi.nlm.nih.gov/sra?term=SRA026813)
