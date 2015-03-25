#Best practices
If you're starting out a brand new project, it's easy to begin in an organized way. However, many of us inherit data that's organized in idiosyncratic ways that may work for the creator, but might not fit into your organization style, or aren't arranged in a way that public databases like NCBI will accept.

We've compiled a list of common data issues, and some suggestions for Good, Better and Best practices. If you're begining with all new data, we suggest you try for Best in each instance, but also offer suggestions for improving the organization of legacy data to get it into public database formats.

Naming standards

Column Headers

Your datasheets and metadata sheets should have column names that are meaningful both to you and to other people who may use your data. If you intend to import this data into R, Python or other program, avoid spaces and non-standard characters.

Good

Name your columns something as short as possible while still being unique and descriptive. Make column comments with an extended description of each column header and any abbreviations in the data sheet.

Better

Best

You can use the Biocode Field Information Management System to generate datasheets with globally acccepted field names. Click on Tools to get started.

Unique Sample Names

Each of your samples should have a unique identifier, and a set of standardized metadata. Avoid names that look like dates (Dec14), times (AM1245) and other things that Excel might auto-convert.

Good

Add a column to your dataset starting with MyLab1, MyLab2...MyLabN, so each sample gets a unique ID

Better

Best

Genomics Data Standards The Global Genome Biodiversity Network (GGBN) was formed in 2011 with the principal aim of making high-quality well-documented and vouchered collections that store DNA or tissue samples of biodiversity, discoverable for research through a networked community of biodiversity repositories. This is achieved through the GGBN Data Portal (http://data.ggbn.org), which links globally distributed databases and bridges the gap between biodiversity repositories, sequence databases and research results. Global Genome Biodiversity Network (GGBN): GGBN Data Standard Terms: http://terms.tdwg.org/wiki/GGBN_Data_Standard

Dates, times and temperatures

In the field, it's often easiest to write collection dates in a familiar format, but programs like R and Excel may do very weird things with dates.

Good

Seperate dates into three (or more) unambiguous columns, minimally Day, Month, Year. If your data is finer grained, also use Hours, Minutes, Seconds, etc.

Better

Whatever the number of your date levels, ensure that every individual has every cell filled in. Be especially careful of numbers like times which Excel may reformat from "00" to " ", and may be interpreted as missing data in downstream analysis.

Best

Follow the good and better practices, and also: In your README, note important meta-meta-data that seems obvious now, but might be difficult to remember later. For example, whether you used 12 or 24 hour time, what temperature scale you used, and what your zero point means. If the data was collected across different time zones, be sure that the timezone has it's own column, and note in your meta-meta-data file whether you've standardized the time (i.e. Were your 5pm and 6pm measurements that were done in adjecent time zones done at the same physical time? or an hour apart?) Add an extended description of each column header and any abbreviations in the data sheet,
