# bioinformatics-pipeline
A set of shell scripts for NGS data analysis. 
Scripts are originally written for BGI, but can be easily adapted for Illumina.

All the used tools can be downloaded here:
These can be browsed from your local tool directory or as modules (second one is better option,but you need to contact your admin first)  
Before using a particular tool, check the version compatibility with other tools

Quality check:
FastQC: https://www.bioinformatics.babraham.ac.uk/projects/fastqc/  
Quality trimming:  
Trimmomatics: http://www.usadellab.org/cms/?page=trimmomatic  
Burrows-Wheeler Aligner  
BWA: https://sourceforge.net/projects/bio-bwa/files/  
BAM file generation:  
Samtools: http://www.htslib.org/  
Variant calling and filtering: (several options)  
Deepvariant: https://github.com/google/deepvariant  
VarScan: https://sourceforge.net/projects/varscan/files/  
GATK4: https://github.com/broadinstitute/gatk/releases  
LoFreq: https://csb5.github.io/lofreq/installation/  
BCFTools: http://samtools.github.io/bcftools/bcftools.html  
VCFTools: https://vcftools.github.io/index.html  

For viral RNA, LoFreq seems to be most suitable variant calling option. However, comparing different vcf tools is recommended before further phylogenetic analysis.
When working with large metagenome data, consinder using best processors available on your machine.
