# Hackbio_Genomics_2a Task: Identification of Somatic and Germline Variants from Tumor and Normal Sample pairs
## Read Mapping
Hackbio Team (Genomics_2a) decided to replicate a tutorial on the 'Identification of Somatic and Germline Variants from Tumor and Normal Sample pairs' using Galaxy or Linux workflows. Members of the team would be working on different steps in NGS Bioinformatic pipeline (from Raw data processing to Variant annotation). This documentation is focused on read mapping.

Once the sequence reads have been filtered and trimmed, read mapping or alignment is the next step in the bioinformatic pipeline. Read mapping is the process of aligning a set of reads to a reference genome to determine their specific genomic location. Several tools are available for read mapping but BWA-MEM (Galaxy Version 0.7.17.2) was used for our analysis as it is faster, accurate and supports paired-end reads. Read mapping was performed independently for the normal and tumor tissue using thesame parameters except otherwise stated.

Paramaters
- Locally cached human hg19 reference genome, Paired end reads, Forward and reverse trimmed reads (output of trimmomatic), Set read groups (SAM/BAM specification), auto-assign (no), Read Group Identifier (231335 for normal tissue and 231336 for tumor tissue), Read group sample name (normal for normal tissue and tunnor for tumor tissue), 
- For parameters not listed, default setting was used.	
	
