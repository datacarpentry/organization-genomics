---
title: "Project Organization"
teaching: 20
exercises: 10
questions:
- "How to organize a sequencing project"
objectives:
- "Learn how to create a directory file structure for data and analysis at the command line"
-
keypoints:
- "First key point."
---

# Getting your project started

Project organization is one of the most important parts of a sequencing project, but is often overlooked in the
excitement to get a first look at new data. While it's best to get yourself organized before you begin analysis,
it's never too late to start.  

You should approach your sequencing project in a very similar way to how you do a biological experiment, and
ideally, begins with experimental design. We're going to assume that you've already designed a beautiful
sequencing experiment to address your biological question, collected appropriate samples, and that you have
enough statistical power. For all of those steps, collecting specimens, extracting DNA, prepping your samples,
you've likely kept a lab notebook that details how and why you did each step, but documentation doesn't stop at
the sequencer!  

Every computational analysis you do is going to spawn many files, and inevitability, you'll
want to run some of those analysis again. Genomics projects can quickly accumulates hundreds of files across
tens of folders. Do you remember what PCR conditions you used to create your sequencing library? Probably not.
Similarly, you probably won't remember whether your best alignment results were in Analysis1, AnalysisRedone,
or AnalysisRedone2; or which quality cutoff you used.  Creating metadata files and taking notes as discussed in the previous lessons will help here.

Luckily, recording your computational experiments is even easier than recording lab data. Copy/Paste will become
your best friend, sensible file names will make your analysis traversable by you and your collaborators, and
writing the methods section for your next paper will be a breeze. Let's look at the best practices for
documenting your genomics project.   

Your future self will thank you.  


In this exercise we will discuss setting up a filesystem for the project we will be using over the next few days. How you set this up exactly will depend what operating system you're on. The focus here is on the general structure. It is very easy with these bioinformatics pipelines to end up with files all over the place.

For each project it's good to have one project folder.

For this workshop we're going to call that folder 'dc_workshop'

Within the 'dc_workshop' folder we'll create three other ones
- one folder for notes or documentation on the analysis
- one folder for the raw data: the data you're using to start the analysis
- one folder for results: the results from the analyses you're doing

> ## Exercise  
> Whatever operating system you're on, create a project with the following folders:
> * dc_workshop   
> * dc_workshop/docs
> * dc_workshop/data  
> * dc_workshop/results  
{: .challenge}


# Document your activity on the project

In the [shell lesson](http://www.datacarpentry.org/shell-genomics/) we'll work on documenting the analysis steps as a part of the pipeline.

We can also document what we do in text files, like we would for a regular lab notebook. Microsoft Word isn't ideal for this, because its automatic formatting sometimes changes important things.

A couple options likely on your computer right now are TextEdit on Mac and Notepad on Windows.

Other options for taking notes, that you can download (some free or some you have to pay for) are text editors like [TextWrangler](https://www.barebones.com/products/textwrangler/) or [BBedit](https://www.barebones.com/products/bbedit/). Other good options are [EverNote](https://evernote.com) for Mac or [OneNote](https://www.onenote.com) for Windows, or [Atom](https://atom.io). There's also nano, vi or emacs for Linux.

When taking notes, document what you did and why, and as you get your results, it's also useful to document your interpretation, particularly as you try different parameters for a program.

> ## Exercise
> - In some text editing program, open a file
> - Make a note about the directory structure you just set up
> - Save the file in the 'dc_workshop/docs' folder
{: .challenge}

We'll continue to use this model in the other lessons on shell and wrangling. Think about setting up the folder structure this way will be a good basis for an project organization, although there will be some variability depending on the files that you have.

## References
- [A Quick Guide to Organizing Computational Biology Projects](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424)
- [Good enough practices in scientific computing](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510)
- [Computing workflows for biologists](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002303)
