This folder contains the files for homework5.

The program (Rmd file) reads files yob2015 & yob2016 which contain popular names and their counts for years 2015 & 2016.
The program filters the data, merges the data, and outputs the top 10 girl names to a csv file.

Credits: StackOverFlow, Helpful Packages: rvest, stringr, knitr, tidyr, diplyr

Input Files
-----------
yob2015.txt: Baby Names for 2015
yob2016.txt: Baby Names for 2016

Output Files
------------
SBramhall_HW5_MSDS6306_Sect404.Rmd: R markdown file with code
SBramhall_HW5_MSDS6306_Sect404.html: R markdown output showing all code and code outputs
TopGirlNames.csv: Output file with top 10 girl names

Libraries
---------
rvest
dplyr
tidyr
stringr
knitr
kableExtra
ggplots

Variables
---------
df: data frame for data in yob2016.txt file
nameFound: "Fionayyy", duplicated and mispelled name with yyy at the end 
y2016: data frame for data in yob2016.txt file with "Fionayyy" removed
y2015: data frame for data in yob2015.txt file
final: merged y2015 & y2016 data frames
girlnames: all girl names
topgirlnames: top 10 girl names


