## Case-Studies-In-Functional-Genomic
# Course outline
This course will have 3 topics: RNA-seq, DNA methylation, and ChIP-seq.

The first two topics (RNA-seq and DNA methylation) have lecture content along with screencasts involving analyzing data using R and Bioconductor. These will have assessments which require that the student run some code using R/Bioconductor software and report their answers. We will provide instructions on installing R and Bioconductor when we get to the first data analysis unit in RNA-seq.

The last topic, ChIP-seq, is lecture content along with some software screencasts, with assessments designed to test student comprehension of the lecture material. The software typically used to analyze ChIP-seq data is mostly designed for Linux and does not involve R/Bioconductor (although there are increasing more packages showing up on Bioconductor for ChIP-seq analysis). Most of our students do not have the capability to run software on the command line (Linux or Unix), therefore the ChIP-seq topic does not have assessments which require running software.

The RNA-seq and DNA methylation content is prepared by the group of Rafael Irizarry and the ChIP-seq content is prepared by the group of X. Shirley Liu.

Here is a quick overview of the RNA-seq material:

# Introduction to RNA-seq: basic concepts of RNA-seq: lectures
# RNA-seq bioinformatics: first look at FASTQ files; aligning RNA-seq reads; visualizing alignments: screencasts
# Normalization of read counts: counting RNA-seq reads or fragments in genes; properties of Poisson and ratios, exploratory data analysis (EDA) and variance stabilization: lecture and screencasts
# Differential expression at the gene-level: count-based differential expression; surrogate variable analysis: screencasts
# Differential expression across isoforms: differential exon usage; inferring expression of transcripts: screencasts
The videos in the class were recorded in 2014 and 2015.

NOTE: The Rmd code, quiz questions and answers, and the book pages have been updated in 2016 to match the latest version of R (3.2.4) and Bioconductor (3.2). Read about how to install R at the Getting Started page.

Additional links to relevant literature and software published in 2015 and 2016 have been added to the edX site.

NOT COVERED in RNA-seq
although still very important:

# allele-specific expression (e.g. as described by Pickrell et al)
# expression quantitative-trait loci (eQTL)
# de-novo transcriptome assembly (e.g. as performed by the Trinity or Cufflinks algorithms)
# single-cell RNA-sequencing
# "single molecule sequencing" (e.g. PacBio sequencing)
# extensive details on RNA-seq lab protocols
# New, fast pseudo-alignment methods (Sailfish, Salmon, kallisto). I will have a short comment on using these tools with Bioconductor statistical packages at the end of the differential gene expression section. 
Note : that RNA-seq analysis is a very large topic, and this short course will only touch on the basics. A good resource for further exploration:

The RNA-seqlopedia from the Cresko Lab of the University of Oregon.
