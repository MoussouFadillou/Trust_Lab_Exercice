Gaol and approach:
For the task of this exercice the goal was to find pages from the common crawl archive that discuss or are relevant to COVID-19’s economic impact.   My approach was to write a function that will help us to download the first 1000 pages (URL’s) of the warc, wat and wet files in the 2020 common crawl archive.  In fact 
Common Crawl’s archives contains three types of files, all in the WARC format: 

        -WARC files containing the raw crawl data .
        -WAT files containing metadata for the WARC records in a corresponding WARC file.
       - WET files containing plaintext contained in the WARC records in a corresponding WARC file.  I wanted this gaol by using python with warc package and request package since the warc module simplifies working with WARC files and requests  module for the examples And I went to  Data location link and get the path for warc files, wat files and wet files for each month in 2020 by using the indicated index. 

Problem:
For the problem I have a bug that I couldn't fix during the 6 hours.  But i still working on.



