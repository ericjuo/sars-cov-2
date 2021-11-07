# SARS-CoV-2
A collection of information about SARS-CoV-2 virus

##  &#128161;Questions
--- 
###  What is SARS-CoV-2 virus?
Severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2) is a highly transmissible virus that causes coronavirus disease (COVID-19). SARS-CoV-2 belongs to coronaviruses - a family of enveloped positive-strand RNA viruses. The GC content of SARS-CoV-2 genome is 37%, which is lower than the mean GC content of other coronavirus (39%). The neucleotide composition of the SARS-CoV-2 genome are A(29%), T(32%), C(18%), G(19%).


###  What are symptoms after SARS-CoV-2 infection?


###  Where is the origin of SARS-CoV-2?


###  How does SARS-CoV-2 transmit?

###  How is the progress of SARS-CoV-2 vaccine development?

###  What are the technology used in each type of vaccine?

###  How is the progress of drug development for treating COVID-19?

###  What is SARS-CoV-2 variant?

###  How do variants escape immunity obtained from vaccination?

## &#128214;Mini Projects
--- 
-   Basic statistics of SARS-CoV-2 genome.
    -   Download SARS-CoV-2 ref seq through command line.
-   Phylogenetic Tree of Coronaviruses

## &#128757;Progress
--- 
### Download SARS-CoV-2 refseq in the NCBI's nucleotide database on the Bash command line.
[EDirect](https://www.ncbi.nlm.nih.gov/books/NBK179288/) is a method provide by NCBI to access NCBI's databases from a Unix terminal window.  

Install EDirect through command line on Windows PC.  
```bash
#!/bin/bash
sh -c "$(curl -fsSL ftp://ftp.ncbi.nlm.nih.gov/entrez/entrezdirect/install-edirect.sh)"
```
Download SARS-CoV-2 refseq (Accession: NC_045512) from NCBI Nucleotide database.  
```bash
#!/bin/bash

efetch -db nucleotide -id NC_045512 -format fasta > NC_045512.fasta
```

## &#128218;Resources
--- 
### SARS-CoV-2 general information
-   https://www.who.int/health-topics/coronavirus#tab=tab_1 
-   https://www.nature.com/articles/s41564-020-0695-z 

### Retrieve Data from databases
-   https://www.ncbi.nlm.nih.gov/books/NBK179288/

### GC content of RNA viruses
-   https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7114242/
-   https://www.mdpi.com/1999-4915/12/5/498/htm#B24-viruses-12-00498



