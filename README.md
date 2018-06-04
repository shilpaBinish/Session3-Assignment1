# Session3-Assignment1
1. How to Import SAS XPORT files into R with the foreign package?
library(sas7bdat)

# Read in the SAS data
mySASData <- read.sas7bdat("example.sas7bdat")

2. How to Import SAS Files into R with the Haven package?
library(haven)

read_sas("mtcars.sas7bdat")


write_sas(mtcars, "mtcars.sas7bdat")

3. How to read Weka Attribute-Relation File Format (ARFF) files in R?

read.arff(system.file("arff", "contact-lenses.arff",
                      package = "RWeka"))
4. How to read a heavy csv/tsv file using readr package?

# Read a txt file, named "mtcars.txt"
my_data <- read_tsv("mtcars.txt")
# Read a csv file, named "mtcars.csv"
my_data <- read_csv("mtcars.csv")
