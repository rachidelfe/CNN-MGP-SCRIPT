
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
    * Output fasta file name
  * -min
    * Minimum ORF length
  * -st
    * Specify the type of output you want to generate (i.e., protein translated gene, nucleotide CDS, or both)
    * nucl or prot or both

  * -u
    * specify the type ofstart codon unresolved codons(ie, ATG, CTG, GTG, TTG).or just codon start ATG
* **interactive mode**

  * provide each argument as an input 

# Setup

## install python 3.7.7
* install python 3.7.7 (64bit) from the officiel website [Python 3.7.7](https://www.python.org/downloads/release/python-377/)  

## install tensorflow 2.3.0 
* Windows : 

 * install the Microsoft Visual C ++ Redistributable package for Visual Studio 2015, 2017, and 2019. As of TensorFlow version 2.1.0, the msvcp140_1.dll file contained in this package is required [Visual C ++](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads/)  

 * Make sure long paths are enabled on Windows [long paths](https://superuser.com/questions/1119883/windows-10-enable-ntfs-long-paths-policy-option-missing/)  

 * install tensoflow using pip3 
   `pip3 install tensorflow==2.3.0`

* Ubuntu 

 * `pip3 install tensorflow==2.3.0`


## install numpy

* pip3 install numpy

## install tqdm
* keeps 
 * pip3 install tqdm
