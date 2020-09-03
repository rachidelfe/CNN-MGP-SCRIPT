
CNN-MGP
=========

Convolutional Neural Networks for Metagenomics Gene Prediction(CNN-MGP)


# Main Description

The script predict genes from metagenomic file :

* **command line mode**
  *  See `CNN-MGP -h`
  * CNN-MGP parametre
  * -i 
    * Input fasta file name
  * -o
    * The name of the output file
  * -min
    * Minimum ORF length to be considered when running the script
  * -st
    * Specify the type of output you want to generate (i.e., protein translated gene, nucleotide CDS, or both)
    * Nucl or Prot or Both

  * -u
    * specify the type of start codon. For unresolved codons(ie, ATG, CTG, GTG, TTG) Type 1. Or Type 0 for just ATG as codon start.
* **interactive mode**
  * execute the scripts with no arguments
    * provide each argument as an input 

# Setup

## install python 3.7.7
* install python 3.7.7 (64bit) from the officiel website [Python 3.7.7](https://www.python.org/downloads/release/python-377/)  

## install requirements.txt
* pip install -r requirements.txt
