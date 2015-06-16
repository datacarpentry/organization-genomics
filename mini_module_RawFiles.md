**What do we mean by raw data?**
Depending on what sequencing facility you use and what services you buy, your sequencing data may arrive in one of several formats, but likely you will get a compressed version of your data (a .tar or .gz file). This file (or files) is your raw data. Your data is compressed, because modern sequencers give huge amounts of data; a single lane of 100bp paired end Illumina reads may give you 100 gigabytes of sequence.

**Raw data needs to stay raw**
The raw data you get from your sequencing facility is virtually irreplaceable. 
Since sequencing facilities process many samples from many labs, most can only afford to store these files for a limited time, often only a few weeks. Once your facility has purged their copy of the file, the only way to get that data is to re-run samples, which often means re-doing the entire experiment. This means that you need to protect your raw data not only from accidental loss, but also from irrevocable changes. 

**How to work with your data (without accidently destroying it)
First, you should always get a copy of your data from the sequencing facility as soon as possible, and make that copy READ-ONLY. That means, that you can open your data, look at it, and even make copies of it, but the computer won't let you save any changes to it. To make your date read-only, navigate to the folder that holds the file and then type:
<pre class="sourceCode bash"><code class="sourceCode bash">$ chmod 444 MyRawData</code></pre>
The <code class="sourceCode bash">chmod</code> command calls a program *ch*ange *mod*e, that alters the permissions for a file or directory. It accepts three or four digits, where the first digit is optional, and each of the other three coorosponds to a different level of computer operator: user, group and all. The numerical value of each digit (found in the table below) specifies how each of those operators can interact with the file in question. So <code class="sourceCode bash">$ chmod 444 MyRawData</code> gives everyone (user, group and all) the ability to look at the data file but not to change it.

\# | Permission 
---|-------------
7 | read, write and execute
6 | read and write
5 | read and execute
4 | read only
3 | write and execute
2 | write only
1 | execute only
0 | none

When you want to work with the data file, simply copy it to a new location, and work only with the copy. That way any accidental deletions, or other changes, won't effect your raw data. One simple way to do this is to use <code class="sourceCode bash">rsync</code> instead of <code class="sourceCode bash">cp</code>. 

<pre class="sourceCode bash"><code class="sourceCode bash">$ rsync MyRawData MyWorkingDirectory/datacopy chmod 744 MyRawData</code></pre>
This will make a copy of MyRawData called datacopy in MyWorkingDirectory, and simultanously update the permissions of datacopy to allow the user (you) to read, write and execute (do science on!) that copy, all without editing the content or permissions of MyRawData

**How to best store your raw data**
Remember, the raw data files from your sequencing facility are virtually irreplaceable, so you should always have more than one copy. Discussion of all of the various storage options are beyond the scope of this workshop, but your data storage solution should include at least two (preferably three or more) copies of your data, at widely varying locations and pass the fire test: If one of your data copies is on fire, the rest shouldn't be. Backing up your desktop computer to a harddrive on your desk will save you if a hardrive fails, but not if your office is on fire. 
