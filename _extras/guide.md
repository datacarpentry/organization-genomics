---
layout: page
title: Instructor Notes
---

## Instructor notes

## Lesson motivation and learning objectives

The purpose of this lesson is *not* to teach how to do data analysis in spreadsheets,
but to teach good data organization and how to do some data cleaning and 
quality control in a spreadsheet program.

## Lesson design

#### [Data tidiness](../01-tidiness/)

* Introduce that we're teaching data organization, and that we're using
spreadsheets, because most people do data entry in spreadsheets or 
have data in spreadsheets.
* Emphasize that we are teaching good practice in data organization and that
this is the foundation of their research practice. Without organized and clean
data, it will be difficult for them to apply the things we're teaching in the
rest of the workshop to their data.
* Much of their lives as a researcher will be spent on this 'data wrangling' stage, but
some of it can be prevented with good strategies for data collection up front.
* Tell that we're not teaching data analysis or plotting in spreadsheets, because it's
very manual and also not reproducible. That's why we're teaching bash shell scripting!
* Now let's talk about spreadsheets, and when we say spreadsheets, we mean any program that
does spreadsheets like Excel, LibreOffice, OpenOffice. Most learners are probably using Excel.
* Ask the audience any things they've accidentally done in spreadsheets. Talk about an example of your own, like that you accidentally sorted only a single column and not the rest.
of the data in the spreadsheet. What are the pain points!?
* As people answer, highlight some of these issues with spreadsheets.
* Go through the point about keeping track of your steps and keeping raw data raw.
* Go through the cardinal rule of spreadsheets about columns, rows and cells.
* Hand them a messy data file and have them pair up and work together to clean up the data.

#### [Planning for NGS projects](../02-project-planning/)

* This episode depends on learners discussing exercises with one another. Be sure to give plenty of time for this discussion.

#### [Examining Data on the NCBI SRA Database](../03-ncbi-sra/)

* Learners should *not* actually download the ENA files in the "Downloading a few sequencing files: EMBL-EBI" section. 

#### Concluding points

* Now your data is organized so that a computer can read and understand it. This
lets you use the full power of the computer for your analyses as we'll see in the
rest of the workshop. 

## Working with participants' level of expertise

Learners may be taking this lesson for many reasons - they may be just thinking of maybe doing a sequencing experiment, they may be trying to analyse public data, they may have already generated their own data, they may be speculatively acquiring new skills.

You should feel free to "read the room", and it can be helpful to ask more specifics in a pre-workshop survey.

#### [Data tidiness](../01-tidiness/)

Discussion 1, "What kinds of data and information have you generated before you sent your DNA/RNA off for sequencing?" can go very differently depending on the participants' background. Many instructors make adjustments to this section, and they should, depending on the learners. 

Some instructors have succeeded in adding ice-breaker questions and more on scientific background to discussion 1, such as:

* What's your name? 
* What kind of sequencing data are you collecting? 
* What question is your experiment answering? 
* What kinds of data and information have you generated before you sent your DNA/RNA off for sequencing?

This had some positive points:

* instructors got to see the range of projects being worked on (metagenomics, RNA-seq, DNA-seq, etc).
* we had a good discussion about linked metadata, e.g. a plant scientist also takes photos of their plants, an ecologist has site sampling data.
* learners got to share lessons they'd learned.
* for some learners, it may have been the first time they'd thought about it.
* it only added 5 minutes.

The drawback:
* only about 1/2 of learners got to the point of talking about file types of that data.

It could be more efficient to ask these questions in the pre-workshop survey, then present the range of answers during the class. It can also be helpful for instructors and helpers to share what they work on.

## Technical tips and tricks

Provide information on setting up your environment for learners to view your 
live coding (increasing text size, changing text color, etc), as well as 
general recommendations for working with coding tools to best suit the 
learning environment.

## Common problems

#### Excel looks and acts different on different operating systems

The main challenge with this lesson is that Excel looks very different and how you
do things is even different between Mac and PC, and between different versions of
Excel. So, the presenter's environment will only be the same as some of the learners. 

We need better notes and screenshots of how things work on both Mac and PC. But we
likely won't be able to cover all the different versions of Excel. 

If you have a helper who has more experience with the other OS than you, it would be good
to prepare them to help with this lesson and tell people how to do things in the other OS.

#### People are not interactive or responsive on the exercises

This lesson depends on people working on the exercise and responding with things
that are fixed. If your audience is reluctant to participate, start out with
some things on your own, or ask a helper for their answers. This generally gets
even a reluctant audience started. 

