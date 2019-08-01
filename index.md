---
layout: lesson
root: .
---

Good data organization is the foundation of any research project. It not only sets you up well for an analysis, but it also makes it easier to come back to the project later and share with collaborators, including your most important collaborator - future you.

Organizing a project that includes sequencing involves many components. There's the experimental setup and conditions metadata, measurements of experimental parameters, sequencing preparation and sample information, the sequences themselves and the files and workflow of any bioinformatics analysis. So much of the information of a sequencing project is digital, and we need to keep track of our digital records in the same way we have a lab notebook and sample freezer. In this lesson, we'll go through the project organization and documentation that will make an efficient bioinformatics workflow possible. Not only will this make you a more effective bioinformatics researcher, it also prepares your data and project for publication, as grant agencies and publishers increasingly require this information.

In this lesson, we'll be using data from a study of experimental evolution using *E. coli*. [More information about this dataset is available here](http://www.datacarpentry.org/organization-genomics/data/). In this study there are several types of files:

- spreadsheet data from the experiment that tracks the strains and their phenotype over time
- spreadsheet data with information on the samples that were sequenced - the names of the samples, how they were prepared and the sequencing conditions
- the sequence data

Throughout the analysis, we'll also generate files from the steps in the bioinformatics pipeline and documentation on the tools and parameters that we used.

In this lesson you will learn:

- How to structure your metadata, tabular data and information about the experiment. The metadata is the information about the experiment and the samples you're sequencing.
- How to prepare for, understand, organize and store the sequencing data that comes back from the sequencing center
- How to access and download publicly available data that may need to be used in your bioinformatics analysis
- The concepts of organizing the files and documenting the workflow of your bioinformatics analysis

> ## Getting Started
>
> This lesson assumes no prior experience with the tools covered in the workshop. 
> However, learners are expected to have some familiarity with biological concepts,
> including the 
> concept of genomic variation within a population. Participants should bring their laptops and plan to participate actively. 
>
> This lesson is part of a workshop that uses data hosted on an Amazon Machine Instance (AMI). Workshop participants will be given 
> information on how
> to log-in to the AMI during the workshop. Learners using these materials for self-directed study will need to set up their own
> AMI. Information on setting up an AMI and accessing the required data is provided on the [Genomics Workshop setup page](http://www.datacarpentry.org/genomics-workshop/setup.html).
{: .prereq}

> ## For Instructors
> If you are teaching this lesson in a workshop, please see the
> [Instructor notes](guide/).
{: .prereq}
