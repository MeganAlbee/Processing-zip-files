# Processing Zipped Files
This project established the groundwork for the Wedge Co-Op data engineering repo. Through this project, I am able to transform irregular, inconsistent transactional data into a uniform format for analysis.


# Project Intro/Objective

This repository outlines a process for aggregating information from a series of zip files containing Wedge Co-Op transaction data. The data is read one file at a time and stored in a Pandas dataframe, with the delimiter and header row determined using the CSV sniffer. The information from each file is then stored in an empty data frame called `wedge_summary` which contains columns for file name, number of rows, number of unique card numbers and number of dates.

<b>This Project uses Python and the following libraries: </b>

* pandas 
* numPy
* datetime
* csv 
* os
* re
* io
* janitor
* zipfile

***The Python zipfile module is a standard library intended to manipulate ZIP files, a widely adopted industry standard for archiving, compressing, packaging together related files, reducing file size, and facilitating data exchange over computer networks.


# Key learnings 

1. Python for loops can be used to unzip files one at a time.
2. CSV sniffer can be used to determine the file delimiter and header row.
3. Processing data correctly is necessary for a comprehensive data analysis.