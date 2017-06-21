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
- "First key point."
---

# Lesson 

There are a variety ways to approach working with a large sequencing dataset. You may be a novice who has not used bioinformatics tools beyond doing BLAST searches. You may have bioinformatics experience with other types of data and are working with high-throughput (NGS) sequence data for the first time. Either way, these lessons are for you! In the most important ways, the methods and approaches we need in bioinformatics are the same ones we need at the bench or in the field - planning, documenting, and organizing  will be the key to good reproducible science. 

# Discussion Questions

Before we go any further here are some important questions to consider. If you are learning at a workshop, please discuss these questions with your neighbor (this is a good chance to introduce yourself) and your instructors will collect your answers (on minute cards or in the Etherpad).

### **Metadata** 

1. What is your definition of metadata?
2. What kinds of metadata might a sequencing project generate?

### **Working with sequence data**

1. What challenges do you think you'll face (or have already faced) in working with a large sequence dataset?
2. What is your strategy for saving and sharing your sequence files?
3. How can you be sure that your raw data are unintentionally uncorrupted?
4. Where/how will you (did you) analyze your data - what software, what computer(s)?

# Exercises

## **A. Sending samples to the facility**

The first step in sending your sample for sequencing will be to complete a form documenting the metadata for the facility. Take a look at the following submission spreadsheet. 

[Sample submission sheet](./sample_submission.txt)*<br>
> *Download the file using right-click (PC)/command-click (Mac). This is a tab-delimited text file; try opening it with Excel or another spreadsheet program. 

### **Questions**

1. What are some errors you can spot in the data?
-  Typos, missing data, inconstancies?
2. What improvements could be made to the choices in naming?
3. What are some errors in the spreadsheet that would be difficult to spot? Is there anyway you can test this?


## **B. Retrieving samples from the facility**

When the data come back from the facility, you will receive some documentation (metadata) as well as the sequence files themselves. Download and examine the following file - here provided both as an excel and a text file:

- [Sequencing results - excel](http://de.iplantcollaborative.org/dl/d/94749C20-0DA6-45A6-8CA0-11D6A7C75E78/sequencing_results_metadata.xls)
- [Sequencing results - text](./sequencing_results_metadata.txt)

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

What are the minimum metadata standards for your experiment/datatype - 

[Biosharing.org's listing of minimum information standards](https://biosharing.org/standards/?selected_facets=isMIBBI:true&selected_facets=domains_exact:DNA%20sequence%20data)

Why not everyone needs to be an expert in everything - 

L. Welch, F. Lewitter, R. Schwartz, C. Brooksbank, P. Radivojac, B. Gaeta and M. Schneider, **'Bioinformatics Curriculum Guidelines: Toward a Definition of Core Competencies'**, PLoS Comput Biol, vol. 10, no. 3, p. e1003496, 2014.