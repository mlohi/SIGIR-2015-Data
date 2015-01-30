# SIGIR-2015-Data
Mining Article Background in Scientific Literature: HMM-like Structured Modeling

-----------
Description
-----------
This dataset contains papers that come from 4 related conferences, i.e., KDD, WWW, SIGIR, CIKM, from 2001 to 2010. The related reference is also included.

---------------
Data statistics
---------------
15020 papers

66632 valid citation relations

-----
Files
-----
* The data is formatted one paper per file in the corresponding directory categorized by the publication year.

-----------
Data format
-----------
file name: #indexID+#venue+#publication_date

e.g., #index96644#cCIKM#t2008

content:
\#* title  
\#@ author 
\#t publication date
\#c venue
\# reference indexID
...
\# reference indexID
\#! abstract

e.g.,
\#*Data winnowing.
\#@Yoav Freund
\#t2010
\#cKDD
\#index1540897
\#!Massive quantities of ...
