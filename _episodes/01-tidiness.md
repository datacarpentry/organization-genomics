---
title: "Data Tidiness"
teaching: 20
exercises: 0
questions:
- "Key question"
objectives:
- "Think about and understand the types of metadata a sequencing experiment will generate."
- "Make decisions about how (if) data will be stored, archived, shared, etc."
- "Anticipate strategies we will need to learn in the rest of the lesson set."
keypoints:
- "Tabular data needs to be structured to be able to work with it effectively"
---

# Introduction

When we think about the data for a sequening project, we often start by thinking about the sequencing data that we get back from the sequencing center, but just as important, if not more so, is the data you've generated about the sequences before it ever goes to the sequencing center. This is the data about the data, often called the metadata. Without the information about what you sequenced, the sequence data itself is useless.  

> # Discussion
> With the person next to you, discuss: What kinds of data and information have
> you generated before you send your DNA/RNA off for sequencing?
> > Types of files and information you have generated:  
> > - spreadsheet or tabular data with the data from your experiment and whatever you were measuring for your study
> > - lab notebook notes about how you conducted those experiments
> > - spreadsheet or tabular data about the samples you sent off for sequencing. Sequencing centers often have a particular format they need with the name of the sample, DNA concentration and other information.
> > - lab notebook notes about how you prepared the DNA/RNA for sequencing and what type of sequencing you're doing, e.g. paired end Illumina HiSeq.
> > There likely will be other ideas here too.
> > Was this more information and data than you were expecting?
> {: .solution}
{: .challenge}

All of the data and information just discussed can be considered metadata, data about the data. We want to follow a few golden rules for metadata.

## Notes

Notes about your experiment, including how you prepared your samples from sequencing, should be in your lab notebook, whether that's a physical lab notebook or electronic lab notebook. For guidelines on good lab notebooks, see ...

Including dates on your lab notebook pages, the samples themselves and in
any records about those samples helps you associate everything with each
other later. Using dates also helps create unique identifiers, because even
if you process the same sample twice, you don't usually do it on the same
day, or if you do, you're aware of it and give them names like A and B.

> *Unique identifiers*
> Unique identifiers are a unique name for a sample or set of sequencing data. > They are names for that data that only exist for that data. Having these
> unique names makes them much easier to track later.
{: .callout}

## Data about the experiment

Basically the spreadsheet lesson using the E. coli metadata

TODO: Create messy spreadsheet metadata with the E. coli data

> *Metadata standards*
> Many fields have particular ways that they structure their metadata so it's
> consistent and can be used across the field. Some examples of metadata
> standards are ...
>
> What are the minimum metadata standards for your experiment/datatype -
>
> [Biosharing.org's listing of minimum information standards](https://biosharing.org/standards/?selected_facets=isMIBBI:true&selected_facets=domains_exact:DNA%20sequence%20data)
{: .callout}

## Working with sequence data

1. What challenges do you think you'll face (or have already faced) in working with a large sequence dataset?
2. What is your strategy for saving and sharing your sequence files?
3. How can you be sure that your raw data aren't unintentionally uncorrupted?
4. Where/how will you (did you) analyze your data - what software, what computer(s)?

### Submission of samples to the sequencing center

> # Exercises
>
> ## **A. Sending samples to the facility**
>
> The first step in sending your sample for sequencing will be to complete a
> form documenting the metadata for the facility. Take a look at the following
> submission spreadsheet.
>
> [Sample submission sheet](./sample_submission.txt)*<br> **FIXLINK**
> *Download the file using right-click (PC)/command-click (Mac). This is a
> tab-delimited text file; try opening it with Excel or another spreadsheet >
program.
{: .challenge}

### **Questions**

1. What are some errors you can spot in the data?
-  Typos, missing data, inconstancies?
2. What improvements could be made to the choices in naming?
3. What are some errors in the spreadsheet that would be difficult to spot? Is there anyway you can test this?


### Retrieving samples from the facility

When the data come back from the facility, you will receive some documentation (metadata) as well as the sequence files themselves. Download and examine the following file - here provided both as an excel and a text file:

- [Sequencing results - excel](http://de.iplantcollaborative.org/dl/d/94749C20-0DA6-45A6-8CA0-11D6A7C75E78/sequencing_results_metadata.xls) **FIXLINK**
- [Sequencing results - text](./sequencing_results_metadata.txt) **FIXLINK**

### **Questions**

1. How are these samples organized?
2. If you wanted to relate file names to the sample names submitted above (e.g. wild type...) could you do so?
3. What do the \_R1/\_R2 extensions mean in the file names?
4. What does the '.gz' extension on the filenames indicate?
5. What is the total file size - what challenges in downloading and sharing these data might exsist?

## Summary

Before analysis of data has begun, there are already many potential areas for errors and omissions. Keeping organized and keeping a critical eye can help catch mistakes.

One of Data Carpentry's goals is to help you achieve *competency* in working with bioinformatics. This means that you can accomplish routine tasks, under normal conditions, in an acceptable amount of time. While an expert might be able to get to a solution on instinct alone - taking your time, using Google, and asking for help are all valid ways of solving your problems. As you complete the lessons you'll be able to use all of those methods more efficiently.

## Where to go from here

Why not everyone needs to be an expert in everything -

L. Welch, F. Lewitter, R. Schwartz, C. Brooksbank, P. Radivojac, B. Gaeta and M. Schneider, **'Bioinformatics Curriculum Guidelines: Toward a Definition of Core Competencies'**, PLoS Comput Biol, vol. 10, no. 3, p. e1003496, 2014.
