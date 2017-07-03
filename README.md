# CHIPseq_SE_discovery
#Discovery of disease or aging related superenhancers
###################
##This depository is a detailed description of how to use cistrome pipeline in galaxy and Peakranger for CHIPseq analysis and how to summarize large ##volume of datasets for disease related superenhancer identification. This serves as a documentation for our current project/paper for ##the discovery of aging/excercise/Alzheimer's disease related sueprenhancers
## step 1: patient sample collection and clinical documentation
## step 2: CHIPseq assay on postmortum brain samples (right side)   H3K27Ac genomewide, other factors targeted sequencing

####CHIPseq protocol:  
####   isolation of dentate gyrus and fixation
####   nuclei isolation and clean up by sorting (NeuN for neuron nuclei)
####   Lysis & shearing(Corvaris)
####   pull down and washes
####   elute and reverse crosslink (Allen brain protocol)
####   PCR validation for quality control
####   CHIPseq library prep (try different methods for pushing the limit of starting materials)

## Step 3Analysis

## Alignment using Bowtie2 or BWA 0.7.12
## BAM to BED, upload BED file to cistrome in galaxy
## BAM to SAM
## manipulate SAM files to fit cisgenome .aln file requirements




## Peak calling using either cistrome or cisgenome tools
Deal with H3K27 wide peaks:  slide window analysis. Once genomewide peaks are identified, use in-house script to measure differential binding during aging for the targeted regions ( unique counts/base for the identified regions,also plot counts/base distribution plot across the locus of interest) 



