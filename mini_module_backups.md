Any files that are difficult or impossible to replace should be backed up on a regular basis. Depending on what your project is, this may include raw data files, processed data files, programs and scripts, and metadata. Technology is always changing, so it is impossible for this tutorial to provide a complete guide to backups. However, the following considerations should help you narrow down yout backup choices and choose an appropriate one. 

But remember: what's most important is *that* you backup, not *how* you backup.

##Backup Basics: The 3-2-1 rule
>You should always have:
>* 3 Copies of any important data
>* 2 Different types of backup (cloud and tape for instance)
>* 1 Off-site backup (physically as far away from your other backups as possible)

This may sound a bit excessive, but hard-drives fail, buildings catch fire and accidents happen, and there are good reasons for these rules. 

### 3: Copies of any important data
If your data is important enough to back up, it's important enough to keep in triplicate. Just like your main copy, backups can fail. The more copies you have, <a href="https://en.wikipedia.org/wiki/Roy_Sullivan"> the less likely they'll all fail at once.</a> 

### 2: Different types of backup media
There are two good reasons for having multiple media types. First, different media wear out at different rates: <a href="https://www.backblaze.com/blog/how-long-do-disk-drives-last/"> About 6% of harddrives fail per year</a>, and are usually said to have an average lifespan of 3 to 5 years. Consumer grade CDs and DVDs (from a good brand) can last about 5 years, flashdrives can last 10 years, and tapes <a href="http://www.pcmech.com/article/how-long-does-backup-media-last/">perhaps for 50 years</a>. However, it's important to realize that these are <a href="http://www.storagecraft.com/blog/data-storage-lifespan/"> mostly best guesses</a>, and are based on your media being treated perfectly. Also, consider that if you go buy two harddrives today, back up all your data to both and store them in two different places, even with perfect care they're likely to fail at around the same time.
Second, it hedges your technological bets: Theoretically, it will take 50 years for tapes to lose their magnetic charge, but that time can be drastically reduced by temperature, dust...or breaking the reader. Storing all your data in one format increases the chance that you'll have a <a href="http://www.digitaltrends.com/computing/keeping-data-safe-eternity/">great archive that you can't access</a>.  

### 1: Off-site backup
For an experiment, you may do technical replicates and biological replicates. The first is a just a second copy, it can tell you about your pipettes, but doesn't tell you anything about your study system. You can think of computer back-ups in a similar way: if you make a second copy of all your data onto another part of your laptop, you technically have a backup...but it won't be any help if you drop your computer in the stairwell. For a backup to actually be helpful it should be as physically distant as is possible from your main copy. Another building is good, another city is better. Extra points for another continent.

So where should you keep all these data copies? The first thing to consider is: Who you are storing the data *for* and *why*?

The level of accessibility you need can help determine where to store it. Are you storing data for your future self? for you and your collegues to use? for the scientific community? 
* If it's just for you or a few collaborators, a few harddrives or your university HPC might be the easiest option. 
* If many people will be accessing it, cloud options, like <a href="http://aws.amazon.com/"> AWS </a>, <a href="http://datadryad.org/"> DRYAD</a>, <a href="https://osf.io/"> osf.io</a>, or <a href="http://figshare.com/">Figshare</a> might be best.
* If your data is sensitive (like human genomic data), it may be illegal to store in many of the popular online data repositories. Check with your campus HPC or campus librarian, many universites already have data repositories and management plans in place for sensitive research data.
*Scripts and other non-data files can be stored at a public or private <a href="https://github.com/"> Github</a> repository, <a href="https://bitbucket.org/"> Bitbucket</a>, <a href="https://code.google.com/p/support/wiki/GettingStarted"> Google Code</a>, <a href="http://sourceforge.net/"> SourceForge</a> or <a href="http://www.google.com/search?q=online+version+control"> others</a> 

##For more discussion
* <a href="https://github.com/swcarpentry/site/issues/797"> Where should scientists store their data?</a>
* <a href="https://github.com/blog/1840-improving-github-for-science"> Github for Science </a>
* <a href="http://journals.plos.org/ploscollections/article?id=10.1371/journal.pcbi.1003285"> Ten Simple Rules for Reproducible Computational Research</a>
