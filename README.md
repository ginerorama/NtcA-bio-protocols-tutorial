# Bioinformatic tutorial for NtcA ChIP-seq analysis 
![alt text](https://github.com/ginerorama/NtcA_bio-protocols_tutorial/blob/master/header-logo.png "Logo Title Text 1")

This repository is used to store the code and raw material for the ChIP-seq bioinformatic tutorial of _Synechocystis'_ NtcA published in bio-protocols.

citations:_Joaquín Giner-Lamia*, Miguel Hernández-Prieto, M.E. Futschik_. "ChIP-seq Experiment and Data Analysis in the Cyanobacterium Synechocystis sp. PCC 6803". 2018. _bio-protocols_

*To whom correspondence should be addressed:jginer[AT]cnb.csic.es


The data deposited in this project comes from a series of ChIP-seq experiments to the aims of analyse the regulon of NtcA in conditions of low and high avilability of nitrogen. The analysis of these data can be found at:

_Joaquin Giner-Lamia et al.,_ Identification of the direct regulon of NtcA during early acclimation to nitrogen starvation in the cyanobacterium Synechocystis sp. PCC 6803. 2017._Nucleic Acids Res_.


Note: Fastq files presents in this repository has been modify to minimize the computational time consuming for the bioinformatic analysis during the protocols. Thus files presents in this repository contains only 1% of total reads presents in the original ChIP-seq files.

The original fastq files are available at Gene Expression Omnibus(GEO) with the accession number: GSE97291.


## **Files description:**

Here you can find all the files neccesaries for this tutorial.

[**N_input.fastq:**](https://github.com/ginerorama/NtcA_bio-protocols_tutorial/blob/master/N_input.fastq.zip) input sample from _Synechocystis_ cells grown 4 hours in absence of nitrogen.

[**N_ChIP.fastq:**](https://github.com/ginerorama/NtcA_bio-protocols_tutorial/blob/master/N_ChIP.fastq.zip) ChIP-seq sample from _Synechocystis_ cells grown 4 hours in absence of nitrogen.

[**NH4_input.fastq:**](https://github.com/ginerorama/NtcA_bio-protocols_tutorial/blob/master/NH4_input.fastq.zip) input sample from _Synechocystis_ cells grown 4 hours in presence of ammonium.

[**NH4_ChIP.fastq:**](https://github.com/ginerorama/NtcA_bio-protocols_tutorial/blob/master/NH4_ChIP.fastq.zip) ChIP-seq sample from _Synechocystis_ cells grown 4 hours in presence of ammonium.

[**Syn6803.genome:**](https://github.com/ginerorama/NtcA_bio-protocols_tutorial/blob/master/syn6803.genome) IGV genome file of _Synechocystis_ created using .fasta and .GFF from the          Synechocystis sp. PCC 6803 Refseq                 genome NC_000911.1

[**NC_000911.1.fasta:**](https://github.com/ginerorama/NtcA_bio-protocols_tutorial/blob/master/NC_000911.1.fasta) _Synechocystis_ sp. PCC6803 genome in .fasta format                

[**NC_000911.1.gff:**](https://github.com/ginerorama/NtcA_bio-protocols_tutorial/blob/master/NC_000911.1.gff) _Synechocystis_ sp. PCC6803 genome in .gff format  

**command_lines.txt**: all command lines used in this tutorial

Note: while all_files folder contains all the files generated in this tutorial(including intermediate and final files), in the scripts folder users can find all the scripts used during this tutorial.




