# CHIPseq_SE_discovery
#Discovery of disease or aging related superenhancers
###################
##This depository is a detailed description of how to use cistrome pipeline in galaxy for CHIPseq analysis and how to summarize large ##volume of datasets for disease related superenhancer identification. This serves as a documentation for our current project/paper for ##the discovery of aging/excercise/Alzheimer's disease related sueprenhancers
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
## Peak calling 
